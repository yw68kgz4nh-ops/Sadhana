# Sadhana Evidence Register

**Status:** 🟠 Amber — initial register; sources must be added and reconciled over time.

This register maps project claims to their best available evidence. It deliberately distinguishes user-reported observations from independently verified product behaviour.

| ID | Claim or topic | Current evidence available | Confidence / limitation | Next action |
|---|---|---|---|---|
| EV-001 | Users may struggle to identify the active conversation and preview other threads without switching. | User's detailed proposal recorded in the current project conversation; formal use case SA-UX-006. | Strong evidence that this user experienced the problem; not evidence of prevalence among all users. | Prototype and test with multiple threads and users. |
| EV-002 | The user reported difficulty finding conversations and resources within Sadhana and distinguishing Project from Library organisation. | Prior project conversations summarised in SA-UX-001, SA-UX-002, SA-UX-010. | Reconstructed summaries; original conversations should be linked where accessible. Exact product cause is unknown. | Map each claim to original source thread and reproducible steps. |
| EV-003 | The user reported different voice-control availability or settings between phone and computer. | Prior project conversations summarised in SA-UX-008. | User-reported symptom; underlying cause not established. | Record device, app/browser, mode, date, and repeatability if retested. |
| EV-004 | The user reported confusion and waiting around usage limits or interruptions. | Prior project conversations summarised in SA-UX-007 and Prompt 15 draft. | Reconstructed summary; account-specific behaviour not independently verified. | Link original source and test state communication. |
| EV-005 | Execution claims should be verified before being described as complete. | Repository workflow rules, prompts, and SA-UX-004/009. | Project governance decision; effectiveness still needs evaluation. | Audit future tasks for tool result plus read-back evidence. |
| EV-006 | Week 1 course materials exist in more than one directory naming pattern. | Current GitHub tree includes both schoolwork/Week_1/ and schoolwork/week-01/. | Directly verified from repository tree; which folder should be canonical needs resolution. | Reconcile links and files before moving or deleting content. |

| EV-007 | The project lead proposed a visual status island, measurable percentage, delay banner, and clear failure recovery. | [2026-11-01 lesson record](../schoolwork/Week_1/Session_2026-11-01_Human_AI_Interaction.md); [focused exercise record](../schoolwork/Week_1/Visibility_of_System_Status_Exercise_Record.md); [design spec](../research/design-specs/Floating_Island_Task_State_UI_v0.1.md). | Strong evidence of user-origin design requirements; not software implementation or external usability evidence. | Prototype timing/states, test accessible comprehension and unsupported duration estimates. |
| EV-008 | An assisted proforma-invoice wizard should flag wrong folder selection, invalid discounts and unapproved purchases/payment actions. | Reconstructed [wizard requirements](../research/case-studies/Assisted_Invoice_PO_Wizard_Requirements_v0.1.md) and [SA-UX-019](../use-cases/SA-UX-019_Error_Prevention_for_Assisted_Business_Documents.md). | Reported requirements; no actual tax, customer or software system verified. | Build synthetic test data and validate each error case with an approved expert workflow. |
| EV-009 | Working status markers should be removed from final print/papers while internal collaboration states remain traceable. | [2026-11-01 learning session](../schoolwork/Week_1/Session_2026-11-01_Human_AI_Interaction.md) and [SA-UX-024](../use-cases/SA-UX-024_Status_Metadata_Hidden_From_Final_Deliverables.md). | Explicit working preference; does not establish the best approach for all users. | Compare working view and final artifact export on test files. |
| EV-010 | Four colour meanings were agreed: blue=complete, amber triangle=in progress, red square=needs fixing, green=checked and added. | [Status specification v0.2](../project-management/Task_Status_and_Colour_System.md) preserving v0.1 and dated discussions. | Governance decision documented, not evidence of universal symbol comprehension. | Run quick recognition and accessibility pilot and correct historical SVG. |

## Evidence handling rules

- Record source type: direct observation, transcript, screenshot, tool result, public reference, or test.
- Record date and context when available.
- Keep the observation separate from interpretation and proposal.
- State what evidence does not establish.
- Link the relevant use case, decision, experiment, or source.
- Do not put confidential personal data, credentials, or private records in this public repository.
