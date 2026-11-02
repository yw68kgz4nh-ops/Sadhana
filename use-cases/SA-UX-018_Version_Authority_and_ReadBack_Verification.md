# SA-UX-018 — Version Authority and Read-Back Verification

Status: Draft saved; historical evidence and tests pending.

## Problem
Several master prompt or document versions may each be described as current, while a write may not have succeeded.

## Proposed behavior
Maintain one current-version pointer and changelog. Label drafted, committed, and read-back verified distinctly. Retain superseded versions and identify the authoritative GitHub path.

## Acceptance criteria and tests
- A new version does not become current until the saved file and pointer have been read back.
- A failed upload leaves the previous version authoritative.
- A person can compare the current version with its predecessor and see exactly what changed.
- Test upload failure, conflicting updates, and stale device views.

## Evidence
Reconstructed from prior Sadhana conversations. Original transcripts, overlaps with SA-UX-009, and independent testing still require reconciliation.

## Detailed scenario and test oracle — added 2026-11-02

**Scenario:** Example: The repository contains versions 0.2–0.8 of the shared AI prompt, while indexes or a chat refer to different versions as 'current'.

**Expected main flow:** Display one authoritative version pointer, preserved older versions, changelog and an exact GitHub path. Advance the pointer only after the new content and pointer have been fetched successfully.

**Failure and recovery:** A write can return an error after partially succeeding; check the exact GitHub path/commit before retry. On failure, retain the last confirmed pointer.

**Evaluation:** Test a concurrent edit, stale link, failed write, and back-and-forth version selection; assess whether participants can identify the true current version.

**Related records:** SA-UX-002, SA-UX-009, SA-UX-017.

**Evidence boundary:** The improvement is a design requirement captured retrospectively, not a verified software fix. Testing, provenance and any necessary expert review remain pending.
