---
type: bot-memory
memory_type: detailed-topic
bot: Avantchybot
created: 2026-05-16
updated: 2026-06-18
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
- Design work must use creativity, flexibility, and aesthetic judgment. Adapt composition, visual emphasis, and information architecture to the actual data instead of applying a rigid template. The final work should feel intentionally designed, with both functional clarity and visual grace.
- Do not over-interpret "Chula tone" as generic bright pink/white. When a reference is provided, extract the actual palette and line/shape language from the reference and apply it consistently.
- Infographics should feel designed, not generic: use balanced white space, proportionate iconography, controlled stroke weights, and restrained color blocks.
- For individual or team performance/evaluation infographics, remember to include a 5-axis radar/spider chart when it fits the data. The user had already specified this previously and corrected the assistant again on 2026-06-15 and 2026-06-18: the spider chart should show 5 dimensions, not a generic chart. Use it for Evidence, Clarity, Impact, Growth, and Ownership/Reliability unless the evaluation framework changes.
- User provided flat-design infographic references on 2026-06-05: one management dashboard with top-down meeting table, percent callouts, charts, icons, and gray/blue/yellow/orange accents; one process/teamwork infographic with yellow background, start-to-success flow, dotted arrows, gears, smart ideas, research, strategy, design, communication, and rocket/success symbols. Treat these as preferred references for clear process/management infographics.
- User explicitly identified the 2026-06-15 outbound student exchange procedure infographic as the perfect style reference for his personal infographic taste. Reference image: `assets/2026-06-15-perfect-infographic-style-reference.jpg`.
- For this gold-standard infographic style, preserve these traits: wide landscape dashboard layout; generous white space; calm grid alignment; thin rounded rectangular section borders; controlled pink/magenta accent blocks on white; clean modern sans-serif typography; clear hierarchy with large section numbers and compact text; line-style pictograms; bottom process cards with icon-first reading flow; strong balance between information density and breathing room; minimal decoration; official but accessible tone.
- The gold-standard reference should guide quality, hierarchy, spacing, typography, icon language, color discipline, and overall balance, but it is not a fixed box-by-box template. The layout structure may and should be adapted to the content type, message, audience, and amount of information. Do not force every future infographic into the same framed-cell grid if another composition communicates better while preserving the reference's quality level.
- On 2026-06-15, the first mock individual performance infographic sample was rated by the user as only "พอใช้ได้" (acceptable/passable), not yet the desired standard. Do not treat that sample as a quality benchmark. Future versions must improve visual refinement, spacing discipline, Thai typography, content sharpness, executive synthesis, and resemblance to the gold-standard reference.
- If uncertain about the intended style, ask for or inspect the reference again before finalizing.

## Reinforced Infographic Rules From 2026-06-18

- For performance/evaluation infographics, especially individual staff evaluation and GAA/OIA performance dashboards, the 5-axis spider/radar chart is a core component, not an optional decoration, whenever the data supports evaluation dimensions.
- The five standard radar dimensions are:
  1. Evidence Completeness
  2. Output Clarity
  3. Work Impact
  4. Personal Growth Trend
  5. Ownership / Reliability
- The user explicitly reminded the assistant on 2026-06-18 that the previous omission of the radar chart was a known mistake. Future performance/evaluation infographic drafts should include the radar chart from the first version unless there is a clear reason not to.
- The perfect infographic reference is a quality and design-language standard, not a fixed box-by-box template. Future layouts may adapt to data type, data volume, audience, and key message, but must preserve the reference-level quality in hierarchy, spacing, typography, pictogram style, color discipline, and overall balance.
- The first mock individual performance infographic sample was only "พอใช้ได้" and must not be used as a benchmark. Future work should raise the standard in executive synthesis, dense-but-not-cluttered information structure, Thai typography, spacing, layout balance, and refinement close to the gold-standard reference.
- Additional reinforced reference image from 2026-06-18: `assets/2026-06-18-perfect-infographic-style-reference-reinforced.jpg`.
- For future evaluation presentations, use the assessment-ready spider chart model together with the user's evaluation summary. The model should show Actual/Current, Expected Standard/Target, Previous Round, Evidence Confidence, and a 1-5 behavior-anchored scale so the visual supports coaching and evidence-based interpretation, not ranking. Reference image: `assets/2026-06-18-assessment-spider-chart-model.png`.

## Image Persona

- User requested photorealistic/reality-style images of “รู้ซิ”.
- Rusi avatar should feel elegant, Thai/Asian, intelligent, charming, and professional.
