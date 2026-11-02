# SA-UX-019 — Error Prevention for Assisted Business Documents

Status: Draft saved; historical source evidence and product feasibility not yet independently verified.
Scope: Human–AI Design Partnership / Sadhana. Applies to ChatGPT and/or Claude as a proposed improvement, not a verified product defect.

## User need and observed/reported problem
An AI invoice or purchase-order wizard may save a document in the wrong client folder, omit discounts, or act without authorization.

## Proposed design behavior
Validate client, work, tax and discount; flag mismatched destination; retrieve existing customer/job data with provenance; require explicit approval before conversion, payment or parts purchase.

## User story
As a person collaborating with AI across research and real tasks, I want error prevention for assisted business documents so I can trust the interface and retain control.

## Acceptance criteria
- Show what is known, unknown, planned, running, saved and verified without conflating them.
- Preserve the correct project and task context; provide a clear recovery path if unavailable.
- Do not claim a completed external action without checking the resulting record.
- Keep user control over consequential decisions and permissions.

## Failure and recovery tests
Test wrong folder, missing discount, unknown customer, unavailable parts, and attempted payment without confirmation.

## Evidence and follow-up
Reconstructed from prior Sadhana discussions; obtain original dated conversation excerpts and independent product tests before marking verified. Check for overlaps with SA-UX-001–012 and consolidate where necessary rather than counting duplicates as separate defects.

## Detailed scenario and test oracle — added 2026-11-02

**Scenario:** Example: A proforma for one customer is accidentally directed to a different client's folder; a client discount has not been validated; the AI suggests ordering unavailable parts.

**Expected main flow:** Wizard validates client, work, discount and tax; shows a folder mismatch warning and moves focus to unverified discount. Parts comparison can be proposed, but buying, sending and invoice conversion require human approval.

**Failure and recovery:** A Save error retains draft data and shows separate states for local draft, stored file, email sent and paid; no silent retry of consequential actions.

**Evaluation:** Use fictional customer data. Test folder mismatch, missing discount, two matching contacts, absent parts, VAT override and proforma conversion; verify each safeguard.

**Related records:** SA-UX-022, research/case-studies/Assisted_Invoice_PO_Wizard_Requirements_v0.1.md.

**Evidence boundary:** The improvement is a design requirement captured retrospectively, not a verified software fix. Testing, provenance and any necessary expert review remain pending.
