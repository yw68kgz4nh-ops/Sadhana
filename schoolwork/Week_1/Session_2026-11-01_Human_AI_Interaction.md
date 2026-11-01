# Session Record — 2026-11-01
Status: 🟠 Learning in progress. This is a summary of the supplied conversation transcript, not a verbatim transcript or a completed university assessment.

## Course direction confirmed
Use Carnegie Mellon University's Human–AI Interaction course 05-318/05-618, Spring 2026 public topic order as the academic sequence. Its published first week lists Introduction to Human-AI Interactions and Practical Machine Learning.
- Course site and linked syllabus: https://haiicmu.github.io/
- Teaching schedule read during this session: https://haiicmu.github.io/calendar/
The full linked Google Docs syllabus was not readable through the retrieval tool; the public teaching schedule was verified. Our explanations, exercises and revision cards are original adaptations. The older Sadhana beginner plan remains supplementary and must not be represented as CMU's official syllabus.
UK alternatives were explored, but the learner's final choice was to retain CMU. No UK course switch was agreed.

## Work actually covered
- Introduced human–AI interaction and the division of responsibilities between person, AI, and interface.
- Discussed user control, transparency, predictability, accessibility, trust, workflow, feedback, and visibility of system status.
- Explained model families and reasoning-effort labels as a side discussion.
- Supplied an extended glossary, then selected five recurring terms at the learner's request.
- Practical machine learning has not yet been taught. Week 1 is not complete.

## Learner's contributions (paraphrased)
- Retain choice over speaking or typing, available reasoning effort, and the narrative of a paper.
- AI may suggest titles, but final naming decisions should remain with the human, particularly when the name carries meaning, as Sadhana does.
- Silent renaming can make a file hard to find, confuse revision tracking, and disconnect references within a paper.
- AI should enhance workflow and make effective use of time, without distracting from the work.

## Status-indicator exercise
Task: design feedback for document analysis underway, delayed, completed, or failed.
Learner proposed an amber circular countdown; expansion to an oblong delay message and revised time; blue completion with a green tick; removal after completion and refreshed results; red expansion with a failure explanation.
These are proposed interface behaviours, not implemented software. The proposed amber circle differs from the project's documented amber-triangle convention and needs reconciliation before implementation.

Feedback:
- Label remaining time as an estimate and use it only when supportable. Avoid repeated unsupported countdown resets.
- Retain clear completion feedback until the refreshed result is available.
- In the project convention, blue means finished and green means checked and added; do not imply verification merely because processing ended.
- Explain a known failure accurately and provide an actionable next step; preserve the original request where possible.
- Pair colours with written labels and distinguishable shapes so colour alone does not carry meaning.

## Teaching correction and assessment
The assistant initially ended the introduction too early. This was corrected: the conversation was a short introductory portion, not the end of Week 1.
The learner demonstrated reasoning about human control, findability, traceability, and reference consistency. Their definition emphasised efficiency; teaching broadened it to the study and design of human–AI relationships.
No formal grade, complete recall check, or completion claim is supported.

## Revision and next checkpoint
- [Five Core Terms revision card](Core_Five_Terms_Revision_Card.md)
- Continue with a short recall check of these five concepts and then practical machine-learning foundations at an appropriate pace.
- Retain the learner's preference for visually prominent key terms and voice-friendly explanations.
- Save lesson material, exercises, learner responses, feedback, revision cards, course decisions, and resume checkpoints in Sadhana, with links and read-back confirmation. Memory alone is not evidence of saving.


## Practical Machine Learning — lesson begun
The learner asked to move to the next lesson. Taught a beginner-friendly introduction based on the next published topic in the CMU sequence: practical machine learning. Covered AI vs ML, data/examples/labels, training, models, inference, predictions, train/test separation, generalisation, supervised/unsupervised/reinforcement learning, LLM use of current context, and failure checking. A practical file-sorting exercise and four recall questions were given. The learner has not answered them yet; this lesson and Week 1 remain in progress.

Next checkpoint: discuss the learner's exercise and quiz answers, clarify as needed, then continue the published course sequence. Full lesson: [CMU adapted Lesson 2 — Practical Machine Learning](CMU_Adapted_Lesson_02_Practical_Machine_Learning.md).


## Practical ML — learner's first response
The learner proposed that a system notice repeatedly discussed features and use them in later learning work. Example: the traffic-light status system is documented in a use case and requested repeatedly, so a learning assistant should apply it consistently in new learning materials.

