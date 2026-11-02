# SA-UX-024 — Status Metadata Hidden From Final Deliverables

**Status:** 🟠 Draft requirement added 2026-11-02; original evidence and usability validation outstanding.
**Source:** Retrospective reconstruction from Sadhana Human–AI Design Partnership discussions, not a verbatim historic transcript or verified general product defect.

## 1. Intended outcome
Make the interaction dependable, accessible and low-friction without depriving the person of control.

## 2. Context / trigger
Workflow markers help the learner and AI agents track work, but visible traffic-light symbols in final university papers, code or client documents are distracting and not part of the deliverable.

## 3. Observations, evidence and uncertainty
The project lead described this need in prior discussions. The source conversation has not been independently attached to this record. Implementation feasibility and prevalence among other users remain unknown.

## 4. Problem impact
Lost work, extra supervision, confusion or unnecessary repeated actions in research/design workflows.

## 5. Preconditions
An identified project, a correctly identified task/session, available permissions and a truthful record of actions; additional integrations only when explicitly connected.

## 6. Proposed main interaction
Keep workflow status in metadata, dashboard or working draft; export a clean human-approved final artifact without status indicators. Preserve the traceable internal audit.

## 7. Alternatives and constraints
A final document may deliberately include a status chart only if the author chooses it as content; never strip status information from research where it is itself the subject.

## 8. Acceptance criteria
- A participant can correctly identify what happened and what action is available next.
- The interface does not claim a saved, verified or background-running task without supporting state evidence.
- The person's approval boundaries and accessible text labels remain visible.
- The proposed interaction does not silently change another project, version or final document.

## 9. Failure / recovery
No measured progress, permissions, stale state, or an interrupted task must produce an explicit honest state and a safe recovery path rather than a deceptive success signal.

## 10. Evaluation plan
Test draft, awaiting review, accepted output and final PDF/code export; verify internal history remains but unintended status badges do not leak into final copies.

## 11. Related use cases
SA-UX-009, SA-UX-018, SA-UX-022.

## 12. Next action / completion boundary
Create low-fidelity flow and expected-results test sheet; link original conversation excerpts if recoverable; perform tests. This document is not evidence that the software feature is already implemented.
