# SA-UX-007 — Usage Limits and Interruption Recovery

- **Status:** 🟠 Amber — reconstructed from prior project discussions; evidence mapping and testing remain open.
- **Category:** Reliability / continuity / transparency
- **Related records:** SA-UX-001, SA-UX-004; Prompt 15 — Interruption, Resumption and No Silent Stall.

## Intended outcome

The user can anticipate and recover from usage limits, interruptions, and stalled workflows without losing their place or being left waiting without useful information.

## Observations reported

The user described reaching or approaching a usage limit on a computer, after which voice interaction appeared unavailable while the phone still worked. They also wanted earlier warnings before limits or interruptions, especially when a wait could be lengthy, and visible progress when work was continuing elsewhere. The exact product cause and account-specific limit behaviour have not been independently established.

## User impact

Uncertainty about whether work is still running, whether a control is broken, whether a task has stopped, and what the user should do next. Long periods without feedback can waste time and reduce confidence.

## Proposed improvement

- Warn clearly when a limit or interruption is approaching, where the system can reliably know this.
- State the affected capability, what will and will not continue, and any confirmed reset or recovery information.
- Save or expose a resumable task state where supported.
- Show meaningful progress during long-running work and identify the last completed step.
- If work has stopped, say so plainly; do not imply background execution without evidence.
- Provide a concise resume path and preserve the current project/thread identity.

## Acceptance criteria

1. Limit and interruption messages distinguish confirmed facts from estimates or unknowns.
2. Users can tell whether a task is running, paused, failed, or completed.
3. Where possible, users receive advance notice of a known limit; the design does not promise warnings when the system cannot predict one.
4. After interruption, the interface identifies the last verified step and remaining work.
5. Resuming does not silently duplicate completed actions or discard prior user decisions.
6. The system does not claim background work continued unless execution can be verified.

## Failure cases

- A warning appears too late or gives a misleading reset time.
- The UI says a task is running when it has stalled.
- Resumption repeats or skips a step.
- A limit on one device is incorrectly described as applying to all devices.
- The user is given generic advice instead of the actual state.

## Evaluation plan

Simulate a long task, a known limit, an unexpected interruption, and a resumed session. Measure successful recovery, duplicated or lost steps, time to understand the state, and user confidence. Record product, device, plan context where voluntarily available, and date; do not generalise from one account observation.

## Evidence to reconcile

Link the original phone/computer voice-limit discussion, workflow diary entries, and Prompt 15. The current record is a reconstruction and must not be treated as proof of the product's underlying cause.
