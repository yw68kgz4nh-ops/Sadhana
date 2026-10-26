# Sadhana — Workflow Diary

## Purpose

A practical diary of how we work together, not just a list of outputs. Close a meaningful work session or project phase with a recap so we can look back and understand what we achieved using the Sadhana workflow, what got in the way, and what should happen next.

Keep entries factual, kind, and useful. Distinguish:
- **Discussed** — ideas or plans considered.
- **Attempted** — an action was tried.
- **Completed** — the action was carried out.
- **Verified** — the result was checked directly.
- **Blocked / unresolved** — something remains uncertain or could not be completed.

Do not treat a plan as completed work. Do not guess at time saved, productivity, or success; record evidence if we later measure it. Keep confidential and sensitive information out because the repository is public.

## Session-close template

Copy this template for each meaningful session or project milestone.

### YYYY-MM-DD — Day / session label

**Aim**
- What we set out to do.

**What we discussed or decided**
- Decisions, working methods, and open questions.

**What we actually did**
- Completed actions and useful outputs, with links where possible.

**What was verified**
- Checks that were actually performed and their results.

**Hurdles and friction**
- Problems, failed attempts, confusion, interruptions, or extra effort. Mark causes as unknown when not established.

**What remains open**
- Work not finished, questions to investigate, and dependencies.

**Next steps**
- The most useful next actions, in priority order.

**Workflow reflection**
- What helped, what did not, and one adjustment to try next time.
- If we later measure effort or outcomes, record the method and evidence rather than estimating from memory.

---

## 2026-10-19 — Day 1: Establishing the Sadhana working system

**Aim**
- Begin shaping a repeatable human–AI working system for learning, design, problem-solving, and keeping reliable project records.

**What we discussed or decided**
- Treat the work as a continuing project rather than a collection of disconnected chats.
- Keep records of design questions, problems encountered, attempted fixes, decisions, and learning.
- Separate proposed work from work actually done, and verify saved outputs where possible.
- Add a workflow diary so that at the end of a meaningful session or project phase we can review progress, plans, hurdles, and what really happened.
- Later prepare a beginner-friendly university-informed UI/UX learning plan, including the first month's topics and practical assignments. This is a planned task, not yet a completed syllabus.

**What we actually did**
- Set up the repository structure and navigation files for Sadhana.
- Saved the Shared AI Working Philosophy v0.2 and labelled reconstructed Prompt 13 and Prompt 14 as drafts.
- Created five draft UX/use-case records, SA-UX-001 through SA-UX-005.
- Added project status, a work log, and an exploratory human–AI working-partnership research record.
- Created this workflow diary and its session-close template.

**What was verified**
- Earlier repository files were read back after saving, including the project status, work log, research record, and prompt/use-case records.
- The project-management README and work log were fetched before this diary was added. The new diary and index updates still need read-back verification after saving.

**Hurdles and friction**
- Conversation continuity and organising work across chats/projects have been recurring concerns.
- Some interface/navigation actions did not behave as expected in the earlier troubleshooting; the precise cause is not established.
- The original complete 13-prompt library has not yet been recovered. Prompt 13 and 14 entries are reconstructed drafts, not confirmed originals.
- The repository is public, so it is not suitable for confidential or sensitive records.

**What remains open**
- Save and verify the diary and link it from the project-management index.
- Continue recovering and reconciling the original prompt library.
- Review and strengthen the UX records with evidence and test results.
- Research credible university UI/UX/HCI course outlines and assessment examples, then create a clearly labelled proposed first-month learning plan.

**Next steps**
1. Finish saving and verifying this diary and its index links.
2. Continue the outstanding project records without claiming unverified work as complete.
3. Research university course examples and draft the first-month learning plan.

