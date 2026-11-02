# SA-UX-013 — Voice Session Resume and Verified Checkpoint

Status: Draft saved; historical source evidence and product feasibility not yet independently verified.
Scope: Human–AI Design Partnership / Sadhana. Applies to ChatGPT and/or Claude as a proposed improvement, not a verified product defect.

## User need and observed/reported problem
After returning to voice or reopening the app, the person needs to resume the correct Sadhana task without reconstructing it.

## Proposed design behavior
Offer a non-intrusive Resume previous work? panel naming project, thread, last verified checkpoint and next step; never silently switch threads.

## User story
As a person collaborating with AI across research and real tasks, I want voice session resume and verified checkpoint so I can trust the interface and retain control.

## Acceptance criteria
- Show what is known, unknown, planned, running, saved and verified without conflating them.
- Preserve the correct project and task context; provide a clear recovery path if unavailable.
- Do not claim a completed external action without checking the resulting record.
- Keep user control over consequential decisions and permissions.

## Failure and recovery tests
Reopen after interruption; choose Resume or Not now; verify thread and checkpoint match; test stale/missing checkpoint and recovery.

## Evidence and follow-up
Reconstructed from prior Sadhana discussions; obtain original dated conversation excerpts and independent product tests before marking verified. Check for overlaps with SA-UX-001–012 and consolidate where necessary rather than counting duplicates as separate defects.
