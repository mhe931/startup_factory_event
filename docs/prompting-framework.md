# C.L.E.A.R.+ Prompting Framework

C.L.E.A.R.+ is a shared-meaning protocol for delegation across people and AI systems. It turns implicit intent into a complete operating contract.

## 120-Minute Workshop Map

| Segment | Time | Duration | Focus |
| --- | --- | ---: | --- |
| 1 | 00:00-00:15 | 15 min | The Intent & Meaning Bottleneck |
| 2 | 00:15-00:35 | 20 min | The Human Delegation Lab |
| 3 | 00:35-00:43 | 8 min | The Multi-Lens Experiment |
| 4 | 00:43-00:50 | 7 min | The C.L.E.A.R.+ Universal Protocol |
| 5 | 00:50-01:00 | 10 min | Reset, Bio-Break & Purposeful Table Alignment |
| 6 | 01:00-01:25 | 25 min | The Executive Makeover Studio |
| 7 | 01:25-01:50 | 25 min | The Live Iteration Crucible & Steering Protocol |
| 8 | 01:50-02:00 | 10 min | Synthesis, Leadership Commitments & The Peak-End Close |

Total: 120 minutes.

## Fields

| Field | Meaning | Required Checks |
| --- | --- | --- |
| C | Context and goal | What situation, source material, objective, and success condition define the work? |
| L | Limits and exclusions | What must the responder avoid, preserve, refuse, or leave out? |
| E | Expected output | What format, sections, length, evidence, and decision use are required? |
| A | Audience | Who receives the output, what do they already know, and what tone/depth fits them? |
| R | Role/Process | What stance, expertise, method, and sequence should guide the work? |
| + | Iterate and verify | What failure signal, revision rule, and pass-fail test decide whether the answer is good enough? |

## Why It Works

- Clark & Brennan: communication depends on common ground, feedback, contribution, and repair. C.L.E.A.R.+ makes common ground explicit before execution.
- Chris Voss: calibrated questions expose assumptions and keep negotiation practical. The workshop uses audience prompts to surface what each participant assumed was obvious.
- Nancy Duarte: strong starts, memorable middles, and Peak-End closes improve retention. The workshop uses a start ritual, the tree-lens experiment, and a commitment close.
- Vaswani et al.: transformer systems attend to supplied context. Better instructions improve the context an AI can use, but verification remains necessary.

## Failure Mapping

- Generic output: weak Context or Expected Output.
- Unsafe, invented, or non-compliant output: weak Limits.
- Wrong tone or depth: weak Audience.
- Poor reasoning path: weak Role/Process.
- Unstable quality across attempts: missing Iterate/Verify.

## Diagnose -> Isolate -> Constrain

1. Diagnose the specific failed C.L.E.A.R.+ field.
2. Isolate one variable and change only that field.
3. Constrain the next attempt with exclusions, source boundaries, and acceptance checks.

## Zero-Trust Data Governance

Use these constraints for data-sensitive work:

- Do not invent facts, citations, numbers, or source names.
- Do not include confidential data in prompts.
- Do not make claims without traceable evidence.
- Do not expand beyond the provided source set.
- If evidence is missing, state what is missing and stop at the supported conclusion.

## Minimal Prompt Skeleton

```text
Role/Process:
Context and Goal:
Limits and Exclusions:
Expected Output:
Audience:
Iteration and Verification:
```

## Six-Point Peer Rubric

A refactored prompt passes when it has:

- Clear business or communication context.
- Explicit exclusions and non-goals.
- Specific output format and completion criteria.
- Named audience and tone/depth fit.
- Role/process instructions that shape the work.
- Verification criteria that can reject a bad answer.