**Workflow reflection**
- Helpful: a central repository, dated records, explicit status labels, and read-back verification.
- To improve: close each meaningful session with a short diary entry, and make the next action clear enough that work can resume without the user having to reconstruct the whole conversation.
- Baseline note: this is Day 1 of documenting the workflow. We have not yet measured time saved or compared outcomes against a baseline, so no productivity claim is made.


---

## 2026-10-19 — Day 1 follow-up: No-silent-stall principle

**Aim**
- Capture the user's observation that an AI task can stop without the user being told, leaving the user to discover the unfinished work later.

**What we discussed or decided**
- Treat silence during unfinished work as a user-experience failure, not a neutral state.
- When the assistant is active again and can inspect the project, it should proactively report unfinished expected work, the last known state, blockers, and next steps.
- Distinguish an ordinary chat from a genuinely configured background task. A prompt cannot create background execution or future notifications by itself.
- Add this principle to the shared master prompt and create a task-specific prompt draft.

**What we actually did**
- Created Prompt 15, "Interruption, Resumption, and No-Silent-Stall", as a clearly labelled draft.
- Created master prompt v0.3, preserving v0.2 and adding a section on task continuity, interruption, and visible status.
- Updated the prompt indexes to link to the new version and draft.

**What was verified**
- GitHub confirmed successful write operations for the new prompt and updated indexes.
- Read-back verification of all these new/updated files is the remaining immediate check.

**Hurdles and friction**
- While responding to the user's proposal, I began carrying out repository updates before sending an acknowledgement. The user received no timely response and had to ask whether everything was okay. This reproduced the very feedback failure under discussion.
- This was a response/communication failure. It does not establish that a background task stopped; the actual issue was that the user was left without an acknowledgement while work was being done.

**What remains open**
- Read back and verify the new prompt and indexes.
- Update the work log and status to reflect this work.
- Consider how the interface could show live task state and interruptions, rather than relying on prompt wording alone.

**Next steps**
1. Complete read-back verification.
2. Continue designing the principle at both prompt/workflow level and product/interface level.
3. Make sure future substantial work starts with a clear acknowledgement when possible, and ends with an honest status/handover.

**Workflow reflection**
- The user's criticism was demonstrated by the interaction itself: performing useful work is not enough if the person cannot tell whether the assistant is responding, working, blocked, or stopped.
- Improvement to try: acknowledge the user's point first, then carry out tool work; report any known limitation or unfinished state explicitly. A prompt can guide this behaviour when the assistant is active, but visible status and genuine background execution require product-level support.


---

## 2026-10-19 — Day 1 follow-up: No-silent-stall principle

**Aim**
- Capture the user's observation that an AI task can stop without the user being told, leaving them to discover unfinished work later.

**What we discussed or decided**
- Silence during unfinished work is a user-experience failure, not a neutral state.
- When the assistant is active again and can inspect the project, it should report unfinished expected work, the last known state, blockers, and next steps.
- Distinguish ordinary chat from a genuinely configured background task. A prompt cannot create background execution or future notifications by itself.
- Add this principle to the shared master prompt and create a task-specific prompt draft.

**What we actually did**
- Created Prompt 15, “Interruption, Resumption, and No-Silent-Stall”, as a draft.
- Created master prompt v0.3, preserving v0.2 and adding guidance on task continuity, interruption, and visible status.
- Updated the prompt indexes to link to the new version and draft.

**What was verified**
- GitHub confirmed successful write operations for the new prompt and updated indexes. Read-back verification remains to be completed.

**Hurdles and friction**
- I began carrying out repository updates before acknowledging the user's proposal. The user received no timely response and had to ask whether everything was okay. This reproduced the feedback failure under discussion.
- This was a response/communication failure; it does not establish that a background task stopped. The user was left without an acknowledgement while repository work was being carried out.

**What remains open**
- Read back and verify the new prompt and updated indexes.
- Update the work log and status to reflect this work.
- Consider how an interface could show task state and interruptions, rather than relying on prompt wording alone.

