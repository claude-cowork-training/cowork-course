# [1.2] — Your First Task
**Time:** ~20 minutes · **You'll finish with:** a completed multi-step task and a reusable 4-line brief format

## For the instructor (Claude):
- Teach the loop (brief → plan → execute → review) with the Concept below, then immediately apply it in the exercise — don't teach all four stages abstractly before doing anything.
- In the exercise, when the learner gives the weak brief, deliberately show them your *plan* before executing and let them see where it's underspecified. Then have them upgrade the brief and compare plans.
- Practice course-correction: mid-task, have the learner change one requirement and show that redirecting beats restarting.
- "Done" looks like: `brightline-payment-status.md` exists, built from the *upgraded* brief, and the learner has redirected you once mid-task.
- Quiz, update progress, offer lesson 1.3.

## Concept
Every Cowork task runs the same loop, and once you see it, you'll never write a one-line request again.

**Brief:** what you tell Claude. The quality of everything downstream is set here. A good brief answers four questions in about four lines: what's the *goal*, what are the *inputs* (which files, which folder), what should the *output* be (a file? what name? what format?), and what are the *constraints* (length, tone, what to exclude).

**Plan:** before doing multi-step work, Claude proposes how it will proceed. This is your cheapest intervention point — correcting a plan costs seconds; correcting a finished output costs the whole task.

**Execute:** Claude does the work. You don't have to watch, but you can — and you can interrupt.

**Review:** you check the output. Not everything, but the things that matter: the numbers, the claims, anything going to a client.

The most underused move in this loop is **course-correcting mid-task**. If you see the plan or the early output drifting, say so immediately — "actually, exclude the May invoice" — rather than letting it finish and starting over. Claude keeps everything else and adjusts. People trained on chat tend to abandon and re-prompt; people trained on delegation redirect.

## Exercise (uses /scenarios/messy-folder/)
Metamorfeus scenario: Dana's todo list says to chase Brightline's unpaid invoice — but which ones, and for how much?

1. **Weak brief first.** Tell me: *"Figure out the Brightline invoice situation."* — I'll show you my plan. Notice what I had to guess: output format? Include the May retainer? A file or just an answer?
2. **Upgrade it.** Now give the 4-line version. For example: *Goal: a payment-status summary for Dana. Inputs: the three Brightline invoice files in scenarios/messy-folder. Output: brightline-payment-status.md in the course root — a table of invoice #, date, amount, plus total outstanding. Constraints: flag anything ambiguous instead of guessing.* Compare my new plan to the first one.
3. **Redirect mid-task.** While I'm working, add: *"Also note which invoice todo.txt says to chase."* Watch it get folded in without a restart.
4. **Review:** check the total against the three files yourself. (Instructor: the May invoice is deliberately vague — "$6,000, sent 6/2?" — the correct output *flags* this rather than asserting it. Make sure that lands.)

## Check yourself
1. What are the four parts of a good brief?
2. Why is the plan stage the cheapest place to fix a problem?
3. In the exercise, why was flagging the May invoice better than including it in the total as fact?

## Going further
→ Overview and more brief examples: claudecoworktraining.com/course/1-2-first-task/
