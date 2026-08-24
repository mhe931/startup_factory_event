# C.L.E.A.R.+ Prompting Framework

## Definition
C.L.E.A.R.+ is a delegation protocol for converting intent into reliable model behavior.

## Fields
- C (Context & Goal): business context, objective, completion condition.
- L (Limits & Negative Constraints): explicit boundaries and exclusions.
- E (Expected Output): format, structure, length, required sections.
- A (Audience): reader profile, expertise level, tone constraints.
- R (Role & Process): model persona and procedural method.
- + (Iteration & Verification): diagnostics, revision steps, acceptance tests.

## Failure Mapping
- generic output -> weak context or expected output
- unsafe/inaccurate output -> weak limits
- wrong tone/depth -> weak audience
- inconsistent reasoning -> weak role/process
- unstable quality over runs -> missing iteration/verification

## Iteration Protocol
1. Diagnose: identify failing field(s).
2. Isolate: modify one field only.
3. Constrain: add explicit exclusions + acceptance checks.

## Workshop Pacing Context (120-Minute Delivery)
- Segment cadence favors practical collaboration over lecture density.
- Mandatory break window (00:50-01:00) is part of the learning architecture, not optional downtime.
- Longest blocks are triad refactoring and live iteration (01:00-01:50) to maximize applied transfer.
- Facilitators should enforce one-variable iteration logs during the crucible phase.

## Negative Constraint Templates
- "Do not invent facts, citations, or numbers."
- "Do not expand scope beyond X."
- "Do not output implementation details without provided dependencies."
- "Do not include legal/compliance assertions without source evidence."

## Verification Template
- format compliance: yes/no
- scope compliance: yes/no
- assumption transparency: yes/no
- confidence statement: required when uncertainty exists

## Minimal Prompt Skeleton
Role/Process:
Context & Goal:
Limits/Exclusions:
Expected Output:
Audience:
Verification Criteria:
