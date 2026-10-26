# Sadhana — Work Log

Use this log for concise, dated summaries of meaningful project work. It is not a substitute for detailed records; link to the relevant files.

## 2026-10-19 — Initial repository and research framing

### Completed and verified
- Established the initial repository structure and navigation indexes.
- Copied the Shared AI Working Philosophy v0.2 into `prompts/master/` and verified the saved content by reading it back.
- Saved reconstructed draft versions of Prompts 13 and 14, labelled so they are not confused with recovered originals.
- Created and indexed five draft user-experience records, SA-UX-001 through SA-UX-005.
- Added a project status file and verified repository files through read-back.
- Created the [Workflow Diary](WORKFLOW_DIARY.md), including a Day 1 recap and a reusable session-close template.
- Added Prompt 15 draft on interruption, resumption, and no-silent-stall behaviour.
- Created master prompt v0.3, preserving v0.2 and adding guidance for visible task state and honest resumption.
- Recorded a response delay as a workflow friction point in the diary: repository work began before the user received an acknowledgement.

### Research framing added
- Added exploratory question SA-RESEARCH-001: whether a structured human–AI working system can reduce user effort while improving continuity, reliability, and trust.
- Marked the question as exploratory. No claim of novelty or demonstrated effectiveness is made.
- Listed candidate measures and initial research tasks, including review of university-level UI/UX/HCI course outlines.

### Open work
- Recover and reconcile the original 13-prompt library wording.
- Strengthen UX records with evidence and test outcomes.
- Review repository visibility and avoid committing private or sensitive material.
- Research credible course outlines and assessment examples before preparing a proposed first-month learning plan.

### Reporting standard
Every entry should distinguish work that was discussed, drafted, attempted, completed, and verified. Only report verification where a check was actually performed.

## 2026-10-19 — UI/UX syllabus research draft

### Completed and verified
- Reviewed public university module descriptions for UX/interaction design and HCI from the Universities of Leeds, Edinburgh, Bath, Kent, and Cardiff.
- Created [UI/UX First-Month Syllabus — Research Draft](../research/UI_UX_First_Month_Syllabus_Research_Draft.md), with four weeks of learning, practical deliverables, a beginner feedback rubric, source links, and explicit limitations.
- Indexed the syllabus draft in the research README.
- Read back the new syllabus and checked the updated status/index content.

### Important qualification
- This is a proposed beginner programme informed by university module outlines, not an official university syllabus or accredited course.
- The earlier planned research was not completed before the user returned and asked about it. The syllabus draft was produced during this live session; no claim is made that it was completed while the user was away.

## 2026-10-19 — Carnegie Mellon focus and dedicated schoolwork folder

### Completed and verified
- Created the dedicated schoolwork folder with a README, a 20-session Month 1 course plan, and a teaching-and-learning guide.
- Based the plan on Carnegie Mellon HCII's public descriptions of Design of AI Products and Services and Human AI Interaction.
- Researched Carnegie Mellon's Eberly Center guidance on prior knowledge, active learning, concept checks, low-stakes assessment, feedback, and responsive teaching, plus systematic reviews of retrieval practice and feedback.
- Archived the earlier multi-university syllabus under schoolwork/archive and removed it from the active research folder/index, so the Carnegie Mellon-focused plan is the active direction.
- Updated the project status and research index.

### Qualification
- The plan is an original beginner-friendly synthesis, not an official Carnegie Mellon course or a claim that CMU is definitively the world's best university.
- The prior draft was archived rather than erased from history; unrelated Sadhana work was left untouched.
- The new files and updated records still require a final read-back check.

## 2026-10-19 — Unified floating-island UI and visible task-state design

### Discussed and decided
- Establish a consistent three-state system across Sadhana features and platforms: blue = complete and verified; yellow = in progress; red = incomplete, blocked, failed, or interrupted.
- Floating islands should feel physically elevated through carefully designed gradients, layered shadows, depth, and restrained halos—not look like flat cards with a glow.
- Show a progress percentage centrally in the island, but calculate it from meaningful, observable work units rather than inventing precision. A status colour must also have a text label and icon for accessibility.
- Design the same status semantics and visual language across desktop and phone, while adapting layout to each platform.
- When a task is unfinished, report exactly what is complete, what remains, the next action, and whether continuation is genuinely automatic or requires user action.
- On verified completion, show a temporary desktop preview and send a phone notification where the implemented platform and permissions support it. Dismissing the notification must not delete the saved work; missed notifications must not lose the completion record.
- Treat these as shared design-system requirements rather than one-off styling choices.

