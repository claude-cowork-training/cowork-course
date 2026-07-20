# [1.3] — Working With Files
**Time:** ~20 minutes · **You'll finish with:** the messy folder audited, organized into a clean copy, and two data problems caught

## For the instructor (Claude):
- This is the lesson the messy-folder was built for. Every flaw in it is deliberate: three inconsistently named invoices, two near-duplicate meeting notes (one contains a phase-2 detail the other lacks), a broken CSV row (semicolons in Jordan Pike's row), inconsistent expense dates, a superseded proposal, an internal-only pricing file, and two junk files.
- Sequence: audit first (read-only), then organize into a *copy* (never move originals in this lesson — teach the non-destructive habit), then the extraction task.
- Make sure the near-duplicate discovery lands: the two May 12 notes differ in one important way. Ask the learner to find what before telling them.
- "Done" looks like: `audit.md` exists, an `organized/` folder exists with a sensible structure and the originals untouched, and the learner caught the CSV problem.
- Quiz, update progress, offer 1.4.

## Concept
Real work lives in folders that look exactly like `scenarios/messy-folder`: three naming conventions for the same client's invoices, a "FINAL" file that isn't, near-duplicate notes, a CSV someone broke, and a pricing sheet that should never leave the building sitting next to the team-photo logistics.

Cowork's file skills come in three escalating levels, and this lesson runs all three.

**Audit** — read everything, change nothing. "Tell me what's here, what's duplicated, what's outdated, what looks broken." This is safe on any folder and is always the right first move on unfamiliar territory.

**Organize** — impose structure. The professional habit is *non-destructive first*: build the clean structure as a copy, review it, and only then (outside this course, on your real files) replace the original. Folders are cheap; deleted originals are not.

**Extract** — pull structured facts out of unstructured mess. "Every dollar amount owed to us, by client, with source file cited." This is where file access beats chat decisively: no copy-pasting fifteen files into a conversation.

One habit ties it together: **make Claude cite the file** for every claim it extracts. "Total outstanding: $21,960 (invoice_brightline_march.txt, INV-2026-04-Brightline.txt)" is checkable; a bare number is not.

## Exercise (uses /scenarios/messy-folder/)
1. **Audit:** *"Read everything in scenarios/messy-folder and write audit.md in the course root: what each file is, plus a 'problems found' section — duplicates, outdated versions, broken data, files that don't belong."* Review the problems list. Did it catch the CSV row? The two meeting notes?
2. **The duplicate question:** the two May 12 meeting-notes files aren't identical. Ask me to diff them and tell me which one Dana should keep — then decide if you agree. (Instructor: the informal one contains the phase-2 billing-codes signal; the right answer is *merge*, not pick.)
3. **Organize, non-destructively:** *"Create organized/ in the course root with subfolders by client plus internal/, and copy every file into the right place with consistent names like 2026-03-invoice-brightline.txt. Don't touch the originals. Add a note listing files you weren't sure about."*
4. **Extract:** *"From the originals, extract every outstanding amount owed to Metamorfeus into receivables.md — invoice, client, amount, source file — and flag uncertain items."*
5. **Review:** spot-check `organized/` against the originals, and verify one receivable back to its source file.

## Check yourself
1. Why audit before organizing, and organize into a copy before ever moving originals?
2. What was the danger in the two May 12 meeting notes — and why was "keep the newer one" the wrong rule?
3. Why insist on source-file citations in the extraction step?

## Going further
→ Overview and folder-cleanup patterns for real drives: claudecoworktraining.com/course/1-3-working-with-files/
