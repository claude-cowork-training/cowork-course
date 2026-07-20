# [2.4] — Shared Workflows
**Time:** ~25 minutes · **You'll finish with:** your 2.2 skill documented to the four-field standard, a workflow library started, and the colleague test passed

## For the instructor (Claude):
- Core mechanic: the colleague test. You role-play a teammate who has never seen the workflow, following ONLY the learner's documentation — no charitable inference. When the doc says "the usual folder," you ask "which folder?" Every question you're forced to ask is a documentation gap; keep a list.
- The learner documents their 2.2 skill first (they know it best), fixes gaps, re-tests. Then the harder rep: they document a workflow they DON'T own — the Metamorfeus monthly report, from the playbook and lesson 1.4 experience — and discover which steps lived in Dana's head.
- Enforce naming: entries follow area-cadence-name (e.g., reporting-monthly-business-report). Reject "my workflow v2 final" style names on sight, kindly.
- "Done" looks like: `workflow-library/` exists in the course root with an index.md and two entries, and the learner's own entry survived the colleague test with zero forced questions on the second pass.
- Quiz, update progress, offer 2.5.

## Concept
Your 2.2 skill has a flaw you can't see: it works because *you* run it. You know which folder "the inputs" means, what to do when the CSV is late, and why the risks section can't be skipped. None of that is written down, so the workflow's real documentation is your memory — which takes vacations, changes jobs, and forgets.

A **shared workflow** is a skill plus the four fields that let someone else run it: **trigger** (what phrase or event starts it), **inputs** (exactly what it needs and exactly where that lives), **output** (name, format, destination), **owner** (who fixes it when it breaks — every workflow breaks eventually, and "everyone's" workflows are no one's). The `templates/workflow-brief.md` file is this standard as a form.

The quality bar is the **colleague test**: could a teammate who's never seen this workflow run it from the documentation alone, asking you nothing? Not "could they figure it out" — *asking you nothing*. Every question they'd need to ask is a step still living in your head. The test is brutal and cheap, and this lesson runs it with Claude playing the colleague, which means you can fail privately and fix everything before a human ever depends on the doc.

Libraries scale on **naming**. `reporting-monthly-business-report` sorts, searches, and self-describes; `dana's thing (new)` does none of that. The convention barely matters; *having* one before entry five matters enormously.

## Exercise (uses your skills/ folder from 2.2 and /scenarios/team-sim/playbooks/)
1. **Set up the library:** create `workflow-library/` in the course root with an `index.md` table: name, trigger, owner, last-verified date.
2. **Document your own:** write your 2.2 skill's library entry using `templates/workflow-brief.md`. All four fields, no "the usual folder" hand-waving.
3. **The colleague test, round one:** say *"run the colleague test on my entry"* — I become a teammate seeing it cold and follow it literally, asking every question the doc forces. Expect three to five. Nobody passes round one.
4. **Fix and re-test:** patch every gap in the doc (not by explaining to me — by editing the entry), then round two. Target: zero forced questions.
5. **The harder rep:** document the Metamorfeus monthly report — a workflow you *don't* own — from `playbooks/monthly-report-playbook.md` and your 1.4 experience. List the questions you couldn't answer. That list is exactly what makes shared documentation valuable: you've just found the knowledge that would leave with Dana.

## Check yourself
1. What are the four fields, and which one prevents the "everyone's workflow is no one's workflow" failure?
2. What's the pass condition of the colleague test — and why is "they could figure it out" a fail?
3. In step 5, what did the unanswerable questions represent?

## Going further
→ Overview and naming conventions that scale: claudecoworktraining.com/course/2-4-shared-workflows/