### Status and qualification
- These were originally design decisions discussed in conversation. The shared task-status semantics are now documented in [Task Status and Colour System](Task_Status_and_Colour_System.md); software UI, automatic status calculation, sync, and notifications remain unimplemented.
- No floating-island UI, live percentage indicator, cross-device sync, or phone push notification has been built or verified in this session.
- The illustrative 60% example shown in conversation was explicitly not a measured progress value.

### Next steps
1. Use the status markers on real project tasks and review whether they help.
2. Define task lifecycle transitions and the evidence required before a task may be marked complete.
3. Prototype the floating island and preview interaction.
4. Investigate feasible desktop/phone sync and notification architecture before promising delivery behaviour.

## 2026-10-19 — Feedback reliability and assessed-learning workflow

### Added
- Drafted master prompt v0.4 to require clear acknowledgement, proportionate progress feedback, explicit completion/unfinished/blocked/failure status, and honest separation of completion from verification.
- Created `schoolwork/Assessment_and_Improvement_Workflow.md` defining practical coursework, rubric-based marking, specific critique, revision, and review of our own teaching and AI workflow.
- Linked the assessment workflow from the teaching guide and schoolwork README, and identified v0.4 in the prompt index.

### Status
- The relevant writes were made; see the corresponding current records for the latest verification state.
- The university comparison for short practical assignments and rubrics, and the first Week 1 assessment pilot, remain open.

## 2026-10-19 — Shared task status and colour system: document prototype

### User-led decision
- Apply the status colour system to the project documents now rather than waiting for the software implementation.
- Use GitHub documents as a low-cost first prototype: make finished, unfinished, blocked, and unverified work visible, then evaluate whether the system helps in actual use.
- Keep status meanings consistent with the future floating-island/task-state design.

### Completed
- Created [Task Status and Colour System](Task_Status_and_Colour_System.md), specifying the blue/yellow/red meanings, text labels, task states, evidence required for verification, unfinished-task reporting, progress-percentage rules, and a pilot checklist.
- Updated the project status to show current open work with explicit status markers.
- Added navigation to the status specification.

### Verification
- 🔵 **COMPLETE — VERIFIED** — Read back the new specification and updated status, work log, and project-management index from GitHub. Checked for the colour definitions, pilot checklist, current task markers, and navigation links.

### Still open
- Review the saved files by reading them back.
- Use the system on several real tasks, then record any confusion, missed updates, or improvement opportunities.
- The document prototype does not itself implement coloured UI backgrounds, automatic tracking, cross-device sync, or notifications.


## 2026-10-20 — Master prompt v0.5: journal meaningful changes

### Added
- Created [Shared AI Working Philosophy v0.5](../prompts/master/Shared_AI_Working_Philosophy_v0.5.md) with a mandatory rule to journal meaningful design decisions, modifications, fixes, solutions, actions, verification, failures, and open work.
- Updated the [prompt index](../prompts/README.md) to identify v0.5 as current while preserving prior versions.
- Added a diary entry explaining the decision and steps, and noted that a retrospective audit of older work is still needed.

### Verification status
- The write operations succeeded. Read-back verification of the new prompt, prompt index, diary entry, and this work-log entry is the next check; do not treat these records as fully verified until that check passes.

### Open work
- Audit earlier meaningful design changes and add clearly labelled retrospective diary notes where the record is missing or incomplete.


## 2026-10-20 — Task-status mini UI

- Created `project-management/assets/task-status-mini-ui.svg` and embedded it in `Task_Status_and_Colour_System.md`.
- Added a provisional rationale for the circle, triangle, and square. These are design metaphors to test, not universal psychological rules; explicit labels and verification remain authoritative.
- Recorded the work in `WORKFLOW_DIARY.md`.
- Open: read back all changed files and confirm the SVG path renders correctly, then test the visual during a real paper critique.


