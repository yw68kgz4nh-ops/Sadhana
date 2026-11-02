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


---

## Structured use-case expansion — 2026-11-02

**Provenance and status:** Retrospective reconstruction of Sadhana discussions; no independent usability test or root-cause confirmation. Original notes above are preserved.

### 1. Intended outcome and 2. Context / trigger
The user returns from a break, changes device, or accidentally enters an unrelated philosophy conversation while intending to continue Sadhana.

### 3. Evidence / uncertainty and 4. Problem impact
See the original observation and uncertainty above. This describes a reported interaction problem, not a proven defect affecting every user.

### 5. Preconditions
At least two project conversations exist and a reliable last-confirmed checkpoint has been saved.

### 6. Main interaction flow
Display project + thread title + last confirmed task; offer Open thread, Preview, Resume checkpoint, or Stay here; never silently route to another project.

### 7. Alternatives
Provide a manually searchable, project-filtered recent-chat list if automatic resume metadata is absent.

### 8. Acceptance criteria
- The active project and exact conversation are distinguishable in text and visually.
- Resume shows the saved timestamp and source, or honestly states that no reliable checkpoint exists.
- No switching occurs without the user's action.

### 9. Failure and recovery
Saved thread deleted, checkpoint stale, or project access revoked: communicate uncertainty and open a safe project list without inventing a checkpoint.

### 10. Evaluation plan
Ask participants to return after a simulated interruption and measure correct-thread resumption, accidental switches, time and repeated prompts.

### 11. Dependencies and related records
SA-UX-006, SA-UX-010, SA-UX-013; EV-002.

### 12. Next action and completion boundary
Collect dated original screenshots/transcripts where accessible; run usability scenarios and log both observed and expected outcomes. The document is a usable **draft requirements record**, not a verified software improvement.
