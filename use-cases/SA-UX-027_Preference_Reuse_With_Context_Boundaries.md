# SA-UX-027 — Preference Reuse With Context Boundaries

**Status:** 🟠 Draft requirement added 2026-11-02; original evidence and usability validation outstanding.
**Source:** Retrospective reconstruction from Sadhana Human–AI Design Partnership discussions, not a verbatim historic transcript or verified general product defect.

## 1. Intended outcome
Make the interaction dependable, accessible and low-friction without depriving the person of control.

## 2. Context / trigger
Repeated project preferences can be ignored, or an AI may apply a remembered rule in the wrong context and change the user's work unexpectedly.

## 3. Observations, evidence and uncertainty
The project lead described this need in prior discussions. The source conversation has not been independently attached to this record. Implementation feasibility and prevalence among other users remain unknown.

## 4. Problem impact
Lost work, extra supervision, confusion or unnecessary repeated actions in research/design workflows.

## 5. Preconditions
An identified project, a correctly identified task/session, available permissions and a truthful record of actions; additional integrations only when explicitly connected.

## 6. Proposed main interaction
Use explicit project instructions as authoritative. Treat repeated patterns as candidates, not permanent model retraining. Apply status rules to internal workflows, preserve human control of titles, voice/typing, and thinking effort, and ask when a preference conflicts with the task.

## 7. Alternatives and constraints
Show the source and scope of a preference; allow correction; do not insert internal status decorations into printed academic outputs.

## 8. Acceptance criteria
- A participant can correctly identify what happened and what action is available next.
- The interface does not claim a saved, verified or background-running task without supporting state evidence.
- The person's approval boundaries and accessible text labels remain visible.
- The proposed interaction does not silently change another project, version or final document.

## 9. Failure / recovery
No measured progress, permissions, stale state, or an interrupted task must produce an explicit honest state and a safe recovery path rather than a deceptive success signal.

## 10. Evaluation plan
Test a rule repeated across sessions; then test contrary request and final-print export; measure correct application without intrusive repetition.

## 11. Related use cases
SA-UX-012, SA-UX-022, SA-UX-024.

## 12. Next action / completion boundary
Create low-fidelity flow and expected-results test sheet; link original conversation excerpts if recoverable; perform tests. This document is not evidence that the software feature is already implemented.