## 2026-10-26 — Historical repository population and status-system correction

### Added or updated
- Added four reconstructed Week 1 learning assets: Lesson 4 on deciding whether AI is appropriate, Lesson 5 review/design brief, an assignment brief and rubric, and a reusable lesson worksheet template.
- Added an initial evidence register, DEC-001 on the authoritative project record, and EXP-001 usability-test plan for active-thread indicators and previews. EXP-001 is a plan only; it has not been run.
- Updated the project status snapshot and indexes for decisions, evidence, and experiments.
- Re-read the repository tree and several key indexes. Confirmed that the repository has both `schoolwork/Week_1/` and `schoolwork/week-01/`; consolidation remains open because files must not be lost.
- Corrected the heading and core definition paragraph in `project-management/Task_Status_and_Colour_System.md` to restore the original three shape-and-colour meanings: blue circle = complete; amber triangle = ongoing; red square = needs fixing. Green “checked and added in” is an additional review distinction, not a replacement for the three core meanings.

### Limitations and open work
- Much historical context is available only as summaries, not complete original transcripts or original prompt text. Reconstructed records remain labelled as such.
- Newly created learning files and all indexes still need a systematic read-back/link audit. The whole repository has not yet been verified for empty folders, broken links, duplicate content, or inconsistent status symbols.
- The repository is public; review privacy and visibility before adding any further personal or confidential material.
- Do not report background work as continuing while the session is idle. Work is recorded here only after the corresponding repository operations.

## 2026-10-26 — Journalled thread-preview proposal and compared Week 1 Lesson 2 variants

### Completed and verified
- Added a clearly labelled retrospective session entry to the [Workflow Diary](WORKFLOW_DIARY.md), capturing the user's press-and-hold thread-preview proposal, why it matters, the stopping point, linked records, and next actions.
- Read the saved diary entry back from GitHub and verified that the thread-preview proposal and retrospective label are present.
- Compared both Lesson 2 files in full: `schoolwork/Week_1/Lesson_02_Problem_Framing.md` and `schoolwork/week-01/Lesson_02_Define_the_Problem_before_the_Solution.md`.

### Lesson 2 comparison findings
- The `Week_1` version has a more explicit evidence-versus-hypothesis exercise, a structured problem frame, a practical task, exit questions, and tutor notes.
- The `week-01` version includes a different worked example, a guided practice checklist, completion evidence, and a source/scope note referencing Carnegie Mellon HCII.
- The two files overlap but are not exact duplicates. No lesson file was deleted or overwritten during this comparison.
- Next decision: consolidate the useful unique teaching content into one canonical Week 1 Lesson 2, preserve provenance and any unique source note, then replace the legacy duplicate with a clear pointer only after the merged canonical file and all inbound links have been checked.

### Still open
- The diary/work log audit is not complete; earlier ideas still need to be extracted in manageable groups.
- The repository-wide relative-link audit and master-prompt version comparison remain outstanding.
- The repository remains public until the owner changes visibility in GitHub settings.


## 2026-10-26 — File-by-file repository inventory and triage

### Completed and verified
- Retrieved the recursive GitHub tree for the default branch and counted **56 files across 16 directories**.
- Created [File-by-File Repository Audit](FILE_BY_FILE_AUDIT_2026-10-26.md), listing every current file with a status and known follow-up where available.
- Read back the new audit and reviewed key indexes, status, diary, work log, and prompt-library migration notes.
- Linked the audit from the project-management index.

### Important limitations and findings
- The 56-file count is the current repository inventory, not a count of files changed today; multiple commits modify the same paths.
- This is an inventory and triage pass, not yet a full line-by-line content and link audit of all 56 files.
- Known next fixes include inconsistent status-key representations, two overlapping Lesson 2 files, the legacy Week 1 folder name, incomplete prompt recovery, and deeper evidence/acceptance-criteria review for earlier use cases.
- The repository remains public; no sensitive material should be added.

### Next step
- Correct status-key inconsistencies and consolidate Lesson 2 safely, then continue the repository-wide relative-link and prompt-version audit.
