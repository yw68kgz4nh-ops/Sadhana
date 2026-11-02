# SA-UX-017 — Reliable Document Transfer and Completeness Check

Status: Draft saved; historical source evidence and product feasibility not yet independently verified.
Scope: Human–AI Design Partnership / Sadhana. Applies to ChatGPT and/or Claude as a proposed improvement, not a verified product defect.

## User need and observed/reported problem
Large text or ZIP handoffs between ChatGPT and Claude can be truncated, lose folders or omit source conversations.

## Proposed design behavior
Before and after export/import, compare file manifest, counts, hashes where available, and explicit missing/truncated warnings; keep source/version provenance.

## User story
As a person collaborating with AI across research and real tasks, I want reliable document transfer and completeness check so I can trust the interface and retain control.

## Acceptance criteria
- Show what is known, unknown, planned, running, saved and verified without conflating them.
- Preserve the correct project and task context; provide a clear recovery path if unavailable.
- Do not claim a completed external action without checking the resulting record.
- Keep user control over consequential decisions and permissions.

## Failure and recovery tests
Transfer multi-file package with nested directories and long document; deliberately truncate one file; require mismatch alert and retry.

## Evidence and follow-up
Reconstructed from prior Sadhana discussions; obtain original dated conversation excerpts and independent product tests before marking verified. Check for overlaps with SA-UX-001–012 and consolidate where necessary rather than counting duplicates as separate defects.
