---
type: bot-memory
memory_type: operating-preference
created: 2026-06-22
updated: 2026-06-22
tags:
  - bot-memory
  - bot/Avantchybot
  - memory-capture
---

# Memory Capture Command

When the user says "บันทึกเรียนรู้ในระบบ" or similar wording, treat it as an instruction to save the current durable learning into Avantchybot's canonical memory repo.

If the learning content is clear from the immediate conversation, save it directly in the relevant memory note, update `00-Index.md` when adding a new note, then commit and push when possible.

If the learning content is not clear, ask a brief clarification question before saving new substantive facts.
