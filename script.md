# Professional Prompting & Human Communication
## Facilitator Script (90 Minutes)

Audience: founders, students, and operators using AI for real work output.
Framework: C.L.E.A.R.+

- C: Context & Goal
- L: Limits & Negative Constraints
- E: Expected Output
- A: Audience
- R: Role & Process
- +: Iteration & Verification

---

## 00:00-00:10 (10m) | The Cost of Ambiguity
Objective: make communication failure visible and measurable.

Facilitator script:
"Welcome to The Architecture of Intent. This session is not about clever prompts. It is about professional delegation. If the model fails, we inspect instruction quality before blaming capability."

Prompt to room:
- "What did you ask?"
- "What did the model assume?"
- "What was the cost?"

Diagnostic poll options:
- Missing context
- Missing limits
- Missing output specification
- Wrong audience/tone
- Role/process unclear

Pacing counters:
- Minute 03: collect two failure examples.
- Minute 06: poll and classify root causes.
- Minute 09: transition statement.

Transition line:
"Ambiguity is expensive. C.L.E.A.R.+ is the control surface that reduces rework."

---

## 00:10-00:25 (15m) | The Human Delegation Lab
Objective: prove that structure outperforms vague intent.

Exercise setup:
- Pair participants as Architect and Builder.
- Builder can ask exactly one clarifying question.

Round 1 (raw request, 6m):
- Architect gives one-sentence task.
- Builder executes literally.
- Pair records mismatch count.

Round 2 (structured request, 7m):
- Architect rewrites with C.L.E.A.R.+ fields.
- Builder executes again.
- Pair compares output quality + elapsed time.

Debrief prompts (2m):
- "Which field removed most confusion?"
- "Which assumption remained unconstrained?"

Pacing counters:
- Minute 12: call switch to round 2.
- Minute 23: stop and debrief.

Transition line:
"Now we formalize what just improved your result."

---

## 00:25-00:40 (15m) | The C.L.E.A.R.+ Framework
Objective: teach the mental model and shared vocabulary.

Facilitator script:
"Treat C.L.E.A.R.+ as an instruction architecture. Every weak output can be mapped to a weak field."

Field-by-field brief:
- Context & Goal: business scenario + completion definition.
- Limits & Negative Constraints: what must not happen.
- Expected Output: format, sections, and quality bar.
- Audience: who reads and what they understand.
- Role & Process: model persona and working method.
- Iteration & Verification: checks before acceptance.

Live micro-demo:
- Start with weak request.
- Add one field at a time.
- Show quality jump after adding limits + expected output.

Pacing counters:
- Minute 30: complete first three fields.
- Minute 36: complete + verification criteria.

Transition line:
"Now we use the framework on real workplace requests."

---

## 00:40-01:00 (20m) | Prompt Makeover Studio
Objective: refactor weak prompts into execution-grade prompts.

Task:
- Participants submit one weak workplace request.
- They refactor using C.L.E.A.R.+.
- They run before/after outputs and compare.

Facilitator prompts:
- "What is excluded explicitly?"
- "How would you audit success without reading everything?"
- "Which output shape reduces downstream work?"

Makeover checklist:
- Add two negative constraints.
- Add explicit output structure.
- Add verification rubric.

Pacing counters:
- Minute 45: collect raw prompts.
- Minute 52: run first before/after comparison.
- Minute 58: collect one strong rewrite example.

Transition line:
"Great. Now we pressure-test iteration under time constraints."

---

## 01:00-01:20 (20m) | Live Iteration Crucible
Objective: practice multi-turn debugging with discipline.

Mode:
- Solo build (10m) + peer audit (8m) + rapid fix (2m).

Iteration protocol (must follow in order):
1. Diagnose: identify failing C.L.E.A.R.+ field.
2. Isolate: change one variable only.
3. Constrain: add exclusions and verification gate.

Peer audit questions:
- "What assumption still leaks?"
- "What check would reject this output?"
- "What changed from prior iteration?"

Pacing counters:
- Minute 66: solo build checkpoint.
- Minute 72: start peer audits.
- Minute 78: finalize one improved prompt.

Transition line:
"Last block: we convert this into repeatable behavior for next week."

---

## 01:20-01:30 (10m) | Synthesis, Action Plan & Post-Test
Objective: commit transfer to real work.

Post-test (4m):
- Rewrite one flawed prompt from segment 1 using C.L.E.A.R.+.
- Include two negative constraints.
- Include pass/fail criteria.

Action plan (4m):
- One real use-case this week.
- One verification rule to enforce.
- One stakeholder to share workflow with.

Close (2m):
"You now have a repeatable delegation architecture. Use C.L.E.A.R.+ first, then iterate with Diagnose-Isolate-Constrain."

---

## Participant FAQs (Use During Any Segment)
- "What if I do not know the right constraints yet?"
  - Start with risk boundaries: no fabrication, no legal claims, no hidden assumptions.
- "How long should prompts be?"
  - As long as needed for unambiguous delegation; optimize for clarity, not brevity.
- "Can I skip role/audience?"
  - Only if output is purely internal and structure already constrains behavior.
- "How many iterations before stopping?"
  - Stop when pass/fail rubric is consistently met across two runs.

## Facilitation Controls
- Hard stop rule: if discussion exceeds 90 seconds, park and continue.
- Energy reset: ask participants to stand for 20 seconds before segment 5.
- Inclusion rule: every pair shares one failure and one fix.

## Asset Map
- Slides: index.html
- Desk card: cheatsheet.html
- LLM context docs: llms.txt and docs/