**Workflow reflection**
- Performing useful work is not enough if the person cannot tell whether the assistant is responding, working, blocked, or stopped.
- Improvement to try: acknowledge the user's point first, then carry out tool work; report limitations and unfinished state explicitly. Prompt wording can guide behaviour while the assistant is active, but visible status and genuine background execution require product-level support.


---

## 2026-10-19 — UI/UX syllabus research resumed

**Aim**
- Respond honestly to the user's question about whether university course syllabuses had been gathered, then make concrete progress on that outstanding task.

**What we discussed or decided**
- The research had not been completed before the user returned. It was important to state that plainly rather than imply background work had continued.
- Use real public university module descriptions as reference points, but label our beginner syllabus as a proposal rather than an official university syllabus.

**What we actually did**
- Reviewed official module information from the Universities of Leeds, Edinburgh, Bath, Kent, and Cardiff.
- Drafted a four-week beginner programme covering UX/UI/HCI foundations, user research, task flows and wireframes, prototyping, usability testing, iteration, and a small portfolio case study.
- Added deliverables, a manageable weekly rhythm, a feedback rubric, ethical boundaries, and direct source links.
- Saved the draft in the repository and indexed it in the research README.

**What was verified**
- Read the syllabus draft back from GitHub after creation.
- Read the research README, current status, work log, and diary before updating records. Further final read-back of the updated records is the remaining check.

**Hurdles and friction**
- The syllabus research had remained unfinished after the previous discussion. The user had to ask about it. No background continuation should be implied.
- The course examples differ in level and scope; the beginner plan is a synthesis and simplification, not a direct reproduction of any one course.

**What remains open**
- Expand the plan into lesson-by-lesson teaching notes, accessible examples, and practical assignment briefs.
- Confirm the learner's available time and preferred focus (websites/apps or broader services) before tailoring the workload.
- Verify the final updated project records after this diary entry is saved.

**Next steps**
1. Read back the final repository updates.
2. Develop Week 1 lesson material and its interface-critique exercise.
3. Keep source facts, our synthesis, and untested assumptions distinct.

**Workflow reflection**
- Honest status is more useful than the appearance of uninterrupted work. The correct report is that the research had not been completed while the user was away, and that a sourced draft was made during this session.


---

## 2026-10-19 — Carnegie Mellon focus and teaching approach

**Aim**
- Establish a consistent academic reference, build a month of learning work, and decide how the lessons should be taught.

**What we discussed or decided**
- Use Carnegie Mellon University's Human-Computer Interaction Institute as the main reference for UI/UX combined with AI and human–AI interaction.
- Avoid picking courses and services at random; prioritise strong evidence and fit for the learning goal.
- Keep all schoolwork in one dedicated folder, even when it connects to broader Sadhana research.
- Treat teaching as an interactive process, not simply reading material: diagnose current understanding, invite the learner's ideas, explain in manageable pieces, practise, test, give specific feedback, and adjust the method.

**What we actually did**
- Created schoolwork/README.md, a 20-session Month 1 course plan, and a guide to our teaching-and-learning approach.
- Used CMU HCII's public course descriptions for Design of AI Products and Services and Human AI Interaction.
- Used CMU Eberly Center guidance on prior knowledge, active learning, concept tests, formative assessment, inclusive low-stakes practice, and learning feedback, alongside research reviews.
- Archived the previous multi-university syllabus in schoolwork/archive and removed it from the active research area. Unrelated Sadhana files were not deleted.
- Updated the project status and research index.

**What was verified**
- The three main schoolwork files were created successfully.
- The earlier syllabus was copied into the schoolwork archive before the old copy was deleted from the research folder.
- Final read-back completed: the three main schoolwork files, archive, research index, status, work log, and diary were fetched again from GitHub. The superseded active syllabus path returned not found, as intended.

