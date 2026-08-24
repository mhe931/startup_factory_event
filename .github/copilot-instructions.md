# Copilot Instructions for Workshop Repository

## Repository Purpose
Maintain a facilitator-ready workshop suite for The Architecture of Intent (90-minute Professional Prompting & Human Communication session).

## Source of Truth
- Timing and segment sequence must match the 90-minute structure in script.md.
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

## Validation Checklist Before Commit
- Total workshop time = 90 minutes.
- All six agenda segments present and ordered.
- C.L.E.A.R.+ expanded consistently.
- Diagnose-Isolate-Constrain loop included.
- No dead links between repository assets.
