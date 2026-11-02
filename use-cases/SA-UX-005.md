# SA-UX-005 — Read-Aloud Interaction

Status: Draft from the current project conversation.

Goal: Listen to ChatGPT replies while using the ordinary text interface.

Observation: On a Windows PC in a web browser, the person enabled Windows Narrator. It began reading broadly across the interface, which the person found frustrating and did not want to continue using.

Impact: The attempted workaround produced excessive narration rather than a focused reading of ChatGPT replies.

Uncertainty: The exact cause has not been established. A focused Read Aloud control in ChatGPT has not yet been tested in this interface.

Improvement to evaluate: Use per-response read-aloud if available; distinguish that from a full screen reader. Compare setup effort, unwanted speech, and ability to return to typing.

---

## Structured use-case expansion — 2026-11-02

**Provenance and status:** Retrospective reconstruction of Sadhana discussions; no independent usability test or root-cause confirmation. Original notes above are preserved.

### 1. Intended outcome and 2. Context / trigger
A learner wishes to hear only the current answer or revision card, not every on-screen item.

### 3. Evidence / uncertainty and 4. Problem impact
See the original observation and uncertainty above. This describes a reported interaction problem, not a proven defect affecting every user.

### 5. Preconditions
A spoken-output capability is available or its absence is explicitly stated.

### 6. Main interaction flow
Offer per-answer Play/Stop/Resume and a way back to typing without switching projects; clearly identify whether this is response playback, dictation, or full screen reader.

### 7. Alternatives
Offer concise voice-friendly chunks and a copyable text alternative when targeted playback cannot be controlled.

### 8. Acceptance criteria
- Only the selected content is read when that mode is chosen.
- Stop is effective and text is still available.
- A mode unavailable on a given device is explained without suggesting the microphone is necessarily broken.

### 9. Failure and recovery
Voice limit, permissions, or device mismatch: disclose the known reason and a suitable recovery action; do not claim to have started audio.

### 10. Evaluation plan
Compare comprehension, unwanted narration, number of controls and task completion across reading modes.

### 11. Dependencies and related records
SA-UX-008, SA-UX-021; schoolwork/How_We_Will_Teach_and_Learn.md.

### 12. Next action and completion boundary
Collect dated original screenshots/transcripts where accessible; run usability scenarios and log both observed and expected outcomes. The document is a usable **draft requirements record**, not a verified software improvement.
