---
type: bot-memory
memory_type: detailed-topic
bot: Avantchybot
created: 2026-05-16
updated: 2026-06-13
tags:
  - bot-memory
  - Avantchybot
  - platform
  - trello
  - performance
---

# Staff Performance Platform Idea

User asked to create a platform to upload employee work and connect it to Trello, then summarize weekly staff performance.

## Desired Capabilities

- Upload employee outputs.
- Connect or map to Trello cards/tasks.
- Weekly performance summaries.
- Infographic per person.
- Track work count, duration, owner, follow-up, feedback, and development guidance.

## Design Direction

- Useful for management, not decorative.
- Should support fair review and actionable coaching.

## Evaluation Philosophy

- Preferred framing: "Daily Evidence & Growth Review System" / "ระบบบันทึกผลงานรายวันและติดตามการพัฒนา" rather than a raw performance leaderboard.
- Core intent: evaluate whether work is real, evidence is trustworthy, the person is improving, output has impact, and compensation decisions can be justified fairly.
- Avoid toxic ranking: do not reduce performance to "who submitted the most" or a single raw score.
- Use daily logs as evidence for coaching, growth tracking, and compensation readiness, not as punishment.
- Key phrase to preserve: "เราไม่ได้วัดว่าใครส่งเยอะที่สุด แต่วัดว่าใครมีผลงานจริง เห็นพัฒนาการจริง และมีหลักฐานพอให้บริษัทตอบแทนได้อย่างยุติธรรม"

## Recommended Review Dimensions

Use five dimensions for now:

1. Evidence Completeness - whether supporting evidence exists and is accessible.
2. Output Clarity - whether the actual completed work is understandable and verifiable.
3. Work Impact - whether the work affected project, client, company, revenue, cost, risk, or delivery.
4. Personal Growth Trend - whether the person improves relative to their own baseline.
5. Ownership / Reliability - whether they follow through, handle blockers, and hand off clearly.

AI/tool usage should be excluded from performance scoring for now. It may be tracked as optional context for training, workflow improvement, or future capability development, but should not affect review level, readiness level, coaching status, or compensation decisions at this stage.

## Operating Rules

- Separate personal performance review from team operation health.
- Personal review should focus on actual working days, growth, evidence quality, coaching, and compensation readiness.
- Team operation dashboards may track workload, OT, leave, daily coverage, blocker frequency, delivery risk, and lead capacity, but these should not directly become personal performance penalties or rewards.
- Leave, holidays, and OT should be context/status data, not direct performance score inputs.
- Handoff should be context/explanation input, not a scoring formula. Daily credit follows what the person actually did that day.
- Use two cutoffs: 21:00 daily snapshot and 09:30 next-day correction window. Communicate 21:00 as the primary submission time and 09:30 as correction close, not normal submission time.
- First 3 months should be calibration/probation-style for the system and everyone: month 1 adoption, month 2 quality, month 3 compensation readiness.
- Friendly to honest mistakes, strict against fake evidence.
- Daily submission must be simple enough that a person doing real work can submit in 3-5 minutes, including via mobile/Telegram if possible.

## Visibility And Compensation

- CEO/Management/PM/Lead can see full data for operational performance management and talent visibility, with shared usage principles rather than heavy access controls.
- Employees should see their own status, growth/readiness level, anonymized benchmark, gaps, and improvement actions, not raw scores of colleagues.
- Use privacy-safe names such as Growth Track, Performance Tier, Evidence Level, Readiness Level, or Review Status rather than Salary Band.
- Compensation should be tied to reviewed readiness/eligibility, not automatic raw scores.
- Suggested flow: daily evidence -> AI/Lead interpretation -> individual trend -> coaching -> 3-month verified trend -> top-up/salary review support.
