# Sadhana — Visibility of system status: design-exercise record

**Date of discussion:** 2026-11-01. **Reconstructed:** 2026-11-02. **Status:** Learner's concept captured; not yet formally assessed or implemented.

## Foundational UX principle
**Visibility of system status** means a system keeps people informed about what is happening, in sufficient time and with accurate feedback. A loading animation alone is not evidence of real progress.

## Exercise brief
Sketch feedback for a chat document analysis taking approximately 30 seconds. Show three outcomes: normal running and success; an unexpected delay; and failure.

## Learner's proposed solution (paraphrased, not verbatim)
- An amber circular indicator with a number counting down from 30, signalling that analysis is underway.
- On completion, the indicator glows blue, shows a green tick, the interface refreshes, and the marker then disappears.
- If taking longer, the marker expands into an oblong message 'Taking longer than expected', then returns to a compact state with a revised estimate, such as 60 seconds.
- If a failure occurs, the marker turns red, expands into a message that explains the known failure and suggests a retry.

## Strengths of the proposed interaction
It communicates acknowledgement, active work, delay, success and failure as distinguishable states; uses a small footprint that expands only when important; offers a recovery action.

## Critique and unresolved design decisions
1. **Estimation credibility:** A precise countdown without an actual estimate source misleads users. A qualitative status is better when duration is unknown.
2. **Meaning of colours and shapes:** Sadhana's project workflow convention uses blue circle=finished, amber triangle=in progress, red square=needs fixing, and green=checked and added. A different compact animation may still be evaluated, but the reason for departing from the convention should be explicit, not accidental.
3. **Completion versus verification:** A file analysis finishing is not the same as its answer being checked or saved.
4. **Accessibility:** Important text should be available to screen readers and usable without movement, sound or colour.
5. **Recovery:** An error banner must preserve the request or safe checkpoint; Retry should not cause duplicate external actions.
6. **No phantom background work:** An idle or sleeping phone is not proof that the assistant continues executing.

## Follow-up questions for the learner
- What would the indicator show if the system cannot measure remaining time?
- How would someone know whether a result is saved versus merely generated?
- Would a simpler text progress label work better for frequent tasks?
- Should a failed-state message persist until acknowledged?
- How would you test whether other people interpret the colours and shapes correctly?

## Assessment state
The learner produced a substantive design concept. A formal graded critique, user test, independently verified prototype and final approval have not occurred. This exercise does **not** mark Week 1 complete.

## Related material
[2026-11-01 lesson session](Session_2026-11-01_Human_AI_Interaction.md) · [Five key terms card](Core_Five_Terms_Revision_Card.md) · [Design specification](../../research/design-specs/Floating_Island_Task_State_UI_v0.1.md).
