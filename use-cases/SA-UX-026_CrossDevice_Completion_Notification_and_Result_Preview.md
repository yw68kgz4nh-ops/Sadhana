# SA-UX-026 — CrossDevice Completion Notification and Result Preview

**Status:** 🟠 Draft requirement added 2026-11-02; original evidence and usability validation outstanding.
**Source:** Retrospective reconstruction from Sadhana Human–AI Design Partnership discussions, not a verbatim historic transcript or verified general product defect.

## 1. Intended outcome
Make the interaction dependable, accessible and low-friction without depriving the person of control.

## 2. Context / trigger
A person must repeatedly reopen a chat to check if a lengthy task finished; completion can be mistaken for a saved and verified outcome.

## 3. Observations, evidence and uncertainty
The project lead described this need in prior discussions. The source conversation has not been independently attached to this record. Implementation feasibility and prevalence among other users remain unknown.

## 4. Problem impact
Lost work, extra supervision, confusion or unnecessary repeated actions in research/design workflows.

## 5. Preconditions
An identified project, a correctly identified task/session, available permissions and a truthful record of actions; additional integrations only when explicitly connected.

## 6. Proposed main interaction
On a truly asynchronous task with appropriate permission, show a concise desktop preview and optional phone notification tied to the authoritative task record, naming finished vs saved vs verified separately.

## 7. Alternatives and constraints
No automatic notifications or continuation are implied when a background service is not available or permitted; dismissing the notice must not erase the deliverable.

## 8. Acceptance criteria
- A participant can correctly identify what happened and what action is available next.
- The interface does not claim a saved, verified or background-running task without supporting state evidence.
- The person's approval boundaries and accessible text labels remain visible.
- The proposed interaction does not silently change another project, version or final document.

## 9. Failure / recovery
No measured progress, permissions, stale state, or an interrupted task must produce an explicit honest state and a safe recovery path rather than a deceptive success signal.

## 10. Evaluation plan
Test notification permission off, offline phone, duplicate alerts, task failed, task finished without verification, tapping preview and dismissing it.

## 11. Related use cases
SA-UX-009, SA-UX-014, SA-UX-020.

## 12. Next action / completion boundary
Create low-fidelity flow and expected-results test sheet; link original conversation excerpts if recoverable; perform tests. This document is not evidence that the software feature is already implemented.
