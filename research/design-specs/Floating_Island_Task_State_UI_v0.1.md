# Sadhana design specification — Floating-island task-state interface

**Version:** 0.1 reconstructed working brief, 2026-11-02. **Status:** Draft; not implemented or tested.

## The underlying need
A person collaborating with AI should see whether work has started, what is happening, whether it is delayed, whether the result is saved, and what to do if it fails. Silence and arbitrary spinners make task state hard to understand.

## User-origin concept
The user described visually elevated, floating 'islands' or folder cards with subtle depth, gradient, shadows or halos; a meaningful percentage centrally displayed; consistent colour-and-shape status cues; and completion information available on desktop and phone. In a later lesson the user proposed an amber circular estimated countdown (example 30 seconds), an expanding oblong delay banner with an updated estimate, a clear completion transition with a check, and a red expanded explanation on failure. These are design ideas, not a deployed interface.

## Proposed interface state machine
1. **Ready:** task and authoritative project identity; primary action available.
2. **Submitted / queued:** acknowledgement; not yet shown as 'actively running'.
3. **Active:** amber triangle + 'Working'; name the operation and real progress units, if available.
4. **Delayed:** expand to a readable banner with truthful delay reason if known; avoid unsupported precise countdown resets.
5. **Finished:** blue circle + 'Finished'; present result or preview. 'Finished' does not necessarily mean checked.
6. **Checked and added:** green marker after a verified save/read-back or explicit review check, with type of check named.
7. **Failed / interrupted:** red square + known issue, last safe checkpoint and Retry / Review / Stop options.
8. **Waiting for human review:** labelled separately (amber), never silently treated as human-approved.

## Progress measurements
A percentage is valid only when the denominator is known: e.g., 3 of 5 defined files created and checked. A duration estimate is not progress; label it 'Estimated time' and disclose uncertainty. If the agent cannot run while the chat is inactive, show the current task as stopped or not running, not an animated fiction.

## Interactions and accessibility
- Short summary visible before the card expands; details on tap, keyboard or accessible action.
- Shape + text status should work without colour and with reduced motion.
- Keep focus and screen-reader updates polite and non-repetitive.
- No auto-removal of a failure until acknowledged. Completion feedback remains long enough to identify the result.
- Clicking a completion notice opens the actual saved artifact, not a generic chat.
- Dismissing the notification must not delete the work.
- Respect opt-in for mobile notifications and permission boundaries.

## Main scenarios to prototype
Normal 30-second analysis; unexpected long wait; network drop; file written but read-back failed; multiple parallel tasks with mixed states; handoff from PC to phone; returning when the underlying task stopped; final paper exported without workflow markers.

## Alternative to test
A simple inline text status plus task log may be more usable than an elaborate animated island. Compare comprehension, recovery time, perceived effort and accessibility. Visual polish alone is not evidence of better UX.

## Acceptance criteria
- Every status corresponds to authoritative task evidence, not merely animation.
- The displayed state can be correctly identified in a brief comprehension test.
- People can find and recover from a failed task.
- The system distinguishes finished / saved / verified / human approved.
- The user can work by voice, keyboard or touch.
- The design adds no status markers to clean final papers.

## Related work
[Status convention](../../project-management/Task_Status_and_Colour_System.md) · [SA-UX-020](../../use-cases/SA-UX-020_Progress_Indicator_With_Delay_and_Failure_Recovery.md) · [SA-UX-023](../../use-cases/SA-UX-023_Floating_Island_Task_Progress_Dashboard.md) · [SA-UX-026](../../use-cases/SA-UX-026_CrossDevice_Completion_Notification_and_Result_Preview.md).

**Provenance:** Retrospectively paraphrased from Sadhana discussions and lesson notes. Source code, working prototype, user-test results and original verbatim source have not been supplied.
