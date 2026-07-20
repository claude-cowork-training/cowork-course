# [1.4] — Documents and Decks
**Time:** ~20 minutes · **You'll finish with:** a leadership-ready May report built from a CSV, context notes, and an example — then a deck version of it

## For the instructor (Claude):
- The core teaching: an example file is worth more than a page of format instructions. The exercise proves it by generating the report *without* the example first, then *with* it.
- Enforce Dana's notes: the pipeline dip must be explained (cleanup, not demand), Tomás's 91% must appear as a risk, the Cascadia milestone payment must be called out. If your own draft misses one, let the learner catch it in review — that's the lesson working.
- Produce the report as a Word document (.docx) and the deck as a real .pptx so the learner sees actual output files, not markdown pretending.
- "Done" looks like: `may-report.docx` and `may-report-deck.pptx` in the course root, matching the April example's structure, with all three of Dana's notes reflected.
- Quiz, update progress, offer 1.5.

## Concept
The gap between "AI-generated draft" and "document you'd actually send" is almost never writing quality. It's three inputs most people don't provide.

**The data** — obviously. Here, `monthly-metrics.csv`.

**The context that isn't in the data** — the human knowledge that turns numbers into a story. May's pipeline number *fell*, and the data can't tell you that's because two stale leads were cleaned out, not because demand dropped. Without `notes-from-dana.md`, any honest draft would report the dip as bad news. Feeding Claude the "here's what the numbers don't say" file is the single highest-leverage habit in document work.

**An example of done** — `last-month-report-example.md` shows April's report: its structure, its length discipline, its table format, its voice. One good example replaces paragraphs of format instructions and outperforms them, because it encodes decisions nobody thinks to spell out (like leading with a one-line headline).

Same inputs, different container: once the report exists, "turn this into a five-slide deck for the same audience" is a *reshaping* task, not a rewriting one. The thinking is done; only the packaging changes. That's why document-then-deck beats deck-from-scratch.

## Exercise (uses /scenarios/report-inputs/)
1. **Without the example:** *"Write Metamorfeus's May 2026 report from monthly-metrics.csv and notes-from-dana.md."* Skim my draft. It's probably fine — and probably shaped nothing like what leadership expects.
2. **With the example:** *"Redo it matching the structure, length, and voice of last-month-report-example.md exactly. Save as may-report.docx in the course root."* Compare. Name two decisions the example made for you.
3. **Review against Dana's notes:** check all three landed — milestone payment called out, pipeline dip explained correctly, Tomás's utilization framed as risk. If one is missing, don't fix it yourself: tell me what's wrong and have me revise. (Redirect, don't redo — lesson 1.2's habit.)
4. **Reshape:** *"Turn may-report.docx into a 5-slide leadership deck, may-report-deck.pptx: headline, numbers, drivers, risks, next month."* Open it. Review the risk slide especially.

## Check yourself
1. What information did notes-from-dana.md contain that no amount of staring at the CSV could produce?
2. Why does one example file usually beat detailed formatting instructions?
3. Why build the deck from the finished report instead of from the raw inputs?

## Going further
→ Overview plus document-type patterns (proposals, memos, one-pagers): claudecoworktraining.com/course/1-4-documents-and-decks/
