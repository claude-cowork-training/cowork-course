# Screenshot Shot List — Free Claude Cowork Course

Capture all shots during **one QA run-through** of the course in Claude Desktop / Cowork, using the fictional **Metamorfeus** data in `/scenarios/` (synthetic — safe to publish).

## Capture rules

- **Resolution:** ~1600px wide, PNG. The one GIF (`demo-start-lesson.gif`) should be short (5–10 s), looping.
- **Naming:** `lesson-<n>-<slug>-<shot>.png` exactly as listed below. Save everything into this `assets/` folder.
- **Privacy:** no real account name/email visible in the Claude Desktop chrome — use a demo profile or crop. Nothing else needs redaction; all scenario data is fictional.
- **Where they go:** each image is embedded in (a) the matching GitHub lesson `.md` and (b) the matching WordPress lesson page in `claudecoworktraining-complete-import-july-7-2026.xml`. Alt text suggestions included below.

## Progress tracker

Check off each shot as you capture it.

### Hub page / README

- [ ] `demo-start-lesson.gif` — GIF of typing "start lesson 1.1" and Claude taking over as instructor. *(Replaces README.md placeholder; also the hub-page hero as a still: save the key frame as `hub-start-lesson.png`.)*
  - Alt: "Typing 'start lesson 1.1' in Claude Cowork and Claude beginning to teach the course"
- [ ] `hub-course-folder.png` — the unzipped `cowork-course` folder in File Explorer showing `lessons/`, `scenarios/`, `my-progress.md`.
  - Alt: "The downloaded course folder — everything runs inside it"

### Lesson 1.1 — What Is Claude Cowork

- [ ] `lesson-1-1-chat-vs-agent.png` — Cowork answering a question about `scenarios/messy-folder` (chat) vs. creating `folder-tour.md` (agent steps pane visible).
  - Alt: "Chat answer versus agent action: Cowork creating a real file"
- [ ] `lesson-1-1-new-file-proof.png` — File Explorer showing the freshly created `folder-tour.md`, with its content open.
  - Alt: "The folder-tour.md file Cowork just created, open in an editor"

### Lesson 1.2 — Your First Task

- [ ] `lesson-1-2-brief-vs-vague.png` — side-by-side outputs: lazy one-liner vs. outcome-inputs-format brief on the same task.
  - Alt: "Same task, two briefs: vague instruction output next to proper-brief output"
- [ ] `lesson-1-2-plan-and-redirect.png` — Cowork's plan before executing, with the user's mid-task redirect message beneath it.
  - Alt: "Cowork presents its plan; the user redirects it mid-task"
- [ ] *(optional)* `lesson-1-2-payment-status-table.png` — finished `brightline-payment-status.md` table.

### Lesson 1.3 — Working With Files

- [ ] `lesson-1-3-messy-before.png` — the 16-file `scenarios/messy-folder` mess in File Explorer.
  - Alt: "The messy 16-file scenario folder before organizing"
- [ ] `lesson-1-3-organized-after.png` — the non-destructive `organized/` tree (client subfolders + `internal/`) next to the untouched original.
  - Alt: "The organized copy Cowork built, with the original folder untouched"
- [ ] *(optional)* `lesson-1-3-receivables-citations.png` — `receivables.md` extraction table with source-file citations.

### Lesson 1.4 — Documents and Decks

- [ ] `lesson-1-4-inputs-to-doc.png` — brief referencing the CSV + `notes-from-dana.md` + example report, with generated `may-report.docx` open beside the chat.
  - Alt: "Three inputs — data, context notes, an example — producing a finished Word report"
- [ ] `lesson-1-4-deck-slides.png` — `may-report-deck.pptx` slide-sorter view: headline / numbers / drivers / risks / next.
  - Alt: "The five-slide deck Cowork reshaped from the report"

### Lesson 1.5 — Agents and Parallel Work

- [ ] `lesson-1-5-parallel-tracks.png` — Cowork with the three research tracks (Ferrostar / competitors / market) running simultaneously. **The 'wow' shot — take extra care.**
  - Alt: "Three research agents running in parallel on separate tracks"
- [ ] `lesson-1-5-synthesis-memo.png` — `recommendation-memo.md` open, citations pointing back to the three track files.
  - Alt: "The synthesized recommendation memo citing all three track files"

### Lesson 2.1 — Connectors

- [ ] `lesson-2-1-connector-settings.png` — Claude Desktop connectors panel showing scoped permissions (read vs. write visible).
  - Alt: "Connector settings: scoped, per-tool permissions"
- [ ] `lesson-2-1-meeting-prep.png` — `meeting-prep.md` generated from a connected calendar, calendar source visible in the reasoning. *(Fallback: use the `scenarios/connector-fallback/` simulated path.)*
  - Alt: "A meeting-prep file built from calendar data"

### Lesson 2.2 — Plugins and Skills

- [ ] `lesson-2-2-skill-file.png` — filled-in `skill-template.md` inside the new `skills/` folder.
  - Alt: "A completed skill file in the skills folder"
- [ ] `lesson-2-2-skill-triggered.png` — trigger phrase invoking the skill in chat, plus the v1→v2 changelog line at the bottom of the skill file.
  - Alt: "The skill running from its trigger phrase, with its revision changelog"

### Lesson 2.3 — Team Context Folder

- [ ] `lesson-2-3-cold-vs-context.png` — `digest-cold.md` (generic) next to `digest-with-context.md` (green/yellow/red statuses, team vocabulary).
  - Alt: "The same digest written cold versus with team context"
- [ ] `lesson-2-3-context-folder.png` — `team-sim/` open showing the five context file types: about / style / glossary / playbooks / examples.
  - Alt: "Anatomy of a team context folder: five file types"

### Lesson 2.4 — Shared Workflows

- [ ] `lesson-2-4-library-index.png` — `workflow-library/index.md` table with `area-cadence-name` naming.
  - Alt: "A team workflow library index"
- [ ] `lesson-2-4-workflow-brief.png` — filled `workflow-brief.md` with the four fields: trigger / inputs / output / owner.
  - Alt: "A workflow brief documented to the four-field standard"
- [ ] *(optional)* `lesson-2-4-colleague-test.png` — the colleague-test Q&A exposing a documentation gap.

### Lesson 2.5 — Capstone

- [ ] `lesson-2-5-checklist-done.png` — `capstone-checklist.md` fully checked off.
  - Alt: "The capstone checklist, complete"
- [ ] `lesson-2-5-pressure-test.png` — two runs side by side: clean input vs. degraded input, workflow surviving both.
  - Alt: "Pressure test: the workflow handling a clean and a degraded input"
- [ ] *(optional)* `lesson-2-5-handoff-note.png` — the finished `handoff-note.md`.

## After capture

1. Drop all files into this folder with the exact names above.
2. Embed images in the GitHub lesson `.md` files (relative `assets/...` paths) and swap the README placeholder for the GIF.
3. Add `<figure>` blocks to the lesson pages in `claudecoworktraining-complete-import-july-7-2026.xml` (upload copies to WP Media).
4. Re-zip `cowork-course-complete.zip` so the download matches the repo.
