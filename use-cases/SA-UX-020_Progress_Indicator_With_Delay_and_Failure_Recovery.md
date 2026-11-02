# SA-UX-020 — Progress Indicator With Delay and Failure Recovery

Status: Draft saved; historical source evidence and product feasibility not yet independently verified.
Scope: Human–AI Design Partnership / Sadhana. Applies to ChatGPT and/or Claude as a proposed improvement, not a verified product defect.

## User need and observed/reported problem
An opaque spinner during a long document analysis gives no indication of work, delay or failure.

## Proposed design behavior
Show an amber progress indicator with countdown only when grounded in a real estimate; expand into a delay banner if exceeded; on failure show red error reason and Retry; on verified success show completion then clear.

## User story
As a person collaborating with AI across research and real tasks, I want progress indicator with delay and failure recovery so I can trust the interface and retain control.

## Acceptance criteria
- Show what is known, unknown, planned, running, saved and verified without conflating them.
- Preserve the correct project and task context; provide a clear recovery path if unavailable.
- Do not claim a completed external action without checking the resulting record.
- Keep user control over consequential decisions and permissions.

## Failure and recovery tests
Test nominal 30-second analysis, 60-second delay, cancelled task, failure, and inaccurate estimate; never imply work continues after session ends.

## Evidence and follow-up
Reconstructed from prior Sadhana discussions; obtain original dated conversation excerpts and independent product tests before marking verified. Check for overlaps with SA-UX-001–012 and consolidate where necessary rather than counting duplicates as separate defects.