Teaching feedback: repetition can serve as a signal of a preference. In ML language, frequency could be one input feature for a prediction, but it is not proof by itself. A reliable system should also retrieve the authoritative Sadhana instruction, consider which task the preference applies to, and distinguish an explicit standing rule from a pattern it has only inferred. Do not claim that a model has permanently learned a preference just because it appeared in conversation.

The learner has begun the practical exercise; the rest of the exercise and quiz are not yet answered. Week 1 remains in progress. Next: explain how examples, labels, and test data could help evaluate a system that detects and applies recurring design preferences, including how it might wrongly apply an old or context-specific preference.


## ML exercise — status-marker boundaries and human review
The learner gave a useful example of when status markers help: work produced by multiple AI agents needs a marker showing an agent has finished while the learner has not yet reviewed or accepted the work. The learner also said markers hinder a final university paper because they can look childish or distract from the submitted argument; the markers are for the user's working process and should not appear in the final print.

Teaching point: a collaborative workflow should distinguish at least “agent work finished, awaiting human review” from “human reviewed and accepted.” Do not present an agent's completed draft as human-verified. Keep workflow state in an internal project record, separate from the clean final deliverable. The learner described a semantic need; no new colour assignment was agreed here.

This answer advances the practical ML exercise by identifying a context boundary for applying learned preferences. The remaining exercise and quiz are still open.


## ML exercise — learner's proposed test scenario
The learner proposed testing status-marker rules in a coding workflow with three sample states: code still being written, code finished, and code broken. During coding mode the appropriate status marker should appear. After the work is complete, checked, and authorized, markers should not remain in the final code/output. The learner suggested rerunning the scenario during development to ensure the rule continues to be followed.

Teaching feedback: this is a concrete state-based test and identifies both expected display and expected removal. To make it reliable, write the expected result for each state before running it; include a separate “finished but awaiting human review” case; test both working record and final output; and check an example the system did not use when building its own tests. AI-generated tests can help, but an independent expected-results list or human check helps catch shared assumptions. Preserve audit status in the internal record even when omitting markers from the finished deliverable.

Practical ML exercise now includes preference detection and test design. Remaining quiz questions are unanswered; Week 1 remains in progress.


## Learner preference — polish coursework contributions
The learner asked: “polish everything I do,” in response to whether their test plan should be kept as spoken or polished into coursework language. Treat this as a standing preference for coursework and substantive project contributions: preserve their meaning, reasoning, examples, and ownership while presenting a clear, professionally worded version. Do not introduce claims they did not make. Keep the original contribution or faithful paraphrase in the learning record, and explain material edits when useful.

### Polished version of the learner's test-plan idea
“To evaluate this behaviour, I would create a test programme with examples of code at different stages: code still in progress, code completed, and code containing errors. In coding mode, the interface should display the appropriate status marker for each state. After the code has been checked and authorised, the marker should be removed from the final output. I would rerun these test scenarios during development to confirm that the rules continue to work.”

**Teaching refinement:** Include a separate case where the agent has finished its work but the human has not reviewed it. The internal record should distinguish that state from human approval, while the final deliverable remains free of workflow markers.


## Polished test-case refinement — pending learner review
The following expands the learner's test-case idea into acceptance criteria. It is an AI-polished teaching refinement, not a verbatim learner statement or a newly agreed colour assignment.

**Purpose:** Check that workflow markers reflect the real state of coding work, help the user review it, and do not leak into final deliverables.

| Test state | Expected behaviour |
|---|---|
| Code is still being written | Show a clear working state in the coding interface. |
| Agent has finished; human review is pending | Show that agent work is complete but not yet reviewed or approved. |
| Code is broken or a check fails | Show a clear issue state and the available recovery step. |
| Human has checked and authorised the result | Record verification in the internal workflow record; remove temporary workflow markers from the final code or paper. |

Before running the test, write down the expected result for every state. Test the working interface and final deliverable separately. Include a new scenario the test generator did not use, and have the learner or an independent checker compare observed behaviour with the expected results. Keep any audit record needed to explain who reviewed or authorised the work.

The learner has not yet reviewed or approved this expanded wording. The lesson remains in progress.


