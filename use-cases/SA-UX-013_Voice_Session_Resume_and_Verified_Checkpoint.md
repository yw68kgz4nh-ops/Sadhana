# SA-UX-013 — Voice Session Resume and Verified Checkpoint

Status: Draft saved; historical source evidence and product feasibility not yet independently verified.
Scope: Human–AI Design Partnership / Sadhana. Applies to ChatGPT and/or Claude as a proposed improvement, not a verified product defect.

## User need and observed/reported problem
After returning to voice or reopening the app, the person needs to resume the correct Sadhana task without reconstructing it.

## Proposed design behavior
Offer a non-intrusive Resume previous work? panel naming project, thread, last verified checkpoint and next step; never silently switch threads.

## User story
As a person collaborating with AI across research and real tasks, I want voice session resume and verified checkpoint so I can trust the interface and retain control.

## Acceptance criteria
- Show what is known, unknown, planned, running, saved and verified without conflating them.
- Preserve the correct project and task context; provide a clear recovery path if unavailable.
- Do not claim a completed external action without checking the resulting record.
- Keep user control over consequential decisions and permissions.

## Failure and recovery tests
Reopen after interruption; choose Resume or Not now; verify thread and checkpoint match; test stale/missing checkpoint and recovery.

## Evidence and follow-up
Reconstructed from prior Sadhana discussions; obtain original dated conversation excerpts and independent product tests before marking verified. Check for overlaps with SA-UX-001–012 and consolidate where necessary rather than counting duplicates as separate defects.

## Detailed scenario and test oracle — added 2026-11-02

**Scenario:** Example: A user closes voice mode during Sadhana research and reopens the app, but a philosophy thread is shown. The interface must not assume that the last visually displayed chat was the intended research project.

**Expected main flow:** Resume card shows exact Sadhana project, last task, source and checkpoint; user chooses Resume, Preview or Dismiss.

**Failure and recovery:** A checkpoint may be absent or outdated: show 'Last verified step unknown' and search project chats rather than inventing continuity.

**Evaluation:** Test five resumes after switching among two projects, including one deleted conversation. Count wrong-thread launches and steps to recover.

**Related records:** SA-UX-001, SA-UX-010, SA-UX-025.

**Evidence boundary:** This test case is based on the Sadhana user's discussion and a reconstructed design proposal. It remains untested; do not claim the product has these capabilities.
