# Improvement Backlog — 31 October 2026

**Status:** AMBER TRIANGLE — first population batch; source reconciliation and testing pending.

## Provenance and boundaries
This synthesis uses conversation context supplied to the current session and the repository records read today. It is a reconstructed requirements backlog, not a complete transcript audit. The user's current request authorises populating Sadhana GitHub files. Only project-relevant requirements are included; personal history and unrelated conversations are excluded.

Existing record links were checked against the repository tree before this batch. That check does not validate the product behaviour described in those records.

## Prioritised coverage

| Priority | User need | Record | Remaining work |
|---|---|---|---|
| High | Resume the correct thread and last confirmed checkpoint | [SA-UX-001](../use-cases/SA-UX-001_Conversation_Identity_and_Continuity.md) | Attach original evidence and test recovery after interruption |
| High | Distinguish intended actions from actual execution | [SA-UX-004](../use-cases/SA-UX-004.md) | Verify capabilities before promises; retain returned action evidence |
| High | Warn about limits and preserve unfinished work | [SA-UX-007](../use-cases/SA-UX-007_Usage_Limits_and_Interruption_Recovery.md) | Test warnings where limit information is available; never invent reset times |
| High | Explain phone/computer voice differences and unavailable controls | [SA-UX-008](../use-cases/SA-UX-008_Cross_Device_Voice_and_Interaction_Consistency.md) | Reproduce reported behaviour; cause remains unknown |
| High | Show real progress and verified completion | [SA-UX-009](../use-cases/SA-UX-009_Progress_Transparency_and_Verified_Completion.md) | Test visible and voice feedback; distinguish running, interrupted, saved, checked |
| High | Exchange complete work between assistants without version confusion | [SA-UX-011](../use-cases/SA-UX-011_Cross_Assistant_Work_Exchange.md) | New detailed requirements; integration not implemented |
| Medium | Find conversations belonging to the selected project | [SA-UX-010](../use-cases/SA-UX-010_Project_Conversation_Discoverability.md) | Test project filter, recent chats, and return from search |
| Medium | Highlight the active thread and preview another without switching | [SA-UX-006](use-cases/SA-UX-006_Thread_Context_Preview_and_Active_Thread_Indicator.md) | Evaluate long-press plus keyboard/accessible alternatives |
| Medium | Keep one authoritative record across files and services | [SA-UX-002](../use-cases/SA-UX-002.md) | Reconcile competing versions with the repository decision |
| Medium | Focus read-aloud on the selected response | [SA-UX-005](../use-cases/SA-UX-005.md) | Test focused playback, stop control, and return to typing |
| Medium | Challenge proposals constructively | [SA-UX-012](../use-cases/SA-UX-012_Constructive_Challenge_and_Review.md) | New detailed requirements; review pilot pending |

Priorities are an assistant proposal based on continuity, lost-work risk, and user effort; they are not measured research findings.

## Status-system inconsistency requiring reconciliation
The [status specification](../project-management/Task_Status_and_Colour_System.md) gives blue both “finished” and “verified” meanings in different sections; its table also uses circle glyphs where it names a triangle or square. The [research overview](ChatGPT_UI_UX_Improvement_Research.md) preserves the four-state convention.

The explicit preference recorded in supplied context is:
- Blue circle: completed.
- Amber triangle: in progress.
- Red square: needs fixing.
- Green: checked and added.

Recommended correction: reconcile the central specification and SVG against that preference, define the green shape explicitly, and give unstarted work a clear text label instead of implying a defect. This batch flags the inconsistency; it does not silently change the central specification.

## What this batch contributes
- Two detailed use cases covering cross-assistant exchange and constructive review.
- This linked backlog mapping prior ideas to existing records.
- Discoverability links in the research and use-case indexes.

## Next bounded batch
1. Reconcile the central status definitions.
2. Expand existing short records SA-UX-001 through SA-UX-005 using the same structured fields.
3. Attach original evidence when available; do not invent journal quotations.
4. Pilot one continuity scenario and one critique scenario, preserving failures.
5. Reconcile the work log and overall project status after inspecting their current contents.

No product changes, external messages, Claude transfer, usability study, or complete repository content-and-link audit is claimed by this batch.
