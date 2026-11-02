# Sadhana case study — Assisted invoice and purchase-order wizard

**Status:** Draft interaction brief reconstructed on 2026-11-02. Business workflow is illustrative and unimplemented. No real client data is stored here.

## Problem
A person entering a routine proforma invoice or purchase order should not have to repeatedly look up the same customer, job description, discount, delivery or parts information. However, automatic completion can silently introduce wrong totals, wrong folder assignments or unauthorised financial actions.

## Suggested wizard flow (user-origin)
1. **Company / client:** Search authorised contact database when the person types a client name; show matching records and ask for selection if ambiguous. Never invent contact details.
2. **Work description:** For known tasks (example 'hard drive change'), suggest previously used work steps and time estimates from provenance-labelled past jobs; person can edit.
3. **Amounts and tax:** Calculate estimated work and parts, apply a client-specific discount only when validated, and apply the legitimate tax rate determined by authorised business rules. Do not allow an AI to override government-controlled VAT rules.
4. **Parts check:** Indicate known stock availability; if missing, compare supplier prices, lead times and suitability; request explicit purchasing confirmation rather than placing an order automatically.
5. **Preview:** Show recipient, work, subtotals, discount, tax, final amount, due/response date and destination folder before saving.
6. **Save as proforma:** Produce the correct document type and store it in the client/job folder when authorised and verified.
7. **Send and follow up:** Show recipient, email content and follow-up interval (example ten days) for approval before consequential sending or scheduling.
8. **Convert to invoice / process payment:** Treat as a separate higher-authority action requiring explicit human confirmation.

## Error and recovery interaction
- If a proposed destination folder does not match the selected client (example, document for Client B about to be saved in AC Supplies), present a destination warning and ask whether to continue.
- If a discount has not been validated when Save is pressed, put a clear red-square error label next to that field, move focus to it, explain the issue and block save.
- If the client name has several matches, show evidence and choices rather than picking one silently.
- If parts prices are stale or unavailable, show uncertainty and do not fabricate a confirmed quote.
- If an external send or save fails, preserve the draft, show exactly what did and did not happen, and avoid duplicate transmission during retry.

## Human/AI boundary
AI may suggest supplier comparisons, text, work steps, time estimates and error checks. The human retains approval over recipient, contractual/financial commitments, sending, purchases, tax exceptions and payment processing. VAT compliance requires expert/business verification; this design does not give tax advice.

## Usability test matrix
| Test | Expected outcome |
|---|---|
| Recognised client | Correct customer candidate with source shown |
| Two clients with similar names | Explicit disambiguation |
| Incorrect destination folder | Warning and correctable choice |
| Invalid client discount | Save blocked, focus moves to field |
| New job with no history | No invented past estimate |
| Parts not in stock | Alternatives shown; no automatic purchase |
| User requests conversion to final invoice | Explicit approval gate |
| Send fails after a save | Draft retained, separate save/send status |

## Deliverables and related cases
Next create a low-fidelity screen flow, test data set and error-state specification. [SA-UX-019](../../use-cases/SA-UX-019_Error_Prevention_for_Assisted_Business_Documents.md) · [SA-UX-022](../../use-cases/SA-UX-022_Human_Approval_and_AI_Autonomy_Boundaries.md). Do not use real client names, addresses, financial records or supplier credentials in this public repo.
