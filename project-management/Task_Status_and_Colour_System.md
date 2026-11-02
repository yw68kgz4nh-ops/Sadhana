# Sadhana — Shared Task Status and Colour System

**Version:** 0.2 (2026-11-02)  
**Status:** 🔵 COMPLETE — specification revised; 🟠 evidence and usability pilot still pending.  
**Previous version:** [Archived v0.1](../archive/Task_Status_and_Colour_System_v0.1_preserved_2026-11-02.md)

## 1. Agreed project convention — single source of meaning

Use shape, written name and state label together. The key is a **working-document convention**, not final-paper decoration.

| Marker | Status | Meaning | Example |
|---|---|---|---|
| 🔵 **BLUE CIRCLE** | **COMPLETE** | The defined work has been finished; may still need an independent check | A draft has been written |
| **▲ AMBER TRIANGLE** | **IN PROGRESS / AWAITING CHECK** | Work actually underway, or finished output awaiting a named check | AI has finished generating but human review is pending |
| 🟥 **RED SQUARE** | **NEEDS FIXING / BLOCKED / FAILED** | Something is wrong and must be addressed | File write failed, link broken |
| 🟢 **GREEN CHECKED MARKER** | **CHECKED AND ADDED IN** | The outcome was read back or checked and added to its authoritative destination | GitHub file committed and content verified |

**Human approval is distinct from technical read-back.** A saved-and-checked draft is not automatically an accepted paper, successfully learned lesson, valid scientific finding, or working feature. Say what kind of check happened.

The amber marker uses an explicit triangle character and word because emoji palettes often depict an orange *circle*; shape matters for accessibility. Green has a defined **review state**, but no new mandatory shape beyond a distinct green checked marker has been decided by the project lead. Design prototypes should test and confirm a final glyph.

## 2. Operational lifecycle states

- **PLANNED / NOT STARTED:** A future intention; label it plainly. Not automatically a system error.
- **ACTIVE:** Evidence of real execution; use amber.
- **WAITING / INTERRUPTED:** Name what stopped, the last confirmed action, and required input; use amber for normal awaiting review, red for a genuine blockage or failure.
- **FAILED / BROKEN / WRONG RESULT:** Use red and state the cause only if known.
- **FINISHED:** Use blue and state what is actually finished.
- **CHECKED AND ADDED:** Use green only after the relevant saved output was independently inspected at its authoritative destination.

A final submitted artifact may be clean of working markers while its separate project status record retains the history. See [SA-UX-024](../use-cases/SA-UX-024_Status_Metadata_Hidden_From_Final_Deliverables.md).

## 3. Never confuse technical, content, and human checks

Example: A use-case document may be **green — read-back verified as a saved GitHub file**, while the **use-case requirement is amber — awaiting human review**, and the **proposed product feature is red — not implemented**. These are separate dimensions.

An assistant should never infer that an ordinary chat remains actively working once its response finishes. A background task must have an actual task service and state record before progress or future completion is promised.

## 4. Visual and accessibility requirements

- Always pair color with distinct shape and a plain-language label.
- Don't rely on color, movement, or animation alone.
- State what remains and what the user can do next.
- Use estimated time only when grounded in real measurements; otherwise say progress is unknown.
- Avoid unnecessary notifications. Keep quiet, meaningful feedback.
- For a multi-item project, percentage = number of completed defined units / total defined units, **only** if units are comparable and set in advance.
- Do not alter existing academic papers, source code or final print by inserting internal traffic-light markers unless their author explicitly wants them as content.
- Use identical meanings on phone, PC, documents and future UI; the actual controls may be platform-specific.

## 5. Example task-state table

| Task | Work state | Verification state | Next action |
|---|---|---|---|
| New GitHub file created | 🔵 COMPLETE | 🟠 Awaiting check | Fetch saved file |
| File fetched and contents match | 🔵 COMPLETE | 🟢 CHECKED AND ADDED | Seek human review of content |
| API returned an error | 🟥 NEEDS FIXING | Not verified | Inspect whether the write took effect before retry |
| A lesson paper exists | 🔵 Paper written | 🟠 Learning not assessed | Ask learner to do exercise and quiz |

## 6. How to evaluate this convention

Pilot on several real tasks. Ask participants to identify finished, checked, waiting, blocked and human-approved states; record misinterpretations, time to locate unfinished work, false completion claims and cognitive load. Compare with the [task-preview experiment](../experiments/EXP-001_Thread_Preview_Usability_Test.md) where appropriate. A written convention is not a validated usability result.

## 7. Existing visual and associated research

The [v0.1 mini UI illustration](assets/task-status-mini-ui.svg) remains a **historical illustrative artifact**, not an authoritative legend: its glyphs/status meaning may differ from this corrected convention. It requires a visual revision and usability check before publication as an accurate status mock-up.

References carried forward for future source checking:
- Jonauskaite & Mohr (2025), [systematic review of color–emotion associations](https://pmc.ncbi.nlm.nih.gov/articles/PMC12325498/).
- Schloss (2024), [Color Semantics in Human Cognition](https://doi.org/10.1177/09637214231208189).

Neither establishes universal meanings for Sadhana's palette. The rationale and mappings are design hypotheses to be tested.

## 8. Change log and review

- **2026-11-02:** Preserved v0.1 in archive; clarified blue=finished vs green=checked and added; aligned amber with triangle and red with square; separated internal status, human signoff, and final output. Change is based on explicitly discussed Sadhana rules.
- **Still open:** Align/replace SVG artwork, review status labels in older files, run usability pilot and obtain approval of the final glyphs. Do not retroactively alter historical journal quotations to make them appear consistent.
