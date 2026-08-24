# Copilot Instructions for Workshop Repository

## Repository Purpose
Maintain a facilitator-ready workshop suite for The Architecture of Intent (120-minute Professional Prompting & Human Communication session).

## Agent Operating Protocol
- Assume full task ownership and execute requests end-to-end without unnecessary pause prompts.
- Use available tools and sub-agents autonomously when they improve speed, accuracy, or coverage.
- Prefer implementation plus verification in the same run; do not stop at planning unless explicitly asked.
- Surface blockers only when they are non-discoverable or require user authority.

## Autonomous Git Delivery Protocol
- Create a dedicated feature branch for each non-trivial change.
- Use conventional commit messages.
- Push branch and create a Pull Request into `main`.
- Merge the PR when checks pass or when repository policy permits direct merge.
- Return to `main`, pull latest, and delete merged feature branches both locally and remotely.
- Preserve unrelated local changes; never discard user work without explicit permission.

## Source of Truth
- Timing and segment sequence must match the 120-minute structure in script.md.
- Framework naming must remain C.L.E.A.R.+ in all assets.
- Terminology alignment required across index.html, cheatsheet.html, script.md, README.md, llms.txt, and docs/.

## Content Conventions
- Tone: practical, professional, direct.
- Prioritize clear delegation language over motivational prose.
- Include negative constraints and verification steps in prompt examples.
- Keep docs token-efficient: low fluff, high semantic density.

## File Responsibilities
- index.html: Reveal.js deck, primary teaching flow, facilitator cues.
- cheatsheet.html: fast reference card for participants.
- script.md: exact speaking runbook and pacing controls.
- docs/: concise machine/human support docs.
- llms.txt: compressed context for LLM ingestion.

## Editing Rules
- Preserve existing visual theme in deck-related assets.
- Preserve responsive behavior for desktop and mobile.
- Do not change workshop duration without updating all dependent files.
- When adding examples, always include at least one explicit exclusion.

## Presenter Notes Requirements
- Keep main slide viewport free from facilitator buttons and time badge elements.
- Store timing metadata and full speaker guidance in per-slide speaker-note structures.
- Speaker notes must contain both verbatim spoken script and explicit facilitation actions.
- Maintain keyboard access for presenter notes via `s` toggle and keep behavior case-insensitive.

## Validation Checklist Before Commit
- Total workshop time = 120 minutes.
- All seven agenda segments (including break) present and ordered.
- C.L.E.A.R.+ expanded consistently.
- Diagnose-Isolate-Constrain loop included.
- No dead links between repository assets.
- `s` key notes toggle works and ignores typing contexts.
- No facilitator button or badge-time visual chips remain in the presentation viewport.
