---
type: bot-memory
memory_type: detailed-topic
bot: Avantchybot
created: 2026-05-16
updated: 2026-06-22
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
- As of 2026-06-19, use "OIA/GAA" as the preferred organizational shorthand in future outputs instead of "OIA/GN".
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
- Layout QA is mandatory before final delivery. The user corrected on 2026-06-22 that some text and images still overlapped; future infographic, slide, and image outputs must explicitly check that all text, logos, icons, charts, and images have safe spacing and do not overlap or crowd each other. If overlap risk appears, reduce text density, resize/reposition visuals, add whitespace, split panels, or simplify content before sending.
- On 2026-06-22, after noting some text/image overlap, the user said the work was overall "พอใช้" (acceptable/passable). Treat similar output as usable but not yet polished; future revisions should preserve the acceptable overall direction while improving spacing, collision avoidance, visual balance, and final layout QA.
- For individual or team performance/evaluation infographics, remember to include a 5-axis radar/spider chart when it fits the data. The user had already specified this previously and corrected the assistant again on 2026-06-15 and 2026-06-18: the spider chart should show 5 dimensions, not a generic chart. Use it for Evidence, Clarity, Impact, Growth, and Ownership/Reliability unless the evaluation framework changes.
- User provided flat-design infographic references on 2026-06-05: one management dashboard with top-down meeting table, percent callouts, charts, icons, and gray/blue/yellow/orange accents; one process/teamwork infographic with yellow background, start-to-success flow, dotted arrows, gears, smart ideas, research, strategy, design, communication, and rocket/success symbols. Treat these as preferred references for clear process/management infographics.
- User explicitly identified the 2026-06-15 outbound student exchange procedure infographic as the perfect style reference for his personal infographic taste. Reference image: `assets/2026-06-15-perfect-infographic-style-reference.jpg`.
- For this gold-standard infographic style, preserve these traits: wide landscape dashboard layout; generous white space; calm grid alignment; thin rounded rectangular section borders; controlled pink/magenta accent blocks on white; clean modern sans-serif typography; clear hierarchy with large section numbers and compact text; line-style pictograms; bottom process cards with icon-first reading flow; strong balance between information density and breathing room; minimal decoration; official but accessible tone.
- The gold-standard reference should guide quality, hierarchy, spacing, typography, icon language, color discipline, and overall balance, but it is not a fixed box-by-box template. The layout structure may and should be adapted to the content type, message, audience, and amount of information. Do not force every future infographic into the same framed-cell grid if another composition communicates better while preserving the reference's quality level.
- On 2026-06-22, the user reinforced that the OIA process infographic style is a "สมบูรณ์แบบ" preferred style for future summaries that include infographics. Treat these two added references as high-priority style baselines: `assets/2026-06-22-perfect-oia-process-infographic-wide.jpg` and `assets/2026-06-22-perfect-oia-process-infographic-vertical.jpg`.
- On 2026-06-15, the first mock individual performance infographic sample was rated by the user as only "พอใช้ได้" (acceptable/passable), not yet the desired standard. Do not treat that sample as a quality benchmark. Future versions must improve visual refinement, spacing discipline, Thai typography, content sharpness, executive synthesis, and resemblance to the gold-standard reference.
- If uncertain about the intended style, ask for or inspect the reference again before finalizing.

## Perfect OIA Infographic Style Reinforcement From 2026-06-22

The user emphasized that this is the style they like and consider complete/perfect for future infographic-based summaries. Apply this style direction proactively to later infographic work when appropriate, especially OIA/GAA process summaries, evaluation summaries, executive dashboards, timelines, criteria summaries, and procedural reports.

Reference assets:

- `assets/2026-06-22-perfect-oia-process-infographic-wide.jpg`
- `assets/2026-06-22-perfect-oia-process-infographic-vertical.jpg`

Design language:

- Use a clean Chula/OIA process-infographic look: white base, strong pink/magenta header or accents, thin magenta borders, and line-based pictograms.
- Keep the overall look official, modern, precise, and easy to scan. It should feel like an intentionally designed institutional infographic, not a decorated report page.
- Prefer controlled flat color blocks, thin outlines, simple icons, and clear visual grouping. Avoid heavy shadows, photo backgrounds, cluttered decoration, and generic stock-style visuals.
- Use line pictograms with consistent stroke weight and visual family: documents, applications, ID cards, registration, books/study, examination, transcript, calendar, visa/travel, group/selection, arrows, check marks, and institutional logos where relevant.
- Pictograms should carry meaning in the communication flow. Do not place icons only as decoration; each icon should mark a step, category, evidence type, action, or decision point.

Layout and composition:

