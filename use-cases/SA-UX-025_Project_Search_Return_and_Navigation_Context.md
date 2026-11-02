# SA-UX-025 — Project Search Return and Navigation Context

**Status:** 🟠 Draft requirement added 2026-11-02; original evidence and usability validation outstanding.
**Source:** Retrospective reconstruction from Sadhana Human–AI Design Partnership discussions, not a verbatim historic transcript or verified general product defect.

## 1. Intended outcome
Make the interaction dependable, accessible and low-friction without depriving the person of control.

## 2. Context / trigger
Searching for a prior project chat or file can interrupt voice work or return the person to the wrong view.

## 3. Observations, evidence and uncertainty
The project lead described this need in prior discussions. The source conversation has not been independently attached to this record. Implementation feasibility and prevalence among other users remain unknown.

## 4. Problem impact
Lost work, extra supervision, confusion or unnecessary repeated actions in research/design workflows.

## 5. Preconditions
An identified project, a correctly identified task/session, available permissions and a truthful record of actions; additional integrations only when explicitly connected.

## 6. Proposed main interaction
Preserve the active project, thread, current cursor/task state and voice-session context while searching. Provide a clear Return to where I was action that restores the correct view without generating a new chat.

## 7. Alternatives and constraints
If the original session has expired, disclose that and offer its last confirmed checkpoint instead of implying live resumption.

## 8. Acceptance criteria
- A participant can correctly identify what happened and what action is available next.
- The interface does not claim a saved, verified or background-running task without supporting state evidence.
- The person's approval boundaries and accessible text labels remain visible.
- The proposed interaction does not silently change another project, version or final document.

## 9. Failure / recovery
No measured progress, permissions, stale state, or an interrupted task must produce an explicit honest state and a safe recovery path rather than a deceptive success signal.

## 10. Evaluation plan
Open search from within a project and during voice; follow a search result and return; test cancelled search, stale thread and expired voice.

## 11. Related use cases
SA-UX-001, SA-UX-006, SA-UX-010, SA-UX-013.

## 12. Next action / completion boundary
Create low-fidelity flow and expected-results test sheet; link original conversation excerpts if recoverable; perform tests. This document is not evidence that the software feature is already implemented.
