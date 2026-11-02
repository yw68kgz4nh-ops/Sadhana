# SA-UX-015 — Pre-Limit Planning and Graceful Task Handover

Status: Draft saved; historical source evidence and product feasibility not yet independently verified.
Scope: Human–AI Design Partnership / Sadhana. Applies to ChatGPT and/or Claude as a proposed improvement, not a verified product defect.

## User need and observed/reported problem
Usage limits may interrupt lengthy research or voice lessons without time to preserve work.

## Proposed design behavior
Provide available quota/limit warnings when reliably known; offer shorter tasks, save checkpoint and a handover summary before interruption; never guess remaining minutes.

## User story
As a person collaborating with AI across research and real tasks, I want pre-limit planning and graceful task handover so I can trust the interface and retain control.

## Acceptance criteria
- Show what is known, unknown, planned, running, saved and verified without conflating them.
- Preserve the correct project and task context; provide a clear recovery path if unavailable.
- Do not claim a completed external action without checking the resulting record.
- Keep user control over consequential decisions and permissions.

## Failure and recovery tests
Simulate approaching limit, unexpected limit and unknown quota; verify warning accuracy and recoverable handover.

## Evidence and follow-up
Reconstructed from prior Sadhana discussions; obtain original dated conversation excerpts and independent product tests before marking verified. Check for overlaps with SA-UX-001–012 and consolidate where necessary rather than counting duplicates as separate defects.

## Detailed scenario and test oracle — added 2026-11-02

**Scenario:** Example: A student is midway through a long voice lesson or repository audit and receives an interruption or quota limit without warning.

**Expected main flow:** Where actual quota data exist, warn with a measured threshold and offer Finish current section, Save checkpoint or Switch input mode. Preserve explicit next step.

**Failure and recovery:** If exact remaining quota isn't exposed, do not show fictitious minutes or reset hours; provide general interruption-safe checkpoints instead.

**Evaluation:** Test known and unknown quota, interrupted upload, unexpected app exit, and verify a saved handover allows resumption without re-explaining.

**Related records:** SA-UX-007, SA-UX-013, SA-UX-021.

**Evidence boundary:** This test case is based on the Sadhana user's discussion and a reconstructed design proposal. It remains untested; do not claim the product has these capabilities.
