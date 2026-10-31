# SA-UX-011 — Cross-Assistant Work Exchange

**Status:** AMBER TRIANGLE — draft requirements recorded; implementation and evaluation pending.
**Date:** 2026-10-31
**Scope:** ChatGPT, Claude, GitHub, and document services where authorised connectors exist.

## 1. Intended outcome
Exchange project documents and critiques with minimal manual copying, preserving the authoritative version and user control.

## 2. Context and trigger
The user has requested collaboration between ChatGPT and Claude, including mutual review and shared documents. Trigger: a draft is ready for another assistant to critique.

## 3. Evidence and provenance
Reconstructed from the conversation context supplied to this session, including the request for both systems to listen, exchange documents, and critique work. Original full transcripts and a working integration have not been inspected. This is a requested workflow, not evidence that either product supports it.

## 4. Problem and impact
Manual copying can omit long passages, lose provenance, create competing versions, and increase user effort. These are risks to evaluate; no measured frequency is available.

## 5. Preconditions
Identify the authoritative repository path and commit. Verify each connector's actual read/write capabilities. Authorisation to update GitHub does not authorise sending messages or material to a second service. Confirm the permitted content and destination before any cross-service transfer.

## 6. Main flow
1. Select a source document at an immutable commit.
2. Prepare a handoff containing the complete scoped text or accessible source, version, question, and review criteria.
3. Transfer only through an available, authorised mechanism.
4. Record the returned critique with its source and version.
5. Compare objections against evidence and requirements.
6. Apply accepted edits while retaining history.
7. Read back the saved result and report the exact changed paths.

## 7. Alternatives
Use a review file in GitHub if both assistants can access it. Otherwise prepare a bounded handoff for the user. Never describe a prepared handoff as delivered. Simultaneous listening requires separately verified product support.

## 8. Acceptance criteria
- Every handoff identifies source path, commit, scope, and intended recipient.
- Receiver can confirm the complete scoped content; any truncation is explicit.
- Review separates evidence, inference, and suggestions.
- Only one document is designated authoritative.
- No claim of delivery or synchronisation without returned evidence.
- No private material is added to a public repository.

## 9. Failure and recovery
Missing connector: report the limitation and preserve the prepared handoff.
Truncation: stop review of missing sections and split into numbered parts.
Stale source: compare with current head before applying edits.
Conflicting edits: preserve both proposals and explain resolution.
Denied transfer: stop that transfer; continue permitted local analysis.

## 10. Evaluation plan
Compare manual copy/paste with a verified connector workflow on the same non-sensitive test document. Count user actions, omissions, version conflicts, completion time, and unsupported delivery claims. No experiment has run.

## 11. Dependencies and ownership
Project owner selects scope; executing assistant verifies capabilities and saved output. Related: [authoritative-record decision](../decisions/DEC-001_Repository_as_Authoritative_Project_Record.md), [capability record](SA-UX-004.md).

## 12. Next action and completion boundary
Test a single document handoff only when the destination and transfer mechanism are available and authorised. Drafting this requirement does not implement an integration.
