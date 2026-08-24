# THE ARCHITECTURE OF SHARED MEANING

Aligning Human Minds and AI Intelligence Through the C.L.E.A.R.+ Protocol is a 120-minute workshop suite for professional prompting, delegation, and shared understanding.

## Outcome

Participants learn to turn implicit intent into explicit instructions that work for both humans and AI systems. The workshop emphasizes practical delegation, negative constraints, audience calibration, and verification before trust.

## Runtime Map

| Segment | Time | Duration | Focus |
| --- | --- | ---: | --- |
| 1 | 00:00-00:15 | 15 min | The Intent & Meaning Bottleneck: Assumption Gap, Mars Climate Orbiter, Start Ritual |
| 2 | 00:15-00:35 | 20 min | The Human Delegation Lab: Architect vs. Builder, zero-feedback vs. calibrated grounding |
| 3 | 00:35-00:43 | 8 min | The Multi-Lens Experiment: Can we climb a tree? child, psychologist, risk officer, arborist, heavy-eared alien |
| 4 | 00:43-00:50 | 7 min | The C.L.E.A.R.+ Universal Protocol |
| 5 | 00:50-01:00 | 10 min | Reset, Bio-Break & Purposeful Table Alignment |
| 6 | 01:00-01:25 | 25 min | The Executive Makeover Studio: triad refactoring, 12-scenario library, six-point peer rubric |
| 7 | 01:25-01:50 | 25 min | The Live Iteration Crucible & Steering Protocol: Diagnose -> Isolate -> Constrain, zero-trust data governance |
| 8 | 01:50-02:00 | 10 min | Synthesis, Leadership Commitments & The Peak-End Close |

Total: 120 minutes.

## C.L.E.A.R.+ Protocol

- **C - Context:** define the situation, source material, objective, and success condition.
- **L - Limits:** state exclusions, boundaries, risks, and non-goals.
- **E - Expected Output:** specify format, sections, length, and decision use.
- **A - Audience:** tune depth, language, tone, and assumptions.
- **R - Role/Process:** assign stance, expertise, and reasoning workflow.
- **+ - Iterate/Verify:** diagnose failures, isolate one change, constrain the next attempt, and apply pass-fail checks.

## Theoretical Foundations

- Clark & Brennan: common ground explains why communication requires shared context, feedback, and repair.
- Chris Voss: calibrated questions and explicit constraints improve negotiation and reduce hidden assumptions.
- Nancy Duarte: strong opening and closing moments shape retention through contrast, story, and audience movement.
- Vaswani et al.: attention-based AI systems respond to context and token framing; reliable outputs require disciplined input structure and verification.

## Presenter View

[index.html](index.html) contains a custom responsive slide deck and a singleton `#speaker-overlay` outside `<main>`. The public slide viewport contains no facilitator buttons, visible time badges, or raw speaker markup.

Presenter controls:

- `s` or `S`: toggle speaker notes, ignored while typing in inputs or editable fields.
- `Escape`: close speaker notes.
- Arrow keys, PageUp/PageDown, Home, End, Space: navigate slides.

Each `.slide` stores complete speaker-note metadata in `data-speaker-time`, `data-speaker-say`, `data-speaker-do`, `data-speaker-ask`, `data-speaker-adapt`, and `data-speaker-ritual`. JavaScript hydrates the overlay on load, slide change, and speaker-view toggle.

## Repository Files

- [index.html](index.html): interactive presentation and presenter overlay.
- [script.md](script.md): full verbatim speaker transcript, actions, prompts, adaptation notes, and facilitation rituals for all eight segments.
- [cheatsheet.html](cheatsheet.html): participant desk reference for C.L.E.A.R.+ and Diagnose -> Isolate -> Constrain.
- [llms.txt](llms.txt): token-optimized workshop context for LLM onboarding.
- [docs/prompting-framework.md](docs/prompting-framework.md): protocol reference and theoretical grounding.
- [docs/workshop-summary.md](docs/workshop-summary.md): operational delivery summary.

## Delivery Checklist

- Confirm all eight segments are present and ordered.
- Confirm all listed durations sum to exactly 120 minutes.
- Keep C.L.E.A.R.+ terminology unchanged across files.
- Keep the break at 00:50-01:00 and restart on time.
- Use participant examples in Segments 6 and 7 before generic scenarios.
- Require at least one explicit exclusion and one verification check in every production prompt.
- Keep the presenter overlay hidden until toggled with `s`.