**Hurdles and friction**
- The earlier draft had mixed multiple universities, which no longer matched the user's chosen direction. It has been superseded and archived, not treated as the active plan.
- CMU's actual courses may include programming or assume prior knowledge, so the first month is a simplified, non-programming foundation and is not presented as an exact reproduction.

**What remains open**
- Read back all new and updated files to verify the final state.
- Begin Session 1 in an interactive format and use the learner's answers to calibrate pace.
- Keep a record of attempts, feedback, demonstrated understanding, and any lesson changes in schoolwork.

**Workflow reflection**
- “Best” should mean best supported for the specific goal, not a universal ranking or prestige alone. For this project, the direct relevance of CMU's published AI product design and human–AI interaction courses makes it a sensible primary reference.
- The teaching approach must remain responsive: ask before assuming, use practice to reveal understanding, and change course when the evidence says the learner needs a different explanation.


---

## 2026-10-19 — Design session: floating islands, visible completion, and cross-device continuity

**Aim**
- Define how Sadhana should communicate progress and reliability visually, including unfinished work and completion across computer and phone.

**What we discussed or decided**
- Use a consistent three-state system throughout the product: blue for complete and verified; yellow for in progress; red for incomplete, failed, blocked, or interrupted.
- Put a percentage at the centre of the floating-island/folder visual, using a meaningful progress calculation rather than a decorative or invented number.
- Make islands feel elevated from the workspace using gradient separation, depth, layered shadows, subtle halos, and polished interaction details.
- Share design tokens and status meanings across all sections and platforms, while adapting the layout to each device.
- Make unfinished work visible: explain what is done, what remains, the next action, and whether resumption is automatic or requires the user's action.
- When a project finishes, show a temporary desktop preview and, where supported and permitted, a phone notification. Tapping can open the result; dismissing the notification should not remove the saved file.
- Use one reliable task record across devices. Queued, started, finished, and verified must be distinct states.
- Keep the interface quiet: notify for meaningful completion or genuine problems, not every tiny internal step.

**What we actually did**
- Consolidated the user's ideas into a proposed product-design direction and shared status model in conversation.
- Attempted to generate a visual mock-up of the percentage-centred floating island, but image generation was unavailable because of a tool limit.
- Read the existing workflow diary and work log from GitHub and added this session to the diary and work log.

**What was verified**
- The existing work log and diary were fetched from the repository before adding this entry.
- This entry records the design discussion, not a completed software implementation.

**Hurdles and friction**
- The user cannot reliably tell whether work has finished without asking, creating unnecessary interruption and interaction overhead.
- ChatGPT's ordinary conversation interface does not allow the assistant to create a true automatically appearing floating window or independently deliver phone push notifications. Those behaviours require a suitable Sadhana application, background task mechanism, sync, and notification permissions.
- A proposal and an illustrative mock-up are not proof of implementation. No design-system specification or working UI has yet been saved or verified as part of this session.

**What remains open**
- Write and save the shared design-system specification.
- Define measurable progress units and lifecycle rules, including mixed states when some items in a folder are complete and others are not.
- Prototype the floating island, percentage, preview dismissal, and accessible status cues.
- Design and test the cross-device task-state sync and notification architecture.
- Verify all saved implementation artifacts before marking them blue/complete.

**Next steps**
1. Create the design-system specification and link it from the project indexes.
2. Define the task state machine and progress calculation.
3. Prototype the floating-island interface.
4. Investigate platform-specific notification and sync constraints.

**Workflow reflection**
- A design conversation can generate useful decisions, but reliability requires recording them in the project journal and later implementing and verifying them.
- The user should not need to ask repeatedly whether work is finished. A future interface should make task state visible, and the system must never promise background continuation or notifications unless those capabilities are actually configured.


---

## 2026-10-19 — Session: feedback reliability and assessed learning

**Aim**
- Record the principle that people must receive clear feedback on whether requests are underway, completed, incomplete, blocked, or verified; and establish a coursework workflow that assesses understanding and improves our own process.