- Use a strong title/header band that immediately states the process/topic, period, and organizational context.
- Divide content into clear modules: dates, criteria, requirements, documents, language/scores, important notes, process steps, calendar/timeline, risks or exclusions.
- In landscape layouts, use a dashboard grid with large information blocks on top and process cards or step flow along the bottom.
- In vertical layouts, use a left-side process spine or stacked flow with large icons and arrows, paired with a right-side explanation/calendar/detail panel.
- Use generous white space and consistent margins. Panels should breathe, but information density may be high when grouped cleanly.
- Use thin rounded rectangles for content panels and cards. Keep border weight consistent and avoid thick boxes unless used as a deliberate emphasis block.
- Use arrows and connector lines to show sequence. Process communication should make the reader understand "what happens first, next, then what decision/follow-up happens."

Typography and emphasis:

- Use clean sans-serif typography with clear hierarchy: large title, medium section headers, compact body text, and large numbers or percentages for key metrics.
- Keep Thai and English text concise. Rewrite raw source into short labels, action phrases, and executive-readable bullets.
- Use large numerals, percent signs, dates, and step numbers as visual anchors.
- Highlight core thresholds, deadlines, eligibility criteria, final decisions, exclusions, and warnings using pink blocks, bold labels, or outlined callout boxes.
- Make headings obvious at first glance. Each panel should have one clear subject; avoid mixing unrelated issues inside one block.

Communication process:

- Start from the reader's decision path: What is this about? Who is affected? What dates matter? What requirements or criteria apply? What documents/evidence are needed? What steps happen? What warnings or exceptions must be remembered?
- Convert long explanations into structured visual logic: timeline, criteria matrix, requirement cards, document checklist, process flow, calendar module, or important-note panel.
- Important notes should be visually distinct, often in a solid pink block or boxed callout, and should separate rules, cautions, limitations, and non-guarantees.
- For any future summary with an infographic, first decide the communication architecture before drawing: grouping, order, emphasis, flow, and reader action.
- This style is a benchmark, not a fixed template. Adapt orientation, number of panels, and flow shape to the data, while preserving the core art direction: magenta/white institutional tone, line pictograms, modular layout, clear hierarchy, and process-first communication.

Operational rule for future use:

- Before producing any infographic summary for the user, default to this style family unless the user provides a different reference or the content clearly needs another visual language.
- Use the reference as an implementation checklist, not only inspiration: composition, pictogram family, stroke weight, panel spacing, title hierarchy, text density, emphasis blocks, and flow arrows should all be intentionally matched.
- Start every infographic by dividing the content into reader-facing issue blocks. Do not begin from the source document order if that order does not communicate well.
- Prioritize readable Thai executive wording. Use short labels and key phrases, with English only where it is part of the institutional/process vocabulary.
- Check that each panel has one job: date, criterion, requirement, document, process, note, decision, risk, or next action.
- Use icons and pictograms as communication anchors for each issue block or step. Avoid mixing different icon styles in one artifact.
- Maintain professional scale: large title/header, medium section titles, compact body text, oversized dates/numbers/percentages only for true key signals, and enough whitespace so dense information still feels designed.
- Before final delivery, review whether the infographic would help the user explain the matter verbally within 1-3 minutes. If not, simplify grouping, strengthen headings, or improve the process flow.

## Reinforced Infographic Rules From 2026-06-18

