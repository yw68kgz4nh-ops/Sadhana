# Five Core Terms — How They Work
Date: 2026-11-01
Document status: 🔵 Explanation prepared. Learning status: 🟠 In progress; understanding has not yet been assessed.
Original Sadhana teaching material supporting the introductory Human–AI Interaction topic in CMU's public Spring 2026 course schedule. These five terms and this explanation are our teaching selection, not a claim to reproduce CMU lecture text.
🟨 is a vocabulary reading cue, not a task-status marker.

## 🟨 Human–AI interaction
Human–AI interaction is the study and design of how people understand, use, and work with AI. It includes what happens before, during, and after an AI response.

Start with a person and a goal. You want to improve a paper while retaining its meaning. Next, decide how to divide the work: you supply the purpose, audience, and constraints; AI proposes edits; you judge whether those edits serve the paper. The interface lets you communicate, inspect suggestions, and accept or reject changes.

This division needs care because AI can produce convincing mistakes or misunderstand your intention. A good design gives you ways to check and correct it. For Sadhana, that could mean showing a proposed edit beside the original and letting you accept individual changes.

Efficiency matters, but so do accessibility, appropriate control, and quality. An interface that saves ten seconds but quietly changes your argument has failed your goal. Your preference for speaking rather than typing is part of this design problem, not a minor decoration.

**Design question:** Who does what, and how can the person judge whether the collaboration succeeded?

## 🟨 User control
User control means having meaningful ways to direct the system and intervene. It is more than providing a settings menu.

Control starts before an action: you specify the goal and boundaries. During the action, you may need to stop it or change direction. Afterwards, you may need to inspect, correct, reject, or undo the result. What is possible depends on the system; a button should never promise an action the system cannot perform.

In your naming example, AI can generate five suggested titles while you retain the final choice. It should not silently rename Sadhana when you asked only for suggestions. Conversely, if you clearly authorise a particular rename, repeatedly asking for permission adds friction. Good control respects the scope of your instruction and makes consequences clear.

Choices should also be usable. Forty unexplained settings can leave you with less practical control than three well-explained options. Choosing voice or typing and an available reasoning level are examples of control, but neither guarantees the quality of the eventual answer.

**Design question:** Can the person direct, stop, and recover from the actions that matter?

## 🟨 Transparency
Transparency means making relevant actions, changes, capabilities, and limitations understandable. It answers questions such as: What did the AI change? What evidence supports this claim? What is still uncertain?

Suppose AI improves a paragraph. Transparent feedback might say: “I shortened the opening, retained your main claim, and flagged one citation for checking.” You should be able to inspect the actual changes. A confident explanation alone is not evidence that the edit or save really happened.

For GitHub, “I have drafted the card” and “I saved the card and read it back successfully” describe different states. Naming the saved file and providing its link lets you inspect the result.

Transparency also means being honest about limits. If the system cannot identify why an operation failed, it should not invent a technical explanation. It can state what is known and what you can do next. The aim is useful information, not a flood of technical logs or disclosure of private internal reasoning.

**Design question:** Does the person have the information needed to understand and assess the action?

## 🟨 Predictability
Predictability means helping people anticipate how the system will behave. People build expectations through repeated use: this button submits; this symbol means a problem; requesting suggestions leaves the original intact.

AI-generated wording can vary. Predictability does not require every answer to be identical. The interaction rules should still be dependable: the same kinds of request should respect the same permissions, preserve agreed boundaries, and show consistent status meanings.

Your colour system illustrates this. If blue means finished, blue should not suddenly mean “still working.” Green should mean checked and added only when that has actually happened. Colours need written labels and distinguishable shapes so users can understand them without relying on colour alone.

A countdown also shapes expectations. An unqualified “30 seconds” can feel like a promise. A justified estimate, clearly labelled and updated when needed, gives a more realistic expectation.

**Design question:** What will a person expect, and does the system behave consistently with that expectation?

## 🟨 Visibility of system status
Visibility of system status means giving timely, accurate feedback about what is happening now. It helps answer: Did my request arrive? Is work underway? Is the system waiting for me? Has it finished or failed?

Your expandable status indicator is a good example. It could show “Analysing your document,” expand to explain a delay, then show completion when the result is ready. On failure it should explain the known problem and offer a useful recovery action.

The display must be connected to the real task state. An animation proves only that an animation is running. A meaningful status indicator reflects evidence about the operation. A percentage needs a measurable basis; a time estimate needs a defensible basis. If remaining time cannot be estimated reliably, a truthful status message is better.

Completion should stay understandable until the output appears. For voice users and people who cannot see the indicator, important status changes also need an appropriate accessible announcement.

**Design question:** Can the person tell the current state and what action, if any, they need to take?

## Connecting the five terms
Imagine asking AI for a better Sadhana title. Human–AI interaction defines the partnership: AI suggests and you decide. User control gives you ways to select or reject a suggestion. Transparency identifies what would change and any consequences. Predictability means your existing title remains intact while you are considering suggestions. Visibility of system status tells you whether suggestions are being generated, ready, or unavailable.

These concepts overlap. Status visibility focuses on the current state; transparency also covers changes, evidence, and limitations. Predictability concerns expectations over time. User control concerns what you can decide and do. Human–AI interaction is the wider field in which we design and evaluate the whole relationship.

## Revision links and checkpoint
- [Five-term revision card](Core_Five_Terms_Revision_Card.md)
- [Introductory session record](Session_2026-11-01_Human_AI_Interaction.md)
- [CMU published course schedule](https://haiicmu.github.io/calendar/)
This explanation does not complete Week 1. Next: check understanding through the learner's own examples, then continue practical machine-learning foundations at an appropriate pace.
