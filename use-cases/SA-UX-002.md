# SA-UX-002 — Project and Folder Organisation

Status: Draft reconstructed from project notes.

Intended outcome: Find related conversations, prompts, and research records without manual reconciliation.

Observed problem: The person reported difficulty finding related Sadhana conversations and resources. The assistant could not verify or change all aspects of the ChatGPT project interface with its available tools.

Impact: Extra navigation, uncertainty about the authoritative location, risk of duplicates, and reduced continuity.

Facts and uncertainty: The difficulty was reported. GitHub file access was later verified. The exact cause of the interface problem was not established.

Improvement: Maintain a clear repository index, one authoritative location per artefact, and explicit migration status. Do not imply GitHub folders automatically organise the ChatGPT project.

Test: Ask a user to locate the current master prompt, a use case, and a decision; measure time, wrong-file selection, and duplicate creation.

---

## Structured use-case expansion — 2026-11-02

**Provenance and status:** Retrospective reconstruction of Sadhana discussions; no independent usability test or root-cause confirmation. Original notes above are preserved.

### 1. Intended outcome and 2. Context / trigger
A user creates a new chat or file while already inside a project, then expects to find it under that project instead of an unlabelled recent list or another Library.

### 3. Evidence / uncertainty and 4. Problem impact
See the original observation and uncertainty above. This describes a reported interaction problem, not a proven defect affecting every user.

### 5. Preconditions
The current project is named and at least one file or conversation exists.

### 6. Main interaction flow
Show location breadcrumb (Project > chat/file), membership, last saved location and authoritative GitHub record where applicable; offer project-scoped search and migration preview.

### 7. Alternatives
A stable project index linking chats and GitHub documents, with explicit limitations of each product surface.

### 8. Acceptance criteria
- A new project chat appears in a discoverable project-scoped list or a clear failure message.
- Library, Project, and external repository origins are never conflated.
- No duplicate or moved resource is implied without proof.

### 9. Failure and recovery
If a Project cannot contain nested directories, explain and offer supported organisation, rather than creating folders in the Library as though they were Project folders.

### 10. Evaluation plan
Locate a current prompt and three use cases from phone and PC; record errors, duplicates, and navigation steps.

### 11. Dependencies and related records
SA-UX-010, SA-UX-016; DEC-001; EV-002.

### 12. Next action and completion boundary
Collect dated original screenshots/transcripts where accessible; run usability scenarios and log both observed and expected outcomes. The document is a usable **draft requirements record**, not a verified software improvement.