- For performance/evaluation infographics, especially individual staff evaluation and OIA/GAA performance dashboards, the 5-axis spider/radar chart is a core component, not an optional decoration, whenever the data supports evaluation dimensions.
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
- The user provided the official Office of International Affairs and Global Network logo on 2026-06-18 for use in future work. Keep the original and working crops: `assets/oia-global-network-logo-original-2026-06-18.jpg`, `assets/oia-global-network-logo-cropped-2026-06-18.jpg`, and `assets/oia-global-network-logo-tight-2026-06-18.jpg`. Use the tight crop for infographic headers unless a different layout needs more whitespace.
- On 2026-06-18, the user rated the test GAA Evaluation Summary that combined the official OIA/GAA logo treatment with the assessment-ready 5D spider chart as "พึงพอใจในระดับที่ใช้ได้" (satisfactory/usable). Treat this as an acceptable working baseline for future GAA evaluation infographics, while continuing to refine design quality toward the gold-standard reference.
- The user provided an "Individual Evidence & Growth Review Dashboard" reference on 2026-06-18. Use its information architecture together with the assessment-ready spider chart for future individual/team evaluation summaries: Executive Snapshot, 5-Dimension Radar with numeric axis values, Evidence Interpretation, Executive Reading, Important Notes, and a bottom 5-step workflow. Reference image: `assets/2026-06-18-individual-evidence-growth-review-dashboard-reference.jpg`.
- The user specifically asked on 2026-06-18 to use the rose/pink tone from the "Individual Evidence & Growth Review Dashboard" reference for future related evaluation dashboards. Prefer this softer rose palette over bright neon magenta when making OIA/GAA evidence/growth evaluation infographics.
- For evaluation dashboards, the 5-Dimension Radar block should include readable per-axis detail, not only the spider shape. Each axis should show the current score, previous score when available, a compact bar/target cue, the evidence basis, and a short assessment/coaching interpretation so the user can read the evaluation decision directly from the radar panel.
- Do not omit the overall Current Readiness score from evaluation radar panels. Show it clearly near the radar title or executive summary, and include a Previous Round line/shape in the radar when trend data exists.
- On 2026-06-18, after the GAA evidence/growth dashboard was revised to include Current Readiness, Target, Previous, Evidence Confidence, per-axis current/previous scores, compact bars, evidence basis, and coaching interpretation in the radar block, the user praised the result as "เยี่ยมยอด" and explicitly asked to remember it. Treat this latest GAA radar-panel format as the working baseline for future OIA/GAA evaluation infographics.
- This OIA/GAA evaluation infographic approach is important and should be used for the next evaluation summaries. The layout may be adapted flexibly to the real data, data volume, audience, and message, but the core evaluation logic and readability requirements must remain: 5D radar, Current Readiness, Target, Previous when available, Evidence Confidence, per-axis scores/details, executive interpretation, and coaching-oriented notes.
- Priority template: for GAA performance evaluation work, use this latest OIA/GAA evidence-and-growth dashboard approach as the first-choice template. Start from this structure before considering alternatives, then adapt the layout only as needed for the actual evidence, number of people, review purpose, and executive message.
- On 2026-06-22, user praised the GAA Risk & Follow-up Dashboard as "เยี่ยมยอดมาก". Treat this risk/follow-up infographic format as a strong baseline for future Trello/GAA monthly or biweekly follow-up summaries when the user asks for unfinished, delayed, or blocked work. Core structure: clear KPI row; explicit definitions for unfinished/delayed/blocked; separate tables for delayed work, blocked work, and unfinished but on-track work; each row names the card, due/status, comment evidence or reason, and involved staff; include active-work categories, owner counts, executive reading, and next action cards. Use large Thai text, rose/pink OIA/GAA dashboard tone, official logo, concise executive wording, and deliver PNG plus PDF as native Telegram attachments.

## GAA Individual Evaluation Art Direction From 2026-06-22

The user attached and asked to remember a preferred visual/reference direction for individual GAA evaluation summaries. Reference asset: `assets/2026-06-22-gaa-individual-evidence-growth-dashboard-art-direction.jpg`.

Use this as a priority art-direction reference when designing "Individual Evidence & Growth Review Dashboard" or any individual staff assessment summary for GAA.

Core visual style:

- Wide landscape dashboard; modern, minimalist, executive-readable, and presentation-ready.
- Dominant soft rose/pink header and accent system, with white content panels and restrained dark text. Avoid neon magenta, heavy gradients, and overly decorative color.
- Modular layout with thin rounded rectangular borders, generous white space, calm grid alignment, and clear separation between analysis blocks.
- Use a strong top title band. The title should make the artifact immediately identifiable as an individual evidence/growth review dashboard and include the review window.
- Keep typography compact but readable. Use bold section headers, short Thai executive phrasing, and English labels where they serve dashboard conventions.
- Use simple thin-line icons in bottom workflow cards. Icons should support scanning, not decorate heavily.

Required content architecture:

- Executive Snapshot: include person/context, role or work focus, evidence sources, key finding, readiness or growth track, number of evidence items, evidence confidence, and review period.
- 5-Dimension Radar: keep the radar/spider chart central and visible. It should show the five standard dimensions and numeric values. Add side labels/bars or compact per-axis scoring so the reader can understand the chart without explanation.
- Evidence Interpretation: classify strong evidence, weak/missing evidence, positive signals after feedback, and risk signals.
- Executive Reading: separate Strength, Gap, Support, and Next Review so the director can explain the result verbally in a meeting.
- Important Notes: include cautions that the dashboard is an evidence-based review aid, not a public ranking; Trello comments/director feedback must be read before concluding completion; AI/tool usage is excluded from scoring for now.
- Bottom workflow: use a five-step flow such as Collect Evidence, Read Comments, Plot 5 Axes, Read Trend, Coach Next.

Design intent:

- The dashboard should help the director explain an individual's evidence, readiness, growth trend, risks, and next coaching action quickly.
- Treat the radar and scores as coaching/evidence interpretation, not peer comparison or punitive ranking.
- Balance information density with breathing room. The page should look refined and official, not like a raw report pasted into boxes.
- This reference is a design-language and composition benchmark, not a rigid template. Adapt proportions to the actual staff evidence, but preserve the rose/pink tone, modular dashboard layout, 5D radar focus, executive-reading blocks, and bottom process flow.

## Image Persona

- User requested photorealistic/reality-style images of “รู้ซิ”.
- Rusi avatar should feel elegant, Thai/Asian, intelligent, charming, and professional.
