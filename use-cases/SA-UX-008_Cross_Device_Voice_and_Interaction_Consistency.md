# SA-UX-008 — Cross-Device Voice and Interaction Consistency

- **Status:** 🟠 Amber — reconstructed from prior project discussions; needs further evidence and tests.
- **Category:** Accessibility / cross-device UX / continuity
- **Related records:** SA-UX-001, SA-UX-005, SA-UX-007.

## Intended outcome

Users can move between phone and computer and understand which voice, dictation, and interaction capabilities are available, without having to troubleshoot unexplained differences.

## Observations reported

The user reported that voice interaction worked on the phone while a microphone control appeared greyed out on the computer, and that creating a new computer chat seemed to restore microphone availability. The user also reported that voice settings or voices did not appear to stay consistent between phone and computer. These are reported observations; the cause and expected account/device behaviour remain unverified.

## Impact

Interrupted work, repeated troubleshooting, uncertainty about whether a control is broken or a feature differs by device, and additional cognitive effort.

## Proposed improvement

- Make device-specific capability and current interaction mode clear.
- Explain why a control is unavailable when that information is known.
- Preserve or clearly communicate relevant settings across devices where the product supports synchronisation.
- Offer a simple recovery path when a control appears unavailable.
- Distinguish product limitations, permissions, browser/device problems, usage limits, and unknown causes rather than guessing.

## Acceptance criteria

1. Users can identify whether voice, dictation, and read-aloud are available on the current device.
2. Disabled controls have an understandable explanation or next step where feasible.
3. The UI does not imply settings are synchronised if they are device-specific.
4. A user can continue or resume a task on another device without losing project/thread identity.
5. Troubleshooting guidance is specific to the observed state and avoids unnecessary repeated steps.

## Failure cases

- A generic error message hides the reason a control is disabled.
- The assistant confidently attributes a problem to a usage limit without evidence.
- Settings appear to sync but do not, or local settings unexpectedly overwrite one another.
- Recovery steps discard the current thread or unsaved input.

## Evaluation plan

Test matched tasks on phone and computer across normal, unavailable-control, and resume scenarios. Record feature availability, number of troubleshooting actions, task continuity, and users' understanding of which settings are shared versus local.

## Evidence to reconcile

Link the original phone/computer and voice-setting conversations, plus any reproducible screenshots or steps. Keep the reported symptom separate from any confirmed technical diagnosis.
