# SA-UX-016 — Project and Library Location Clarity

Status: Draft saved; historical source evidence and product feasibility not yet independently verified.
Scope: Human–AI Design Partnership / Sadhana. Applies to ChatGPT and/or Claude as a proposed improvement, not a verified product defect.

## User need and observed/reported problem
People cannot tell whether a file is in a Project, Library, chat attachment or GitHub, and may create competing copies.

## Proposed design behavior
Show a clear location breadcrumb, authoritative-source label and explicit save destination; explain when a file has not actually been uploaded.

## User story
As a person collaborating with AI across research and real tasks, I want project and library location clarity so I can trust the interface and retain control.

## Acceptance criteria
- Show what is known, unknown, planned, running, saved and verified without conflating them.
- Preserve the correct project and task context; provide a clear recovery path if unavailable.
- Do not claim a completed external action without checking the resulting record.
- Keep user control over consequential decisions and permissions.

## Failure and recovery tests
Create draft in chat; attempt Project save; verify destination and failure states; inspect on phone and desktop.

## Evidence and follow-up
Reconstructed from prior Sadhana discussions; obtain original dated conversation excerpts and independent product tests before marking verified. Check for overlaps with SA-UX-001–012 and consolidate where necessary rather than counting duplicates as separate defects.
