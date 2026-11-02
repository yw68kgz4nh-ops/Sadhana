# SA-UX-003 — Renaming and Managing Project Resources

Status: Draft reconstructed from project notes.

Intended outcome: The assistant can rename or organise resources when authorised, or clearly state the exact limitation and use the lowest-effort alternative.

Observed problem: The person asked the assistant to rename a conversation or resource. The assistant could not perform and verify the change with the tools available in that interaction.

Impact: Manual work shifted back to the person and extra supervision of a routine action.

Facts and uncertainty: The rename was not completed through the available tools. It was not established whether another UI route or account capability could have enabled it.

Improvement: Expose resource-management actions through authorised tools. If unavailable, explain the limitation briefly and do not present a manual route as an action the assistant will perform.

Test: Rename a test resource, verify its new title, count user actions, and confirm no unrelated resource changed.

---

## Structured use-case expansion — 2026-11-02

**Provenance and status:** Retrospective reconstruction of Sadhana discussions; no independent usability test or root-cause confirmation. Original notes above are preserved.

### 1. Intended outcome and 2. Context / trigger
A proposed rename of a chat, prompt, or project is made while documents link to the old name.

### 3. Evidence / uncertainty and 4. Problem impact
See the original observation and uncertainty above. This describes a reported interaction problem, not a proven defect affecting every user.

### 5. Preconditions
Assistant has verified permission and a suitable tool for the exact resource type.

### 6. Main interaction flow
Show original and proposed names, affected links, and confirmation; execute authorised change; read back the resource and verify references or record any broken links.

### 7. Alternatives
If the action is unsupported, supply a short precise manual step and don't claim execution.

### 8. Acceptance criteria
- No unapproved rename takes place.
- A successful rename has a verifiable record and links remain valid or are explicitly flagged.
- The user receives a truthful supported/unsupported result.

### 9. Failure and recovery
Name conflicts, link failures, or missing permission: preserve original, report blocker and do not mark finished.

### 10. Evaluation plan
Try rename of linked and unlinked test resources; measure broken references and avoidable user work.

### 11. Dependencies and related records
SA-UX-004, SA-UX-018; project-management/Design_Principles.md.

### 12. Next action and completion boundary
Collect dated original screenshots/transcripts where accessible; run usability scenarios and log both observed and expected outcomes. The document is a usable **draft requirements record**, not a verified software improvement.
