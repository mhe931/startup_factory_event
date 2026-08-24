# The Architecture of Intent Workshop Suite

120-minute Professional Prompting and Human Communication workshop delivery package.

## Goal of This Refactor
- Keep the public slide projection surface clean: no visible coaching UI, badges, or facilitator notes.
- Isolate facilitator coaching strictly inside the Presenter View panel toggled with S.
- Integrate AJ&Smart-style facilitation mechanics: strong start rituals, visible progress tracking, dynamic example harvesting, and Peak-End highlight close.

## Runtime Map (120 Minutes Total)
- 00:00-00:15 | Opening Ritual and Baseline
- 00:15-00:35 | Human Delegation Lab
- 00:35-00:50 | Assumption Gap and C.L.E.A.R.+ Engine
- 00:50-01:00 | Break and Informal Table Chat
- 01:00-01:25 | Prompt Makeover Studio
- 01:25-01:50 | Live Iteration Crucible
- 01:50-02:00 | Highlight Session and Commitments

## Structured Coaching Schema
Each slide and script segment uses identical fields:
- TIME
- SAY (Verbatim)
- DO (Facilitation Actions)
- ASK (Audience Prompts)
- CAPTURE and ADAPT
- FACILITATION RITUAL / PRO-TIP

## Presenter View Isolation
- Exactly one global `#speaker-overlay` exists outside the slide viewport.
- Overlay is hidden by default and only shown via S key.
- Escape key closes the overlay.
- Overlay fields are populated from slide metadata:
  - data-speaker-time
  - data-speaker-say
  - data-speaker-do
  - data-speaker-ask
  - data-speaker-adapt
  - data-speaker-ritual

## AJ&Smart Facilitation Techniques Applied
- Serial Position + Strong Start Ritual in opening block.
- Visible progress tracking after Segments 2, 5, and 6 (public board tick).
- Dynamic example harvesting from participant pain points for Segments 5 and 6.
- Peak-End Rule through final Highlight Session and commitment round-robin.

## Pedagogical Case Set (Synchronized Across Slides + Notes)
- Tree Climbing scenario: demonstrate how role, audience, and limits alter identical goals.
- Interpersonal conflict resolution: demonstrate tone, accountability, and de-escalation framing.
- Shared responsibility handoff: demonstrate ownership language without blame.
- Segment alignment: introduced in Segment 2 lab, deconstructed in Segment 3 engine, reused in Segments 5 and 6 practice.

## Repository Files
- index.html: slide deck and presenter coaching overlay.
- script.md: 1:1 facilitator coaching script aligned to slide metadata.
- cheatsheet.html: participant desk card and ritual guardrails.
- llms.txt: token-dense LLM entrypoint with synchronized coaching map.
- docs/workshop-summary.md: compact operational summary.
- docs/prompting-framework.md: C.L.E.A.R.+ protocol reference.
