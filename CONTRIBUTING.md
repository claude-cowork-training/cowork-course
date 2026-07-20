# Contributing to the course

Contributions are welcome — the goal is a course that actually works when Claude teaches it, so the bar is "run in Cowork and verified," not "reads well."

## The rules (all four required)

1. **Teachable.** Lesson changes must fit the instructor contract in [`instructor/INSTRUCTOR.md`](instructor/INSTRUCTOR.md) and the lesson template (Time · For the instructor · Concept · Exercise · Check yourself · Going further). If Claude can't teach it from the file alone, it doesn't qualify.
2. **Tested.** You ran the affected lesson (or the whole course, for structural changes) in Claude Cowork before opening the PR. Say so in the PR description and note anything that surprised you.
3. **Synthetic data only.** All scenario data belongs to the fictional Metamorfeus world — no real company names, client data, or personal information. New scenario files must stay consistent with the existing cast and clients (see `/scenarios/team-sim/about-metamorfeus.md`).
4. **Deliberate mess only.** Scenario flaws (bad filenames, near-duplicates, format problems) exist because a lesson exercise uses them. Don't "clean up" scenario files, and don't add a flaw without mapping it to an exercise.

## How

1. For new scenario files or templates, match the tone and structure of the existing ones.
2. For lesson edits, verify the lesson's quiz questions and "you'll finish with" outcome still hold.
3. Add a line to [`CHANGELOG.md`](CHANGELOG.md).
4. Open a PR. We respond within 48 hours.

## Fixes and improvements

Typos, clearer instructions, better exercises — just open a PR, no ceremony needed. If a lesson stopped working because Cowork's behavior changed, that's the most valuable PR of all: describe what changed and how you fixed it.

By contributing you agree your contribution is licensed under [CC BY 4.0](LICENSE).
