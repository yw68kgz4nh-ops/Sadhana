# SA-UX-004 — Plans Presented as Executable Without Capability Verification

Status: Draft reconstructed from project notes; the user's challenge is documented in the project conversation.

Intended outcome: When the assistant says it will carry out steps, the user can trust that capability and permissions have been checked.

Observed problem: The assistant proposed workflows for editing or organising ChatGPT project resources before verifying that it had the tools or permissions to do them. The user pointed out that this wording implied the plan was executable.

Impact: False expectations, wasted time, unnecessary supervision, reduced confidence, and extra coordination work for the user.

Facts and hypotheses: It was observed that actions were proposed before capability verification. The internal cause of that behaviour has not been established. One plausible contributing factor is that conversational planning language blurs the difference between a proposal and an executable workflow.

Improvement: Check tools and permissions first. Distinguish 'can do now', 'requires authorisation', 'user must act', and 'unverified'. Execute authorised work and verify the result rather than handing routine tasks back to the user.

Test: Compare each execution claim against available tools, permission, actual attempt, and verification. Track false promises, unnecessary user actions, and unverified completion claims.

Related prompts: Prompt 14 — Verified Capability and Honest Execution; Prompt 13 — Problem, Limitation and Solution Capture.

---

## Structured use-case expansion — 2026-11-02

**Provenance and status:** Retrospective reconstruction of Sadhana discussions; no independent usability test or root-cause confirmation. Original notes above are preserved.

### 1. Intended outcome and 2. Context / trigger
An assistant says it will create, upload, edit, or continue working in the background.

### 3. Evidence / uncertainty and 4. Problem impact
See the original observation and uncertainty above. This describes a reported interaction problem, not a proven defect affecting every user.

### 5. Preconditions
Any required connector, permission, working mode and result-verification step are identified.

### 6. Main interaction flow
Verify capability first; state what will be executed during the current task; perform action; inspect response; read back external result; report exactly what succeeded and failed.

### 7. Alternatives
For unavailable operations, present a bounded alternative with no misleading promise.

### 8. Acceptance criteria
- Every claim 'saved', 'sent', 'updated', or 'will continue' matches an actual capability and execution record.
- Work that cannot continue after the current session is described as stopped, not background-running.
- User can identify next action for every incomplete item.

### 9. Failure and recovery
Network error or tool timeout after attempting a write: check whether a file exists before retrying to avoid duplicate content.

### 10. Evaluation plan
Audit assistant claims versus tool logs for authorised, denied and partial-failure scenarios.

### 11. Dependencies and related records
SA-UX-009, SA-UX-014, SA-UX-018; Prompt 14.

### 12. Next action and completion boundary
Collect dated original screenshots/transcripts where accessible; run usability scenarios and log both observed and expected outcomes. The document is a usable **draft requirements record**, not a verified software improvement.
