# SA-UX-021 — Cross-Device Voice Limit and Microphone Error Explanation

Status: Draft saved; historical source evidence and product feasibility not yet independently verified.
Scope: Human–AI Design Partnership / Sadhana. Applies to ChatGPT and/or Claude as a proposed improvement, not a verified product defect.

## User need and observed/reported problem
A disabled microphone on desktop while voice works on phone gives no explanation of whether a limit, permission, device fault or bug is responsible.

## Proposed design behavior
When voice input is unavailable, show a reason if known and targeted recovery actions; do not leave a grey inert control or falsely claim a limit.

## User story
As a person collaborating with AI across research and real tasks, I want cross-device voice limit and microphone error explanation so I can trust the interface and retain control.

## Acceptance criteria
- Show what is known, unknown, planned, running, saved and verified without conflating them.
- Preserve the correct project and task context; provide a clear recovery path if unavailable.
- Do not claim a completed external action without checking the resulting record.
- Keep user control over consequential decisions and permissions.

## Failure and recovery tests
Test quota exhaustion, denied microphone permission, network failure and device inconsistency; confirm reason matches actual state.

## Evidence and follow-up
Reconstructed from prior Sadhana discussions; obtain original dated conversation excerpts and independent product tests before marking verified. Check for overlaps with SA-UX-001–012 and consolidate where necessary rather than counting duplicates as separate defects.