**What we discussed or decided**
- Missing feedback makes a system feel unreliable because the person cannot tell what is happening or whether a result exists.
- Meaningful requests should receive prompt acknowledgement, proportionate progress updates, and an explicit end state.
- Completion and verification are different claims and must be reported separately.
- Learning should include practical assignments at the end of a week or module, rubric-based marking, specific critique, opportunities for discussion or revision, and a review of the teaching and AI workflow itself.
- Improvement should be evidence-led: identify what could have been better, change something specific, and check whether the change helped.

**What we actually did**
- Drafted master prompt v0.4 with explicit user-feedback and completion-communication principles.
- Created a dedicated coursework assessment and continuous-improvement workflow.
- Linked the new workflow from the teaching guide and schoolwork index.
- Updated the prompt index to identify v0.4 as the current master version.

**What was verified**
- The GitHub write operations returned successful results for the new and updated files. Final read-back verification is still required before treating the updates as fully verified.

**Hurdles and friction**
- The user reported that both Grok and ChatGPT had left them without clear feedback about what was happening or whether work had completed. The reported impact is uncertainty and reduced trust; root causes are not established.
- A useful answer or a saved file alone is insufficient if the user cannot distinguish acknowledgement, active work, completion, and verification.

**What remains open**
- Read back the new master prompt, assessment workflow, and updated indexes/guides.
- Research additional university examples of short practical coursework and formative assessment before finalising the first pilot assignment.
- Run the first assignment-and-marking cycle, then review the quality of both the learner feedback and our workflow.

**Next steps**
1. Verify the saved artifacts.
2. Compare university examples of short module assignments, rubrics, and formative feedback.
3. Use a small Week 1 assignment to pilot marking and process review.

**Workflow reflection**
- We need to tune both the learner's understanding and the system that teaches, marks, communicates, and improves. The latter should be assessed with the same honesty: a proposed improvement is not proven until it is tested.


---

## 2026-10-20 — Design philosophy and status markers

**Aim**
- Resolve the problem of unclear paper-section/task completion by making unfinished and verified work easier to distinguish, and record the full reasoning and actions in the journal.

**What we discussed and decided**
- Use the GitHub documents as a low-cost prototype before implementing this design in the Sadhana interface.
- Pair each colour with a distinct shape/icon and explicit wording: blue circle = COMPLETE — VERIFIED; amber triangle = IN PROGRESS or AWAITING VERIFICATION; red square = NOT DONE, BLOCKED, FAILED, or INTERRUPTED. State the exact condition and next action. Colour alone is not authoritative.
- Treat the palette as a convention to test, not a universal psychological rule. Research on colour associations is context- and culture-dependent.
- Add a broader design principle: preserve philosophical continuity as ideas move from foundational philosophy to design principles, documents, prototypes, implementation, and testing.

**What we did**
- Created `Design_Principles.md`.
- Updated `Task_Status_and_Colour_System.md` with the research rationale and links to three relevant publications.
- Updated `project-management/README.md` to link both documents.

**What was verified**
- Read back the three updated/created files from GitHub and checked the links and research references.
- The diary entry itself is being added now; it must be read back after saving before it can be marked verified.

**Hurdles and friction**
- The first attempt to create the design-principles file failed; a later attempt succeeded. The reason for the initial failure is unknown.
- The user pointed out that meaningful design decisions and positive edits must be journalled as they happen. The latest design work had not yet been recorded in the diary.

**What remains open**
- Apply the status markers to real Sadhana tasks and observe whether they clarify what is done, unverified, or blocked.
- Review the palette and wording based on actual usability and accessibility feedback. No software interface has been implemented by these document edits.

**Next steps**
1. Save and read back this diary entry.
2. Apply the system to current tasks and record friction or ambiguity.
3. Review the pilot before calling the design standard established.

