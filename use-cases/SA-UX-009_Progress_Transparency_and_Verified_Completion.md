# SA-UX-009 — Progress Transparency and Verified Completion

- **Status:** 🟠 Amber — reconstructed from prior project discussions; test plan requires refinement.
- **Category:** Feedback / trust / task execution
- **Related records:** SA-UX-004, SA-UX-007; Prompt 14 — Verified Capability and Honest Execution; Prompt 15 — Interruption, Resumption and No Silent Stall.

## Intended outcome

The user can tell what the assistant is doing, what has actually happened, what remains, and which results have been verified.

## Observed problem

The user asked for visible progress when work is underway, particularly when a task may take time or be continuing from another device. They also repeatedly stressed that an assistant must not say files or folders have been saved or organised unless the action was actually performed and checked.

## Impact

Uncertainty, repeated checking, wasted waiting time, and the risk of treating a plan or conversational promise as a completed deliverable.

## Proposed improvement

Use clear, truthful task states and concise progress updates at meaningful transitions. Distinguish:
- **Discussed** — considered, not executed.
- **Planned** — next action identified.
- **Running** — execution has started and is known to be active.
- **Blocked / failed** — execution cannot continue or did not succeed.
- **Completed** — the action returned a successful result.
- **Verified** — the output was inspected or read back and matched the intended result.

Show the last verified step and next unresolved step for multi-stage work. Avoid repetitive filler updates and do not manufacture progress.

## Acceptance criteria

1. Every completion claim corresponds to an actual action result.
2. Verification is labelled separately from execution.
3. Long tasks provide meaningful updates when a stage changes, a blocker appears, or user input is required.
4. If execution status is unknown, the UI says so rather than implying work is continuing.
5. Users can see what remains and resume without reconstructing the plan from the full conversation.
6. Updates are concise, accessible, and do not overwhelm users with tool-level detail.

## Failure cases

- The assistant announces success before the tool confirms it.
- A progress indicator runs indefinitely without meaningful state.
- The UI reports “complete” even though a later verification step failed.
- Frequent updates add noise without useful information.
- A plan is mistaken for an executed action.

## Evaluation plan

Give participants multi-step tasks involving file creation, editing, and read-back verification, including one failed action. Measure accuracy of users' understanding of task state, false completion beliefs, recovery time, and unnecessary follow-up questions.

## Evidence to reconcile

Link prior discussions about silent waits, visible progress, GitHub saving, and distinguishing memory from completed work. Prompt 14 and Prompt 15 are related guidance, not substitutes for this use case.
