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
