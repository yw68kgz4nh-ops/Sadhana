# SA-UX-014 — Cross-Device Active Work Visibility

Status: Draft saved; historical source evidence and product feasibility not yet independently verified.
Scope: Human–AI Design Partnership / Sadhana. Applies to ChatGPT and/or Claude as a proposed improvement, not a verified product defect.

## User need and observed/reported problem
Work started on a computer can appear absent on the phone, leaving the person uncertain whether work is running, paused or finished.

## Proposed design behavior
Display the same authoritative task state, device and last update across supported devices, with explicit paused/offline/unknown states rather than invented progress.

## User story
As a person collaborating with AI across research and real tasks, I want cross-device active work visibility so I can trust the interface and retain control.

## Acceptance criteria
- Show what is known, unknown, planned, running, saved and verified without conflating them.
- Preserve the correct project and task context; provide a clear recovery path if unavailable.
- Do not claim a completed external action without checking the resulting record.
- Keep user control over consequential decisions and permissions.

## Failure and recovery tests
Start a task on desktop and inspect phone; disconnect either device; ensure no phantom background activity or false completion.

## Evidence and follow-up
Reconstructed from prior Sadhana discussions; obtain original dated conversation excerpts and independent product tests before marking verified. Check for overlaps with SA-UX-001–012 and consolidate where necessary rather than counting duplicates as separate defects.
