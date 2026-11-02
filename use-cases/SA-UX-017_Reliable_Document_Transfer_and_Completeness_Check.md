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

## Detailed scenario and test oracle — added 2026-11-02

**Scenario:** Example: A long Claude critique or ZIP is pasted into ChatGPT but half the text disappears; user incorrectly believes both assistants reviewed the complete material.

**Expected main flow:** Exchange a manifest: filename, declared length/size, version, source and a checksum if available. After transfer, compare actual content and show missing/truncated items before downstream critique.

**Failure and recovery:** If checksum or complete source is unavailable, label completeness unverified and do not give a confident 'full document reviewed' claim.

**Evaluation:** Transfer a multi-file archive including a deliberately truncated item and repeated filenames; measure detection, recovery and source traceability.

**Related records:** SA-UX-011, SA-UX-018.

**Evidence boundary:** This test case is based on the Sadhana user's discussion and a reconstructed design proposal. It remains untested; do not claim the product has these capabilities.
