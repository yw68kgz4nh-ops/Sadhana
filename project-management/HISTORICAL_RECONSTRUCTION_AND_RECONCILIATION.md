# Historical Reconstruction and Repository Reconciliation

**Status:** 🟠 Amber — active work; this is a tracking document, not a claim that the historical audit is complete.  
**Repository:** Sadhana  
**Purpose:** Convert relevant project decisions, UX observations, AI-working principles, learning materials, and workflow evidence from prior conversations into durable, correctly located GitHub records.

## Rules for reconstruction

1. GitHub files are the durable project record; conversation memory is a retrieval aid, not proof that a deliverable exists.
2. Do not claim an item has been saved, moved, completed, or verified until the corresponding operation succeeds and the result is checked.
3. Preserve original evidence where available. Label reconstructed material as reconstructed and link the source conversation or journal entry when possible.
4. Distinguish reported observations, verified facts, hypotheses, proposals, decisions, and test results.
5. Avoid creating competing copies. Prefer one authoritative document and links from indexes.
6. Do not invent missing historical text or claim to have recovered an original prompt/document when only a summary is available.
7. Keep the public repository free of private or sensitive information.
8. Apply Sadhana's status convention: 🔴 Red = something wrong; 🟠 Amber = in progress; 🔵 Blue = finished; 🟢 Green = checked and added in.

## Repository areas identified in the current tree

- `PROJECT_MISSION_AND_FOUNDING_BRIEF.md` — mission and founding brief.
- `prompts/` — shared AI working philosophy and prompt library.
- `research/` — research records, including ChatGPT UI/UX improvement research.
- `use-cases/` — UX problem/use-case records.
- `project-management/` — status, workflow diary, work log, design principles, and traffic-light definitions.
- `schoolwork/` — learning programme and assessment workflow.
- `evidence/`, `experiments/`, `decisions/`, and `archive/` — supporting records, experiments, decisions, and retired material.

This is a snapshot of paths inspected during the current reconstruction, not a claim that every file in every folder has been audited in depth.

## Work completed in this reconstruction pass

- Created `research/ChatGPT_UI_UX_Improvement_Research.md` to define the dedicated UI/UX improvement research area.
- Created `research/use-cases/SA-UX-006_Thread_Context_Preview_and_Active_Thread_Indicator.md` from the user's proposal to highlight the active thread and preview other threads without switching.
- Updated `research/README.md` to link the UI/UX research area and SA-UX-006.
- Created `use-cases/SA-UX-007_Usage_Limits_and_Interruption_Recovery.md`.
- Created `use-cases/SA-UX-008_Cross_Device_Voice_and_Interaction_Consistency.md`.
- Created `use-cases/SA-UX-009_Progress_Transparency_and_Verified_Completion.md`.
- Created `use-cases/SA-UX-010_Project_Conversation_Discoverability.md`.
- Updated `use-cases/README.md` to index SA-UX-001 through SA-UX-010, while explicitly noting overlap and reconstruction status.
- Read the new use-case files and updated index back from GitHub to verify they were present.

## Historical topics to reconcile

The following topics are known from project conversations and should be matched to existing evidence before more records are created:

### ChatGPT / Claude product and interaction UX

- Active thread identification and non-navigating thread preview — SA-UX-006.
- Project-scoped chat list, folder/project distinction, and discoverability — SA-UX-001, SA-UX-002, SA-UX-010; review for overlap.
- Resource renaming and organisation capabilities — SA-UX-003.
- Capability verification and avoiding promises that cannot be executed — SA-UX-004; related Prompt 14.
- Read-aloud versus full-screen-reader behaviour — SA-UX-005.
- Usage limits, interruptions, and resumption — SA-UX-007; related Prompt 15.
- Phone/computer voice differences and continuity — SA-UX-008.
- Progress visibility and honest completion claims — SA-UX-009; related Prompts 14 and 15.
- Accessible, low-effort interaction; reduce unnecessary reading, typing, clicks, and repeated explanations.
- Context recovery after switching threads, reopening the app, or moving between devices.

### Shared AI working method and prompt library

- AI should question assumptions, challenge proposals respectfully, and suggest better options rather than merely comply.
- ChatGPT and Claude should help critique each other's proposals, with evidence and reasoning rather than agreement for its own sake.
- Keep one authoritative master working philosophy and make its current version explicit. Existing versions 0.2–0.5 need a version/status audit before any are removed or replaced.
- Prompt 13 (problem/limitation/solution capture), Prompt 14 (verified capability and honest execution), and Prompt 15 (interruption/resumption/no silent stall) are labelled drafts; compare them with original sources where available.
- The complete original prompt library has not been recovered in the available records; do not present reconstructed prompts as originals.

### Learning programme and portfolio

- University-informed UI/UX curriculum, AI integration, and robotics learning context.
- Week 1 materials, revision cards, and lesson papers; inspect `Week_1` versus `week-01` naming and determine a single canonical structure before moving files.
- Portfolio evidence should distinguish learning artefacts, research evidence, working notes, and finished deliverables.
- Explain terminology and documentation conventions accessibly and include practical work, critique, and evaluation.

### Workflow, project organisation, and evidence

- User wants relevant conversations and artefacts converted into durable files rather than left only in memory.
- Journal entries are working notes/evidence, not automatically final deliverables.
- Keep workflow diary, work log, research, decisions, evidence, experiments, and final papers distinct but cross-linked.
- Reconcile any prior critique noting version mismatch (e.g. a later working-philosophy version referenced while an index labels an earlier version current) and incomplete use-case acceptance criteria/failure cases/evaluation plans.

## Remaining work queue

1. Inspect and update `project-management/STATUS.md` so it accurately reflects the current repository state and reconstruction work.
2. Audit the root README and folder indexes for missing links and conflicting “current version” claims.
3. Compare all existing UX use cases with journal/work-log evidence; merge true duplicates carefully without deleting source evidence.
4. Audit master prompt versions and prompt-library status, preserving history and clearly identifying the authoritative version only after content comparison.
5. Inspect the full workflow diary and work log for uncaptured product-improvement ideas; create or update use cases only when supported by evidence.
6. Audit learning folders and naming variants; do not move or delete material until the canonical location and references are clear.
7. Create or update an evidence map linking each claim to a source, and mark unrecovered source material as missing rather than reconstructing it from guesswork.
8. Read back every changed file and update this tracker with verified outcomes.

## Completion standard

A topic is not considered reconciled merely because a summary exists. The work is complete only when its best available source is identified, its authoritative file location is chosen, relevant indexes link to it, duplicates and version conflicts are resolved or explicitly documented, and all changes are verified. Where the original source cannot be found, record the limitation and preserve the reconstructed draft as such.