## Course sequence resumed — Lecture 3: History of AI & HCI
The learner asked to continue with the next syllabus topic. The public CMU Spring 2026 schedule lists Lecture 3 as History of AI & HCI after Practical Machine Learning (with a no-class week in between on the university calendar). Taught an original overview of command-based computing, graphical interfaces, connected systems, machine-learning adaptation, and generative/agentic interaction. Linked the historical shifts to user control and Sadhana file naming. Created a practical exercise and recall questions; learner response is pending. Practical ML exercise and quiz remain incomplete, and no course mastery or completion is claimed. Lesson: [CMU adapted Lecture 3 — A Brief History of AI and HCI](../CMU_Human_AI_Interaction/Lecture_03_History_of_AI_and_HCI.md).


## Teaching preference — define terms before moving on
The learner asked for every new term to be explained before advancing, with a concrete example, as they are starting from no assumed background in AI/HCI. They specifically asked what “hand-written rules,” “AI learning,” and “HCI” mean. Clarification: “hand-written rules” means a programmer explicitly writes rules into software; it does not mean the AI itself is literally written on paper. Subsequent lessons should define each term and give one example before introducing more vocabulary.


## History lesson — spoken continuation
The learner confirmed that the plain-language definitions of AI, HCI, programmer-written rules, machine learning, examples/data, training, model, and prediction made sense, then asked to continue the prior history explanation. Continued with one file-renaming example: command interfaces require a correctly formatted typed instruction; graphical user interfaces show files and controls; HCI evaluates whether the interaction is understandable and recoverable; feedback and undo help confirm or reverse actions; machine-learning suggestions add a guess that should remain inspectable and under the person's control. Explained that these approaches coexist in modern systems rather than cleanly replacing one another. A quick-check question is pending. Lecture 3 remains in progress.


## History lesson — fixed-rule example response
The learner observed that an exact “invoice” search would miss titles such as “bill,” “pro forma invoice,” or “purchase order,” and suggested grouping corresponding terms. They also noted the burden of learning different command syntax, including programming languages.

Polished contribution: “A document-sorting system should account for familiar alternative titles rather than relying on one exact word. However, related terms still need careful classification: a purchase order is connected to an invoice workflow but is not itself an invoice. If the category is uncertain, the system should show a reviewable suggestion instead of silently filing it.”

Teaching feedback: a fixed rule can include manually specified alternate words, but it will not automatically cover every new phrase. “Command interface” means entering system-specific commands; it does not necessarily mean writing Python or C++ code. The assistant clarified this distinction. Next question—whether to auto-file or ask for confirmation on “purchase order”—is pending.


## Learner proposal — guided purchasing workflow
The learner proposed an on-screen wizard that asks for the company, work description, and amount, then generates a document, emails it, saves a copy in the correct folder, and tracks a ten-day deadline. If unresolved after ten days, the system should surface the item with a reminder.

Teaching feedback: this demonstrates workflow design and automation. Clarify the document before implementation: a buyer normally creates a purchase order; a supplier normally creates a pro forma invoice. Define what the deadline means and what evidence counts as resolved, so a reminder does not incorrectly report non-completion. Explicit form fields, templates, filing rules, and date comparisons can operate without machine learning; AI could help interpret descriptions or suggest categories. The proposed sending and reminder behavior is a design scenario, not an instruction to send email or schedule a live automation. Proposal remains unimplemented.


## Next teaching step — rules versus machine learning in the wizard
Use the learner's purchasing wizard to distinguish fixed rules (copying entered company/amount into a template, saving in a specified folder, comparing a recorded deadline with today's date) from possible machine-learning tasks (interpreting a free-text work description and suggesting a category from learned examples). Automation does not inherently require AI. A suggestion may be wrong and should remain reviewable. Check question: does adding ten days to a date require learning from examples, or a fixed instruction? Learner response pending; deadline completion criteria remain open.


## Learner example — hard-drive replacement quotation workflow
The learner proposed entering “hard drive change,” then using similar past jobs to draft the work description, costs, steps, and expected duration. Entering a customer name such as John Smith could retrieve the customer's saved email address, with emailing as a later workflow step. The learner's final sentence about the email recipient was unfinished.
Teaching feedback: distinguish retrieval of saved records, prediction/estimation from examples, and explicit automation rules. Reusing one past job or looking up a contact does not necessarily train a model. Costs and duration depend on the specific computer, drive, and work required, so suggested values should be reviewable estimates. A name may match multiple contacts. The original fixed-rule check remains: adding ten days follows an explicit instruction and does not require machine learning. No live email or automation was requested or performed.


