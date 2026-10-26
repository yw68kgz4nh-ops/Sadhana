# DEC-001 — GitHub as the Authoritative Project Record

**Status:** 🟠 Amber — working decision, to be reviewed as the workflow evolves.  
**Date recorded:** 2026-10-26  
**Area:** Project governance and continuity

## Context

The project spans multiple ChatGPT and Claude conversations, devices, prompt versions, research notes, learning papers, and use cases. Conversation context alone does not guarantee that a document exists in a durable location, is current, or has been verified.

## Decision

Use the Sadhana GitHub repository as the authoritative durable record for project artefacts that are suitable for a public repository. Use conversations to develop ideas, but transfer agreed material into the appropriate file and link it from an index. Do not treat remembered context as proof that an item has been saved.

## Operating rules

- One authoritative file per major artefact; link to it rather than create competing copies.
- Preserve meaningful history when changing master prompts or other important documents.
- Label reconstructed drafts and keep their provenance clear.
- Separate discussion, proposal, attempted action, successful completion, and verification.
- Read changed files back from GitHub before claiming they are verified.
- Keep sensitive or confidential material out of the public repository.
- If original content cannot be recovered, record the gap instead of inventing a replacement.

## Alternatives considered

1. Keep the work primarily in conversation history — rejected as insufficiently reliable for cross-session retrieval and version control.
2. Copy every item into several tools and folders — rejected because competing copies can drift.
3. Use GitHub as the durable record and link from conversations or other tools — selected, with a later review of privacy and accessibility needs.

## Trade-offs and risks

GitHub offers version history and clear file paths, but may be less accessible for some users and the repository is public. Public visibility is a material risk and must be reviewed; this decision does not mean private material should be uploaded.

## Revisit when

The repository's privacy setting changes, a safer integrated document workflow becomes available, or maintaining GitHub creates more friction than it removes.

## Related records

- project-management/HISTORICAL_RECONSTRUCTION_AND_RECONCILIATION.md
- project-management/WORKFLOW_DIARY.md
- project-management/WORK_LOG.md
