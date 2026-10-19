# SA-UX-001 — Conversation Identity and Continuity

- **Status:** Draft reconstructed from project notes; not yet validated against a complete evidence record.
- **Category:** Continuity / navigation / interaction design

## Intended outcome

The person can reliably identify the conversation and project they are working in and resume the correct thread without uncertainty or repeated context-setting.

## Observed problem

The person had difficulty identifying which conversation was open and whether they were in the same or a new chat. The assistant could not independently inspect the live interface state or reliably identify the user's current thread from its own tools.

## Impact

Uncertainty about location, difficulty resuming work, risk of entering the wrong conversation, and additional effort spent navigating and explaining context.

## Facts and uncertainty

- **Reported:** The person could see the Sadhana project but had difficulty finding the relevant conversations.
- **Limitation encountered:** The assistant did not have a verified tool to inspect or manipulate the live ChatGPT sidebar in that interaction.
- **Not established:** Whether the underlying cause was product behaviour, browser state, navigation, or a mismatch between the user's expectation and the interface.

## Desired improvement

Provide persistent conversation identity, clear project membership, recent activity, and a reliable resume path. Make the current project, thread, and artefact identity visible together.

## Test ideas

Measure whether users can resume a specific task after interruption without entering the wrong thread or reconstructing context. Record time to resume, navigation steps, wrong-thread incidents, and repeated explanations.

## Related records

- SA-UX-002 — Project and Folder Organisation
- SA-UX-003 — Renaming and Managing Project Resources
- SA-UX-004 — Plans Presented as Executable Without Capability Verification