## Next learning section — uncertainty in AI estimates
Continued the current explanation with uncertainty, using the hard-drive replacement workflow. Uncertainty means the system lacks enough information to be sure. A prediction is an estimate based on patterns, not a confirmed outcome. A previous job taking one hour does not establish this job's duration; relevant missing facts may include the computer, drive, data transfer, and fault condition. The interface should distinguish saved facts from estimates, explain the basis and missing information in plain language, and permit correction before consequential use. Do not invent confidence percentages. Check question: before estimating the new job's duration, what one piece of information should the assistant ask for? Learner response pending. This is a continuation of our adapted lesson, not a claim about the next official CMU syllabus heading.


## Uncertainty exercise — parts availability
The learner proposed asking whether all required parts are available before estimating completion. Missing parts increase the elapsed time; they proposed an assistant sourcing, purchasing, and arranging delivery. Teaching feedback: distinguish hands-on repair time from overall completion time, including procurement and delivery. A dependency is something that must be available or completed before another task can proceed. The assistant should check compatibility, stock, price, and estimated delivery; purchasing requires agreed authority such as approval or a pre-authorised budget and supplier policy. Supplier delivery estimates should not be presented as guarantees. This is a proposed design scenario; no search, purchase, or delivery was initiated.


## Quick quiz begun
Learner agreed to a quick quiz. Plan: three short questions, one at a time, with spoken answers accepted. Question 1: the assistant finds John Smith's email address in an existing customer record. Is this retrieval, prediction, model training, or uncertainty? Expected answer: retrieval, because the address is looked up from an existing record. Learner answer pending; no score assigned.


## Quick quiz — responses and next question
Q1: learner answered “retrieval”; correct by concept, regardless of the preceding spoken “A.” Q2: adding ten days to a date; learner answered “uncertainty.” Correction: this calculation is a fixed rule; uncertainty concerns an unknown outcome such as whether a part will arrive by the deadline. Q3 pending: before a purchase not already authorised, should the assistant show the component, total cost, and delivery estimate and ask for confirmation? Assesses user control. Quiz is still in progress; Q1 correct and Q2 needs reinforcement.


## Quiz Q2 — second attempt and clarification
Learner revised the answer to “prediction.” Clarified: adding ten days to a given date is a fixed-rule calculation; estimating that a supplier will deliver in ten days is a prediction; uncertainty concerns whether that estimate will hold. Q2 still needs reinforcement. Pause before Q3 and use this distinction without introducing another quiz question.


## Quick quiz — completed spoken version
The actual final question asked in the spoken transcript was: “If AI says the part will arrive in three days, is that a fixed rule, retrieval, prediction, or user control?” This supersedes the previously planned purchasing-confirmation question, which was not administered. Learner answered “prediction because it might not come in three days.” Correct for the intended delivery-estimate scenario. Feedback: prediction estimates an unknown outcome; uncertainty describes how unsure that estimate is. If simply quoting a supplier's stored estimate, fetching that estimate would be retrieval, while the estimate itself remains a prediction. Final outcome: 2 of 3 initial answers correct (retrieval and prediction); fixed-rule date calculation needs reinforcement. This mini-quiz completion does not establish course or Week 1 completion.


## Next topic begun — guidelines for human–AI interaction
After the completed mini-quiz, the learner explicitly asked to move on and agreed to continue. Began an original beginner explanation of the next topic already identified in the adapted course sequence: guidelines for human–AI interaction. A guideline is a practical principle for design. First focus: set clear expectations before use. Capability means what a system can do; limitation means where it cannot reliably perform or lacks information/access. Invoice example: explain that the assistant can draft from saved customer/job records and suggest costs, that suggested costs/delivery need checking, and that sending or purchasing follows the user's agreed authority. Show proposed actions clearly before consequential execution. This is an original teaching adaptation, not a verbatim CMU lecture. Exercise: what should the assistant say at the start so the user understands what it can do and what needs review? Learner response pending.


## Guidelines exercise — calculation and authorisation boundaries
Learner proposed applying appropriate VAT/tax settings and a recorded 10% customer discount. They specified that the assistant must not invent or alter legally applicable tax rules, convert a pro forma to an issued invoice, or make a payment without human interaction. Teaching distinction: capability describes what software can perform; permission/authorisation describes what it is allowed to perform. The invoice/payment restrictions are the learner's chosen workflow controls, not universal claims that software is technically unable to automate these actions. Tax calculation must use verified, applicable rules and current configuration rather than an AI-guessed rate; no rate or tax advice was provided. Polished opening: the wizard can apply verified tax settings and recorded customer discounts, and prepares a draft; issuing an invoice or making a payment requires the user's approval. Student demonstrated useful control boundaries; still distinguish technical limitations from permission boundaries.