**Workflow reflection**
- The journal must record the process, not only the final result: where work paused, what problem we examined, the solution chosen, the steps taken, what was verified, what failed, and what remains.
- Improvement: journal every meaningful design change or decision as part of the same workflow, then read back the saved record. Do not claim a journal update is complete before verifying it.


---

## 2026-10-20 — Master prompt updated to require journalling every meaningful change

**Aim**
- Make sure meaningful design decisions, modifications, fixes, and solutions are captured in the journal as part of the work, without the user needing to remind the assistant.

**What we discussed and decided**
- The diary should record the process that led to a solution: the problem or stopping point, discussion and reasoning, decision, actions, outcome, verification, friction, and next steps.
- Earlier entries already record several major design sessions, including floating-island UI, task-state feedback, and the colour-system prototype. However, the diary cannot yet be assumed to contain every meaningful edit or decision in full. Missed work should be audited and added retrospectively with an honest label, not reconstructed as if written at the time.
- Keep the full process in the Workflow Diary and use the Work Log for concise repository milestones.

**What we actually did**
- Created [Shared AI Working Philosophy v0.5](../prompts/master/Shared_AI_Working_Philosophy_v0.5.md), adding a mandatory rule to journal meaningful design changes, modifications, fixes, solutions, and working-method decisions.
- Added requirements for retrospective entries when earlier work was missed, explicitly distinguishing reconstructed records from contemporaneous notes.
- Updated the [Prompt Library index](../prompts/README.md) to identify v0.5 as the current master prompt and preserve v0.4 as history.

**What was verified**
- GitHub confirmed successful writes for the new v0.5 file and updated prompt index. Read-back verification of those files and this diary entry is the remaining check before marking this entry verified.

**Hurdles and friction**
- The user had to point out that journal updates should happen every time meaningful design work occurs. This latest colour-and-shape work was documented in the diary only after the user raised the omission.
- Earlier diary entries do cover a number of previous design discussions, but coverage is uneven; a full retrospective audit has not yet been completed.

**What remains open**
- Read back v0.5, the prompt index, and this diary entry after saving.
- Add a corresponding concise Work Log entry.
- Audit earlier meaningful design changes in manageable groups, adding clearly labelled retrospective notes for any gaps. Do not claim every historical edit has been recovered until that audit is complete.

**Next steps**
1. Verify the saved prompt and diary/index changes by reading them back.
2. Update and verify the Work Log.
3. Review earlier diary and work-log coverage and record remaining gaps.

**Workflow reflection**
- A rule in a prompt is useful only if we apply it consistently. The record should be updated as part of the change, not left as optional follow-up administration. The journal must distinguish what was discussed, what was actually changed, and what was verified.


---

## 2026-10-20 — Embedded task-status mini UI and explored shape symbolism

**Starting point**
- The status specification was mostly text, making it harder to scan and apply during a paper critique. The user proposed a compact visual with the three states shown side by side.
- The user also suggested giving each shape a meaningful rationale: a circle as a complete whole, a triangle as upward development, and a square as a possible sign of a problem.

**Discussion and design reasoning**
- A compact UI-style visual can make the system easier to understand at a glance, while explicit labels ensure the design does not rely on colour or symbolism alone.
- Circle-as-wholeness and triangle-as-direction/development are plausible metaphors, but not universal meanings. A square should not be described as inherently negative; for this system, its firm edges and corners can serve as a deliberately chosen metaphor for a boundary, obstacle, or unresolved constraint.
- These are design hypotheses to test, not established psychological laws. The actual status text and verification evidence remain authoritative.

**Actions completed**
- Created the mini UI asset at [task-status-mini-ui.svg](assets/task-status-mini-ui.svg), with three status cards:
  - Blue circle — complete and verified.
  - Amber triangle — in progress or awaiting verification.
  - Red square — not done, blocked, failed, or interrupted.
- Embedded the visual into [Task Status and Colour System](Task_Status_and_Colour_System.md) and added a table explaining the operational status and provisional rationale for each shape.

