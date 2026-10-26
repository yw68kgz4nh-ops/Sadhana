# Sadhana — File-by-File Repository Audit

**Audit date:** 2026-10-26  
**Scope:** Snapshot of the default branch `main`, checked against GitHub's recursive repository tree and selected file read-backs.  
**Overall status:** 🟠 **IN PROGRESS — inventory complete; full content/link audit not complete.**

## Snapshot totals

- **56 files** currently present in the repository.
- **16 directories** currently present (including nested directories).
- This is a count of files in the current snapshot, not a count of files changed today.
- The recent commit history contains multiple commits that update the same files; commits must not be counted as unique files.
- A file listed as present has not necessarily been audited line-by-line. The audit below separates recent work, known issues, and files whose detailed review remains outstanding.

## Audit legend

- 🟢 **CHECKED AND ADDED IN** — a recent creation/update was read back or the relevant presence/content was directly checked.
- 🔵 **COMPLETE / VERIFIED** — a defined task was completed and checked; this does not mean the underlying product idea has been validated.
- 🟠 **IN PROGRESS** — present, but further reconciliation, evidence, or content review is needed.
- 🟥 **NEEDS FIXING** — a known inconsistency or specific unresolved defect needs attention.

## File-by-file inventory

### Repository root

| File | Audit result |
|---|---|
| `README.md` | 🟠 Existing project index; read during this audit. States repository is public and historical material is not fully migrated. Full link-by-link audit still pending. |
| `PROJECT_MISSION_AND_FOUNDING_BRIEF.md` | 🟠 Present; founding brief explicitly remains a first draft awaiting review. |
| `Sadhana_Name_and_Meaning.md` | 🟠 Present; detailed content and links not audited in this pass. |

### `archive/`

| File | Audit result |
|---|---|
| `archive/README.md` | 🟠 Present; detailed content/link review pending. |

### `decisions/`

| File | Audit result |
|---|---|
| `decisions/DEC-001_Repository_as_Authoritative_Project_Record.md` | 🟢 Created and read back in the current reconstruction pass. |
| `decisions/README.md` | 🟢 Index populated/updated and checked in the current pass. |

### `evidence/`

| File | Audit result |
|---|---|
| `evidence/EVIDENCE_REGISTER.md` | 🟢 Created and read back; evidence register is an initial structure, not proof that all claims have source evidence. |
| `evidence/README.md` | 🟢 Index populated/updated and checked in the current pass. |

### `experiments/`

| File | Audit result |
|---|---|
| `experiments/EXP-001_Thread_Preview_Usability_Test.md` | 🟢 Created and read back; test plan exists, but the experiment has not been run. |
| `experiments/README.md` | 🟢 Index populated/updated and checked in the current pass. |

### `project-management/`

| File | Audit result |
|---|---|
| `project-management/Design_Principles.md` | 🟠 Present; detailed content and link audit pending. |
| `project-management/HISTORICAL_RECONSTRUCTION_AND_RECONCILIATION.md` | 🟢 Updated and read back; explicitly tracks incomplete historical recovery. |
| `project-management/README.md` | 🟢 Index updated to link the historical reconciliation tracker; read-back verified in prior work. |
| `project-management/STATUS.md` | 🟢 Updated and read back. 🟥 Its status-key formatting still needs alignment with the agreed red-square convention. |
| `project-management/Task_Status_and_Colour_System.md` | 🟢 Corrected and read back: 🔵 blue circle = finished/complete; 🟠 amber triangle = running/in progress; 🟥 red square = something wrong; 🟢 green = checked and added in. |
| `project-management/WORKFLOW_DIARY.md` | 🟢 Updated and read back. Includes the 2026-10-26 retrospective entry about thread preview; it is labelled retrospective, not presented as a contemporaneous record. |
| `project-management/WORK_LOG.md` | 🟢 Updated and read back with the latest repository work and Lesson 2 comparison. |
| `project-management/assets/task-status-mini-ui.svg` | 🟠 Present; asset itself and its consistency with the latest status key need a focused visual/content check. |

