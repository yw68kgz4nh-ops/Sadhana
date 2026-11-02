# SA-UX-016 — Project and Library Location Clarity

Status: Draft saved; historical source evidence and product feasibility not yet independently verified.
Scope: Human–AI Design Partnership / Sadhana. Applies to ChatGPT and/or Claude as a proposed improvement, not a verified product defect.

## User need and observed/reported problem
People cannot tell whether a file is in a Project, Library, chat attachment or GitHub, and may create competing copies.

## Proposed design behavior
Show a clear location breadcrumb, authoritative-source label and explicit save destination; explain when a file has not actually been uploaded.

## User story
As a person collaborating with AI across research and real tasks, I want project and library location clarity so I can trust the interface and retain control.

## Acceptance criteria
- Show what is known, unknown, planned, running, saved and verified without conflating them.
- Preserve the correct project and task context; provide a clear recovery path if unavailable.
- Do not claim a completed external action without checking the resulting record.
- Keep user control over consequential decisions and permissions.

## Failure and recovery tests
Create draft in chat; attempt Project save; verify destination and failure states; inspect on phone and desktop.

## Evidence and follow-up
Reconstructed from prior Sadhana discussions; obtain original dated conversation excerpts and independent product tests before marking verified. Check for overlaps with SA-UX-001–012 and consolidate where necessary rather than counting duplicates as separate defects.

## Detailed scenario and test oracle — added 2026-11-02

**Scenario:** Example: The user sees 'Human–AI Design Partnership' folders in Library and expects them inside the current ChatGPT Project. A chat artifact is then described as saved even though it exists only in the conversation.

**Expected main flow:** Display File location: Project/Library/GitHub and a path/revision when applicable. A save operation returns a verified destination and link.

**Failure and recovery:** If there is no permission to attach a Library document to a Project, say so explicitly; do not simulate a successful move by creating a similarly named folder elsewhere.

**Evaluation:** Ask testers to find a prompt in each surface, identify the authoritative copy, and intentionally trigger a failed save; count mistaken locations and duplicate creation.

**Related records:** SA-UX-002, SA-UX-003, SA-UX-018.

**Evidence boundary:** This test case is based on the Sadhana user's discussion and a reconstructed design proposal. It remains untested; do not claim the product has these capabilities.
