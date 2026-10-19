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
- These are design decisions discussed in the conversation; they have **not yet been implemented or committed as a design-system specification**.
- No floating-island UI, live percentage indicator, cross-device sync, or phone push notification has been built or verified in this session.
- The illustrative 60% example shown in conversation was explicitly not a measured progress value.

### Next steps
1. Create a shared design-system specification covering status semantics, progress calculation, island depth/halo, accessible labels, responsive behaviour, and notification rules.
2. Define task lifecycle transitions and the evidence required before a task may be marked complete.
3. Prototype the floating island and preview interaction.
4. Investigate feasible desktop/phone sync and notification architecture before promising delivery behaviour.