**Verification**
- GitHub confirmed the status specification update was saved. Read-back checks for the specification, visual asset, and this diary entry are still required before marking the full change verified.

**Still open**
- Read back the updated specification and visual asset and confirm that the relative image path works in the repository.
- Add the corresponding concise Work Log entry and read it back.
- Test the mini UI while critiquing a real paper or document; revise if users misunderstand any shape or label.

**Workflow reflection**
- A document used for critique should show the state of each part visibly: blue for complete and checked, amber for work in progress or awaiting a check, and red for unresolved work or an obvious fault. The visual should expose the next action rather than merely decorate the page.

---

## 2026-10-26 — Retrospective session: repository population, thread preview idea, and continuity

**Entry type:** Retrospective reconstruction of the current conversation; not a claim that every earlier conversation has been recovered.

### Starting point / stopping point
The user asked that work continue across the available project history before lessons begin. The immediate work was to populate Sadhana's GitHub repository with previously discussed ChatGPT and Claude improvement ideas, keep the journal current, and ensure each idea is linked to the correct place in the repository. The user specifically clarified that the diary must preserve the stopping point and the solution proposed, not merely create a use-case document.

### User proposal captured
The user described a thread-discovery idea: **press and hold a conversation/thread to preview what is inside it without opening or switching into that thread**. The intent is to make it easier to identify the right conversation, reduce accidental context switches, and recover work without losing the current thread. This is a user-proposed design direction, not yet a tested solution.

### How it should be recorded
- Keep the detailed UX problem, intended behaviour, acceptance criteria, failure cases, and test plan in the existing [SA-UX-006 use case](../research/use-cases/SA-UX-006_Thread_Context_Preview_and_Active_Thread_Indicator.md).
- Keep this diary as the process record: where the work stopped, the idea proposed, the rationale, what was created, what was checked, and what remains unresolved.
- Keep the [evidence register](../evidence/EVIDENCE_REGISTER.md) as the map from reported observations to records; do not treat the idea as validated until tested.
- Add a concise dated milestone to the Work Log after meaningful repository work.
- During the historical audit, add clearly labelled retrospective entries for important earlier ideas that were omitted. Do not fabricate exact dates or pretend reconstructed entries were written contemporaneously.

### Repository work verified in this session
- Re-fetched the two Lesson 2 files in `schoolwork/Week_1/` and `schoolwork/week-01/`. They are distinct files with overlapping subject matter and different wording; they should be compared and reconciled before either is removed or renamed.
- Re-fetched Week 1 learning assets, the evidence register, DEC-001, and EXP-001; the files were present and readable.
- Updated this historical reconstruction tracker with the verified file list, duplicate-folder finding, prompt-index finding, and next audit steps; then fetched the tracker again to confirm the update was saved.

### Decisions and limits
- Do not begin teaching lessons until the user agrees the repository is sufficiently organised.
- Do not merge or delete the two Lesson 2 files until their full content and inbound links have been compared.
- The repository is currently public. The user intends to change its visibility later; until the owner confirms that change, treat all committed material as publicly visible and do not add private or sensitive information.
- Work does not continue in the background when the session is inactive. Progress must be made and recorded during active tool work, and must not be implied otherwise.

### Next actions
1. Compare both Lesson 2 documents in full and inspect all Week 1 index links before choosing a canonical location.
2. Review the master prompt versions 0.2–0.5 against the core principles and record substantive differences without erasing history.
3. Continue extracting ChatGPT/Claude improvement ideas from available workflow diary and work-log records, linking to existing use cases before creating new ones.
4. Audit relative links and indexes; read back every file changed.
5. Update status and work log only for actions actually completed and verified.

### Reflection
A use case explains a problem and candidate solution; the diary explains how the team arrived at it and where the work paused. Both are necessary. The journal is part of the work, not optional administration.

