# Sadhana — Shared Task Status and Colour System

**Version:** 0.1  
**Status:** Working specification; first pilot is the GitHub documentation workflow.  
**Purpose:** Make the state of work immediately understandable, expose unfinished items, and test the proposed Sadhana status system before implementing it in software.

## 1. Core principle

Every meaningful task or deliverable should have a visible state. A reader should not have to infer whether work is finished from silence, a heading, or an optimistic sentence.

Use the same meanings in project documents, task lists, coursework, prototypes, and eventually the Sadhana interface. The document workflow is our first low-cost prototype. Record problems with the system and improve it based on use.

## 2. The three shared status colours

Always pair colour with a plain-language label and an icon/emoji. Colour alone is not accessible and may not render consistently in every interface.

- 🔵 **COMPLETE — VERIFIED:** The requested action is finished, the result has been saved or persisted where applicable, and the relevant result has been checked. State what was checked.
- 🟡 **IN PROGRESS — NOT YET VERIFIED:** Work is actively being carried out, or an action has been completed but still needs a check. Add a short qualifier such as **ACTIVE** or **AWAITING VERIFICATION**; do not imply that waiting work is active.
- 🔴 **NOT DONE / BLOCKED / FAILED / INTERRUPTED:** The item is not complete. State the specific condition, why it remains unfinished when known, and the next action or dependency. **NOT STARTED** is a valid explicit qualifier.

The word label is authoritative if colour is missing or displayed differently. Do not use blue to mean merely drafted, saved, or attempted when verification is still required.

## 3. Task states and transition evidence

For detailed task tracking, use these text states alongside the colour:

1. **PLANNED / NOT STARTED** — no execution has begun.
2. **ACTIVE** — work has actually started and is currently being carried out.
3. **WAITING FOR INPUT / DEPENDENCY** — work cannot proceed until a named input, permission, service, or decision arrives.
4. **INTERRUPTED** — work stopped before completion; record the last completed step.
5. **FAILED** — an attempt did not produce the intended result; record the observed failure and any safe retry.
6. **COMPLETED — AWAITING VERIFICATION** — the action was performed, but the result has not yet been checked.
7. **COMPLETE — VERIFIED** — the result was checked against the stated requirement.

Map states to colours as follows: planned/not started, waiting, interrupted, failed, and other unfinished work are 🔴; active and completed-awaiting-verification are 🟡; only complete-verified is 🔵. Keep the exact text state so the red category does not hide important differences.

## 4. What every unfinished item must say

For each 🔴 item, record:
- **What remains:** the specific unfinished outcome.
- **Why:** known blocker or reason; say **not yet known** rather than guessing.
- **Next action:** the concrete next step.
- **Owner/dependency:** where useful, say who or what is needed.
- **Continuation:** whether work can continue in the current session, requires user input, or needs a separately configured background process.

Do not claim that work will continue automatically unless an actual mechanism has been configured and verified.

For 🟡 items, say what has started or been done and what verification remains. For 🔵 items, record the verification performed.

## 5. Applying the system in GitHub documents

Use visible text markers, not colour styling alone:

- 🔵 **COMPLETE — VERIFIED**
- 🟡 **ACTIVE — NOT YET VERIFIED**
- 🟡 **AWAITING VERIFICATION**
- 🔴 **NOT STARTED**
- 🔴 **BLOCKED**
- 🔴 **FAILED**
- 🔴 **INTERRUPTED**

For a short list, put the marker beside each task. For a larger list, use a table with columns such as **Item**, **Status**, **Evidence / what is done**, **What remains / blocker**, and **Next action**. Avoid duplicating a status register in several files: keep one authoritative detailed list and link to it from summaries.

## 6. Progress percentages

A percentage may be shown only when progress is calculated from meaningful, observable units defined in advance. State the denominator or method where it is not obvious. Do not invent a percentage to make an island, task, or document look more complete. A task can be 100% complete only when its required work is complete; if verification is required, do not call it verified until that check passes.

## 7. Accessibility, research basis, and consistency

- Always use a text label as well as the icon/colour.
- Use consistent definitions across desktop, phone, tablet, GitHub, coursework, and future product UI.
- Keep wording plain and concise; explain technical blockers.
- Do not equate visual polish with successful work.
- Preserve history when a status changes so that meaningful failures and improvements can be reviewed.

### Why use colour at all?

Colour can support quick recognition, but its meaning depends on context, culture, and the task. Research does not justify treating any colour-emotion association as universal. In Sadhana, blue for verified completion, amber for work in progress or awaiting verification, and red for unfinished or blocked work are **design conventions we are choosing to test**, not psychological laws. Pairing each colour with a distinct shape/icon and an explicit text label reduces reliance on colour perception and makes the state clearer when colours render differently.

Relevant research:
- Jonauskaite, D. & Mohr, C. (2025). “Do we feel colours? A systematic review of 128 years of psychological research linking colours and emotions.” *Psychonomic Bulletin & Review*. [Open-access article at PubMed Central](https://pmc.ncbi.nlm.nih.gov/articles/PMC12325498/).
- “A systematic investigation of conceptual color associations.” [PubMed record](https://pubmed.ncbi.nlm.nih.gov/31763867/).
- Schloss, K. B. (2024). “Color Semantics in Human Cognition.” *Current Directions in Psychological Science*. [https://doi.org/10.1177/09637214231208189](https://doi.org/10.1177/09637214231208189).

These sources inform the rationale, but do not by themselves prove that this particular status palette is best. The palette must be evaluated through Sadhana's own usability and accessibility testing.

## 8. How we will test whether this works

During the documentation pilot, notice and record:
- Can the user quickly tell what is finished, what is still open, and what is blocked?
- Are any labels ambiguous or misleading?
- Does the status list make unfinished work easier to find without making the document harder to scan?
- Are items incorrectly marked complete before read-back or other required verification?
- Does the system reduce the need to ask “are you doing anything?” or reopen files to discover what happened?

After using it on real work, review examples of confusion, missed updates, and useful feedback. Change the rules only with a reason and record the change. This is a working prototype, not yet evidence that the system is effective.

## 9. First pilot checklist

- [ ] Add this specification to the project-management index.
- [ ] Use status markers in current project status and future meaningful task lists.
- [ ] Keep unresolved work visibly red and name the next action.
- [ ] Mark items blue only after checking the saved result.
- [ ] Review the pilot after several real tasks and record what worked or failed.
- [ ] Later compare the document workflow with the proposed floating-island UI and shared task-state source.

## 10. Current limitation

This specification changes the way we document and communicate work; it does not itself add coloured backgrounds, automatic status calculation, live progress tracking, cross-device synchronisation, or notifications. Those require product implementation. In GitHub Markdown, the icon plus label is the reliable baseline; rendered colour badges may be added later if they improve accessibility and consistency.
