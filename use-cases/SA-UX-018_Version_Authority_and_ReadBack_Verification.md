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
