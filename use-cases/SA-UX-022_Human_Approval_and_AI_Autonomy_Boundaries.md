# SA-UX-022 — Human Approval and AI Autonomy Boundaries

Status: Draft saved; historical source evidence and product feasibility not yet independently verified.
Scope: Human–AI Design Partnership / Sadhana. Applies to ChatGPT and/or Claude as a proposed improvement, not a verified product defect.

## User need and observed/reported problem
An assistant may infer permission to send documents, spend money or change legally controlled values when the person only asked for a draft.

## Proposed design behavior
Separate suggest, draft, validate and execute permissions; show preview and explicit confirmation for consequential actions; prohibit unapproved tax edits, payment or purchase.

## User story
As a person collaborating with AI across research and real tasks, I want human approval and ai autonomy boundaries so I can trust the interface and retain control.

## Acceptance criteria
- Show what is known, unknown, planned, running, saved and verified without conflating them.
- Preserve the correct project and task context; provide a clear recovery path if unavailable.
- Do not claim a completed external action without checking the resulting record.
- Keep user control over consequential decisions and permissions.

## Failure and recovery tests
Attempt proforma-to-invoice conversion, parts order and VAT override; verify blocked actions and audit trail.

## Evidence and follow-up
Reconstructed from prior Sadhana discussions; obtain original dated conversation excerpts and independent product tests before marking verified. Check for overlaps with SA-UX-001–012 and consolidate where necessary rather than counting duplicates as separate defects.
