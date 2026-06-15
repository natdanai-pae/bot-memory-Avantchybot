---
type: bot-memory
memory_type: detailed-topic
bot: Avantchybot
created: 2026-05-16
updated: 2026-06-15
tags:
  - bot-memory
  - Avantchybot
  - presentation
  - design
---

# Presentation And Design Output Preferences

## Output Preferences

- User asked for PDF/slide report, not only Markdown, because Thai `.md` was hard to read.
- Slides should be concise, not over 5 pages when requested.
- Include user's photo and selected works when creating profile/personal branding slides.
- User likes concise, modern, creative design.
- Chula-branded outputs should use Chula fonts and Chulalongkorn visual tone when appropriate.
- When the user requests an image or file, deliver it as a visible chat attachment every time, not just a local filesystem path or Codex preview.
- For Telegram image/file delivery, always send the local artifact as a native attachment using Hermes `send` with `MEDIA:<local_path>` to `telegram:8781928731`; Codex `view_image`/inline previews may not appear in the user's Telegram chat and should not be treated as delivered.
- User explicitly praised the successful native Telegram attachment delivery on 2026-06-08 and asked to remember this exact behavior: show images directly in the chat this way as the default standard.

## Design Quality Bar

- User expects graphic design to meet a professional design standard, not only clean formatting.
- For infographic work, the quality of the summarized source information must meet the same standard as the visual design. The user explicitly emphasized on 2026-06-15 that the reference infographic is the required benchmark for both content summarization and infographic presentation quality.
- Before designing an infographic, distill information into a clear executive structure: key dates, requirements, criteria, process steps, important notes, risks/limits, decisions, and action points where relevant. The summary should be concise, complete enough for decision-making, and arranged so each content block has a clear purpose.
- Avoid dumping raw text into a graphic. Rewrite source material into compact, official, reader-friendly Thai or English as appropriate, with hierarchy, grouped ideas, and callouts that support fast understanding.
- For user-provided style references, study and reproduce the design language carefully before producing slides: symbols/icons, line weight, color tone, size hierarchy, spacing balance, and composition rhythm.
- Do not over-interpret "Chula tone" as generic bright pink/white. When a reference is provided, extract the actual palette and line/shape language from the reference and apply it consistently.
- Infographics should feel designed, not generic: use balanced white space, proportionate iconography, controlled stroke weights, and restrained color blocks.
- User provided flat-design infographic references on 2026-06-05: one management dashboard with top-down meeting table, percent callouts, charts, icons, and gray/blue/yellow/orange accents; one process/teamwork infographic with yellow background, start-to-success flow, dotted arrows, gears, smart ideas, research, strategy, design, communication, and rocket/success symbols. Treat these as preferred references for clear process/management infographics.
- User explicitly identified the 2026-06-15 outbound student exchange procedure infographic as the perfect style reference for his personal infographic taste. Reference image: `assets/2026-06-15-perfect-infographic-style-reference.jpg`.
- For this gold-standard infographic style, preserve these traits: wide landscape dashboard layout; generous white space; calm grid alignment; thin rounded rectangular section borders; controlled pink/magenta accent blocks on white; clean modern sans-serif typography; clear hierarchy with large section numbers and compact text; line-style pictograms; bottom process cards with icon-first reading flow; strong balance between information density and breathing room; minimal decoration; official but accessible tone.
- If uncertain about the intended style, ask for or inspect the reference again before finalizing.

## Image Persona

- User requested photorealistic/reality-style images of “รู้ซิ”.
- Rusi avatar should feel elegant, Thai/Asian, intelligent, charming, and professional.
