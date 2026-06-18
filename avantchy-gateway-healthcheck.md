---
type: bot-memory
memory_type: operations
bot: Avantchybot
created: 2026-06-18
updated: 2026-06-18
tags:
  - bot-memory
  - Avantchybot
  - hermes
  - healthcheck
---

# Avantchy Gateway Healthcheck

Avantchybot has a local launchd health check for the Hermes gateway:

- Script: `/Users/Maripae/.hermes/profiles/codexbot/bin/hermes-codexbot-healthcheck`
- Health LaunchAgent: `/Users/Maripae/Library/LaunchAgents/ai.hermes.gateway-codexbot-healthcheck.plist`
- Heartbeat LaunchAgent: `/Users/Maripae/Library/LaunchAgents/ai.hermes.gateway-codexbot-heartbeat.plist`
- Health interval: every 300 seconds.
- Heartbeat: daily at 09:00 local time.
- Alert target: Telegram DM `8781928731` (Cholrit / Avantchybot Home).
- Log: `/Users/Maripae/.hermes/profiles/codexbot/logs/codexbot-healthcheck.log`
- State: `/Users/Maripae/.hermes/profiles/codexbot/tmp/healthcheck/state.env`

The script checks whether `ai.hermes.gateway-codexbot` is running, reads Telegram connection state from `gateway_state.json`, scans new `gateway.error.log` bytes for `token_expired` and Telegram network errors, and runs `launchctl kickstart -k gui/$(id -u)/ai.hermes.gateway-codexbot` if the gateway is not running.

If the alert says `auth_expired`, the likely fix is to refresh Codex/OpenAI auth for the profile and restart the gateway service.
