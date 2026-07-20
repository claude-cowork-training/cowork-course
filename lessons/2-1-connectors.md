# [2.1] — Connectors
**Time:** ~20 minutes · **You'll finish with:** one connected tool (or the fallback drill), a cross-boundary task completed, and a written connection policy for yourself

## For the instructor (Claude):
- Teach the permission model FIRST, before anything gets connected — deliberate beats maximal.
- Then guide connecting one real tool (calendar or file storage is the easiest win). You cannot connect it for them; walk them through their client's connector settings and verify by reading something trivial from the connected tool.
- If the learner can't or won't connect a real tool, run the full exercise on /scenarios/connector-fallback/ instead and say plainly that it's simulated — the decision skills transfer, the setup steps they'll do later.
- Cross-boundary rule for this course: connected data may come IN, but every output still lands in this course folder. Never write into their connected tools during the course.
- "Done" looks like: `meeting-prep.md` exists (from real or fallback calendar) and `my-connection-policy.md` exists with their three answers.
- Quiz, update progress, offer 2.2.

## Concept
Everything so far ran on files you handed over. Connectors remove the handing-over: Cowork can read your calendar, search your messages, pull documents from cloud storage — the systems your job actually runs on.

The skill of this lesson isn't clicking "connect." It's the **permission model**, three facts that should shape every connection decision. First, *connectors are scoped*: connecting your calendar grants calendar access, nothing else — each tool is its own decision, like the folder-scoping rule from 1.1 extended outward. Second, *access is not authorship*: reading your inbox and sending mail as you are wildly different grants; know which one you're giving. Third, *connected doesn't mean consulted*: Claude uses connected tools when a task calls for them, but your brief still controls what's in scope — which is why briefs now need a line they never needed before: *which sources to use*.

The selection rule: connect the one tool that would save you the most time **this week**, and add others only when a real task demands them. People who connect everything on day one create a review surface they can't manage; people who connect one tool per real need always know what Claude can see and why.

And a course rule that's also a good starter policy: data flows in, outputs land locally. Writing back into live systems — sending the email, updating the CRM — is a bigger grant with a bigger review burden. Earn it one direction at a time.

## Exercise
1. **Pick one:** which single tool would save you the most time this week? Say it and why.
2. **Connect it** (I'll walk you through your client's connector settings), then verify: ask me to read one trivial thing from it. *No connection today? Say "use the fallback" and we run steps 3–4 on /scenarios/connector-fallback/.*
3. **Cross the boundary:** *"Read tomorrow's calendar and write meeting-prep.md in the course root: for each meeting, what it's about, what I should have ready, and one question I should ask."* (Fallback: same brief against tomorrows-calendar.md — note how the Cascadia check-in prep should pull in what you learned about extracts in earlier lessons.)
4. **Review** the prep doc against the actual calendar. Did anything get misread?
5. **Write your policy:** create `my-connection-policy.md` answering: which tools will I connect and in what order? what will I never connect? what outputs am I comfortable having written back, eventually?

## Check yourself
1. What's the difference between read access and write access to a connected tool, and why does it change your review burden?
2. Why "one tool per real need" instead of connecting everything up front?
3. Why does the course keep all outputs local even once real tools are connected?

## Going further
→ Overview, supported connectors, and security considerations: claudecoworktraining.com/course/2-1-connectors/
