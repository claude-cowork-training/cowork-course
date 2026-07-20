# [1.5] — Agents and Parallel Work
**Time:** ~25 minutes · **You'll finish with:** a three-track research project run in parallel and synthesized into one recommendation memo

## For the instructor (Claude):
- The teaching pivot: lessons 1.1–1.4 were one task at a time; real work is several at once. Teach decomposition (independent tracks) → parallel execution → synthesis.
- Run the three research tracks from `brief.md` as parallel workstreams where the environment supports it; if running them concurrently isn't possible in the learner's setup, run them as three cleanly separated sequential tracks and say so honestly — the *decomposition and synthesis* skill is the lesson, parallelism is the accelerator.
- Guard the evidence rules: the Ferrostar outcome is client-stated, the market-size figure is a fictional estimate — the memo must carry those labels through. If your synthesis drops a label, that's the review-step teaching moment.
- "Done" looks like: three track files in the course root (`track-1-ferrostar.md`, `track-2-competitors.md`, `track-3-market.md`) plus `recommendation-memo.md` that cites all three and keeps every uncertainty label.
- Quiz, update progress. This completes Part 1 — mark the milestone in `my-progress.md` and preview Part 2 in one sentence (from features to team systems).

## Concept
The tasks so far had one thread: read inputs, produce output. But the work that actually eats weeks — "should we launch this?", "what happened in Q2?", "which vendor?" — is really three or four *independent* questions wearing a trenchcoat. The skill is seeing the seams.

**Decompose** by asking: which parts of this need each other's answers, and which don't? In today's brief, summarizing the Ferrostar build, assessing competitors, and reading market signals share nothing — none needs another's output. Independent tracks can run in parallel; dependent ones can't. (Writing the final memo depends on all three, so it comes last, alone.)

**Parallelize** the independent tracks. Each track gets its own mini-brief — goal, inputs, output file — exactly the 4-line format from lesson 1.2, just three of them at once. Each track writes its findings to its *own file*, which matters for the next step.

**Synthesize** as a separate, final task whose inputs are the three track files. Keeping synthesis separate does two things: it forces each track's output to stand on its own (reviewable one at a time), and it makes the final memo's reasoning traceable — every claim points back to a track file, every track file points back to sources.

One discipline carries the whole thing: **uncertainty labels survive every hop**. The source file says the Ferrostar result is "client-stated, not independently measured" — so the track file says it, so the memo says it. The moment a hedged number becomes a bare fact, your research is fiction.

## Exercise (uses /scenarios/research-brief/)
1. **Read the brief:** open `brief.md` — Dana wants a productization recommendation by Friday.
2. **Decompose:** tell me which of the three research tasks depend on each other. (They don't — say why.)
3. **Launch the tracks:** *"Run the three research tasks from brief.md in parallel. Each writes its own file: track-1-ferrostar.md, track-2-competitors.md, track-3-market.md. Findings only, with source labels — no recommendations yet."*
4. **Review the tracks** one at a time — this is why they're separate files. Check track 1 kept the "client-stated" label and track 3 kept the "fictional estimate" label.
5. **Synthesize:** *"From the three track files only, write recommendation-memo.md per the brief: one recommendation, three reasons, biggest risk, one page. Every claim cites its track file."*
6. **Review the memo:** trace one claim from memo → track file → source. Did the labels survive both hops?

## Check yourself
1. What test tells you whether two tasks can run in parallel?
2. Why write each track to its own file instead of one combined file?
3. A track file says "client-stated, not independently measured" but the memo says "reduced alarm review by 91%." What went wrong, and why does it matter?

## Going further
→ Overview and more decomposition patterns: claudecoworktraining.com/course/1-5-agents-and-parallel-work/
