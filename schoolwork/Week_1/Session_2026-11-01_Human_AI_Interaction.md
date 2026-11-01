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