### `prompts/`

| File | Audit result |
|---|---|
| `prompts/README.md` | 🟢 Read during this audit. Identifies v0.5 as current and preserves older versions; migration is not complete. |
| `prompts/library/README.md` | 🟢 Read during this audit. Clearly states the full original 13-prompt source has not been recovered and Prompts 13–15 are reconstructed/new drafts. |
| `prompts/library/Prompt_13_Problem_Limitation_and_Solution_Capture_draft.md` | 🟠 Present; reconstructed draft, not verified as original wording. |
| `prompts/library/Prompt_14_Verified_Capability_and_Honest_Execution_draft.md` | 🟠 Present; reconstructed draft, not verified as original wording. |
| `prompts/library/Prompt_15_Interruption_Resumption_and_No_Silent_Stall_draft.md` | 🟠 Present; draft exists; detailed comparison with conversation history remains open. |
| `prompts/master/Shared_AI_Working_Philosophy_v0.2.md` | 🟠 Preserved historical version; comparison/reconciliation audit pending. |
| `prompts/master/Shared_AI_Working_Philosophy_v0.3.md` | 🟠 Preserved historical version; comparison/reconciliation audit pending. |
| `prompts/master/Shared_AI_Working_Philosophy_v0.4.md` | 🟠 Preserved historical version; comparison/reconciliation audit pending. |
| `prompts/master/Shared_AI_Working_Philosophy_v0.5.md` | 🟠 Identified as current by the prompt index; full requirements/consistency audit remains open. |

### `research/`

| File | Audit result |
|---|---|
| `research/ChatGPT_UI_UX_Improvement_Research.md` | 🟢 Created and read back; initial research framing exists, evidence and validation work remain. |
| `research/README.md` | 🟢 Updated to index the research area and thread-preview use case; read-back verified. |
| `research/SA-RESEARCH-001_Human_AI_Working_Partnership.md` | 🟠 Present; detailed evidence and source review pending. |
| `research/use-cases/SA-UX-006_Thread_Context_Preview_and_Active_Thread_Indicator.md` | 🟢 Created and read back. Captures the user's press/hold-to-preview idea; proposal is not yet tested. |

### `schoolwork/`

| File | Audit result |
|---|---|
| `schoolwork/Assessment_and_Improvement_Workflow.md` | 🟠 Present; detailed review pending. |
| `schoolwork/How_We_Will_Teach_and_Learn.md` | 🟠 Present; detailed review pending. |
| `schoolwork/Month_1_Human_Centred_Design_for_AI_Products.md` | 🟠 Present; detailed review pending. |
| `schoolwork/README.md` | 🟢 Read during this audit; establishes schoolwork as the intended single home for learning materials. |
| `schoolwork/Week_1/README.md` | 🟠 Read during this audit. Lesson 1 still points to the legacy-named folder, and the local status key contains a duplicate blue meaning and inconsistent red marker; fix these. |
| `schoolwork/Week_1/Lesson_02_Problem_Framing.md` | 🟠 Read and compared with the legacy Lesson 2; contains useful distinct material. Consolidation into one authoritative Lesson 2 remains open. |
| `schoolwork/Week_1/Lesson_03_AI_Capabilities_and_Limits.md` | 🟢 Presence and read-back were checked in the current reconstruction; full academic/content review remains open. |
| `schoolwork/Week_1/Lesson_04_When_AI_Is_Appropriate.md` | 🟢 Created and read back in the current reconstruction. |
| `schoolwork/Week_1/Lesson_05_Review_and_Design_Brief.md` | 🟢 Created and read back in the current reconstruction. |
| `schoolwork/Week_1/Lesson_Worksheet_Template.md` | 🟢 Created and read back in the current reconstruction. |
| `schoolwork/Week_1/Week_1_Assignment_Brief_and_Rubric.md` | 🟢 Created and read back in the current reconstruction. |
| `schoolwork/Week_1/Week_1_Revision_Cards.md` | 🟢 Presence and read-back were checked in the current reconstruction. |
| `schoolwork/archive/Previous_Multi_University_Syllabus_Superseded.md` | 🟠 Preserved as superseded material; not part of the active course direction. |
| `schoolwork/week-01/Lesson_01_UX_UI_and_Human_AI_Interaction.md` | 🟠 Present and linked from the Week 1 index, but remains in a differently named folder pending safe consolidation. |
| `schoolwork/week-01/Lesson_02_Define_the_Problem_before_the_Solution.md` | 🟥 Duplicate/overlapping Lesson 2 path with distinct content. Preserve until the canonical Lesson 2 is merged and all links are checked; do not delete prematurely. |

