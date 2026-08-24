# The Architecture of Intent Workshop Suite

120-minute Professional Prompting and Human Communication delivery package.

## Purpose
This repository provides an active facilitator coaching system for high-engagement workshop delivery, using exact dialogue, movement cues, audience prompts, dynamic example capture, and strict pacing.

## Coaching Cue Map (Identical to script.md and llms.txt)
- 00:00-00:08 | Opening and Contract
  - SAY focus: welcome hook and confidence reset
  - ASK focus: name, goal, gut-feeling about AI, one output regret
  - CAPTURE focus: goals and pain points board (tag M or I)
- 00:08-00:15 | Agenda Activation
  - SAY focus: experiential pacing and mandatory break framing
  - ASK focus: hardest segment and peer-audit familiarity
  - CAPTURE focus: adaptation priorities for later segments
- 00:15-00:35 | Human Delegation Lab
  - SAY focus: no gestures and no questions in Round 1
  - ASK focus: assumption-gap reveal from Architect and Builder views
  - CAPTURE focus: three participant assumption-gap cases for Segment 6
- 00:35-00:50 | Assumption Gap and C.L.E.A.R.+ Engine
  - SAY focus: weak output as instruction ambiguity
  - ASK focus: highest-leverage field and skipped field habits
  - CAPTURE focus: convert one participant case to live scaffold
- 00:50-01:00 | Break and Informal Table Chat
  - SAY focus: mandatory pause, movement, coffee, and table reflection
  - ASK focus: one unresolved challenge per table
  - CAPTURE focus: assign table challenges to triads
- 01:00-01:25 | Prompt Makeover Studio
  - SAY focus: triad roles and participant-owned case refactoring
  - ASK focus: strongest constraint and underspecified output checks
  - CAPTURE focus: two participant cases for room critique
- 01:25-01:50 | Live Iteration Crucible
  - SAY focus: one-variable iteration with visible revision logs
  - ASK focus: failure diagnosis, leak detection, and rejection tests
  - CAPTURE focus: unresolved case turned into live debug demo
- 01:50-02:00 | Synthesis and Commitment Contract
  - SAY focus: concrete weekly commitment and pass-fail rule ownership
  - ASK focus: confidence shift and accountability partner
  - CAPTURE focus: map final contracts back to opening pain points

## Repository Structure
- index.html: Reveal.js deck with structured facilitator metadata and dynamic coaching overlay.
- script.md: full 120-minute coaching script with TIME, SAY, DO, ASK, CAPTURE and ADAPT, PRO-TIPS.
- cheatsheet.html: participant quick reference card.
- llms.txt: token-dense machine onboarding entry with synchronized coaching cues.
- docs/workshop-summary.md: compact operations summary.
- docs/prompting-framework.md: C.L.E.A.R.+ protocol reference.
- .github/copilot-instructions.md: autonomous delivery conventions.

## Presenter Overlay Controls
- Press S to toggle coaching overlay.
- Press Escape to close overlay.
- Overlay updates on slide change and pulls from slide data attributes:
  - data-speaker-time
  - data-speaker-say
  - data-speaker-do
  - data-speaker-ask
  - data-speaker-adapt
  - data-speaker-protip

## Delivery Rules
- Total facilitation runtime is exactly 120 minutes.
- Enforce no-gesture/no-questions rule in Delegation Lab Round 1.
- Use participant-generated examples in Makeover and Iteration blocks.
- Protect break boundary from 00:50 to 01:00.