## Guidelines continuation — easy correction
Learner requested the next guideline. Presented an original explanation of making mistakes easy to correct: if the wizard uses a saved 10% discount but the user says this particular job has no discount, allow the user to edit that field, recalculate the draft, and see confirmation. Explain scope: changing one invoice should not silently update the customer's permanent discount setting. Define error recovery as helping a person get back to the intended task after an error. Exercise pending: for “no discount on this job,” should the change affect the current draft or all future invoices? No new official CMU guideline number or quotation is claimed.


## Learner design — red-square discount correction
Learner proposed a red square next to a problematic discount. Attempting to save would take the user back to that field and prevent completion. Selecting it would offer the customer's current recorded discount (example 20%); accepting removes the marker, allowing email sending.
Teaching feedback: strong localisation of an issue and actionable recovery using the established red-square meaning. Pair colour/shape with a specific written explanation of the detected discrepancy. Refine by preserving the draft and blocking issuing/sending rather than preventing all saving. A difference from the customer record is not automatically an error; allow an explicitly authorised exception. On choosing the saved discount, update totals, recheck, and remove the error only if resolved. Correction makes the invoice ready for review/sending; do not silently send solely because the marker disappeared. Proposal only, not implementation.


## Learner proposal — digital sticky note for contextual correction
Learner observed that written computer messages often fail to make clear what happened. Proposed a digital sticky note beside the affected element, containing a brief explanation and a button offering an amendment; after successful amendment, the note disappears.
Polished design: display an anchored contextual message next to the affected field. State the detected issue and proposed correction. Use a specific action label (for example, “Use saved 20% discount”) so its effect is known before selection. On success, update the field and dependent totals, briefly confirm what changed, and dismiss the error note. On failure, retain the note and explain the next action. Preserve the draft, avoid covering relevant content, and retain the existing red-square plus text convention. This exemplifies contextual feedback (information placed where it is relevant) and actionable error recovery. It is a design proposal; no prototype has been implemented and no novelty claim is made.


## Learner proposal — customer-folder mismatch warning
Learner proposed warning when an invoice appears to be filed under the wrong customer (example AC Supplies). The person can continue if intentional, or decline and have the assistant find the appropriate destination. Teaching feedback: show the evidence for the mismatch, describe the invoice rather than calling the folder misplaced, offer explicit “Keep here” and “Choose suggested folder” actions. A pre-move warning is error prevention; after a move, offer undo or a reviewed move to the correct folder as recovery. Suggested destinations remain suggestions and should be confirmed; if ambiguous, ask instead of silently moving. Do not warn on every action, only meaningful detected mismatches. Proposal not implemented.


## System-status response and requested transition
Learner explained that absent feedback during background work leaves users unable to tell whether the system is working. They began exploring a distinctive, easy-to-use activity indicator, then explicitly requested the next lesson before selecting a design. No new visual design was agreed. Do not treat their recalled vendor animations as verified facts.

## Guidelines continuation — proportionate interruptions
Continued with choosing when to interrupt the user. Notification means a message drawing attention to an event. Routine progress (checking folders) can remain visible beside the task without blocking unrelated work. A consequential action requiring a decision (sending to a possibly wrong recipient) should pause that action and ask for a clear choice. An important event can require attention without blocking the whole application. Exercise pending: should successful background saving require dismissing a pop-up every time, or a brief visible saved message? This is an original teaching continuation, not a claimed numbered official guideline.


## Explaining a recommendation — terminology clarification
Learner skipped the notification question. Assistant introduced “sharing reasoning” too vaguely and asked why a 10% discount was suggested. Learner offered cracked office pipes causing a leaking toilet. Treat this as a classroom example, not a report of a real plumbing incident. Teaching clarification: their example connects a problem to a cause; the interface lesson concerns explaining the evidence or rule behind a recommendation. Better term: explaining a recommendation. Example: “Suggested 10% because this customer's saved record lists a 10% discount,” only if actually supported by the record. For their example: “Suggested urgent repair because you reported an active leak.” Explain the basis accurately without inventing a cause or claiming access to hidden internal reasoning. No learner error score assigned.