### `use-cases/`

| File | Audit result |
|---|---|
| `use-cases/README.md` | 🟢 Updated and read back; indexes SA-UX-001 through SA-UX-010 and notes that some records overlap and remain reconstructed. |
| `use-cases/SA-UX-001_Conversation_Identity_and_Continuity.md` | 🟠 Present; historical evidence, acceptance criteria, and test details need review. |
| `use-cases/SA-UX-002.md` | 🟠 Present; historical evidence, acceptance criteria, and test details need review. |
| `use-cases/SA-UX-003.md` | 🟠 Present; historical evidence, acceptance criteria, and test details need review. |
| `use-cases/SA-UX-004.md` | 🟠 Present; historical evidence, acceptance criteria, and test details need review. |
| `use-cases/SA-UX-005.md` | 🟠 Present; historical evidence, acceptance criteria, and test details need review. |
| `use-cases/SA-UX-007_Usage_Limits_and_Interruption_Recovery.md` | 🟢 Created and read back; evidence and testing still needed. |
| `use-cases/SA-UX-008_Cross_Device_Voice_and_Interaction_Consistency.md` | 🟢 Created and read back; evidence and testing still needed. |
| `use-cases/SA-UX-009_Progress_Transparency_and_Verified_Completion.md` | 🟢 Created and read back; evidence and testing still needed. |
| `use-cases/SA-UX-010_Project_Conversation_Discoverability.md` | 🟢 Created and read back; evidence and testing still needed. |

## What this audit establishes

1. The current default branch contains **56 files across 16 directories**.
2. Recent reconstruction work created or updated multiple research, use-case, evidence, experiment, decision, schoolwork, index, and project-management records. The file-specific results above identify which ones were directly checked in this pass or prior recorded read-back checks.
3. Five major project-management records were updated in the latest work sequence: the workflow diary, work log, status file, historical reconstruction tracker, and status-system specification. Several indexes and new records were also created or updated.
4. **This is not yet a complete deep audit of all 56 files.** Older records marked amber have not all been read line-by-line; the audit does not claim every link is valid or every historical idea has been recovered.
5. The GitHub history contains repeated edits to the same paths, so the number of commits is not the number of unique files changed.

## Priority actions

1. 🟥 Fix the inconsistent status-key representations in `STATUS.md` and `schoolwork/Week_1/README.md`; use written labels plus the agreed shape and colour.
2. 🟠 Merge the two Lesson 2 versions into one authoritative paper, preserve unique content and source notes, then redirect/archive the legacy path only after checking links.
3. 🟠 Audit all README/index links against the current file tree.
4. 🟠 Compare master prompt versions 0.2–0.5 and task-specific drafts; preserve version history and do not invent missing original wording.
5. 🟠 Review SA-UX-001–005 and complete missing acceptance criteria, failure cases, evidence, and evaluation plans.
6. 🟠 Continue mapping earlier ChatGPT/Claude improvement ideas to existing records before creating duplicates.
7. 🟥 Reassess repository privacy. It is currently public; do not add sensitive information.
8. 🟠 After each meaningful work session, update the workflow diary and work log, and read back the changes.

## Verification note

This document was created from the recursive GitHub tree for the default branch and selected GitHub file read-backs on 2026-10-26. It is an inventory and triage report. It should be updated as the deeper content and link audit progresses.
