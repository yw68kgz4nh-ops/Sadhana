# Sadhana — Design Principle: Philosophical Continuity

**Version:** 0.1  
**Status:** Initial principle for practical testing  
**Purpose:** Explain why Sadhana should express a coherent design philosophy across its documents, working practices, prototypes, and eventual user interface.

## Principle

Sadhana should express a coherent design philosophy across every layer of the system, from its foundational ideas and working documents to its operational processes and user interface. Each element should be designed in relation to the whole, rather than treated as an isolated feature.

This principle is influenced by the idea, associated with absolute idealism, that parts are understood through their relationships within a wider whole. This is a design inspiration, not a claim that Sadhana implements or proves the whole of that philosophical tradition.

## What this means in practice

1. **Continuity across representations.** A concept developed in a document should remain recognisable when it moves into a prototype and later into software. The representation may change, but its purpose and meaning should remain coherent.
2. **Useful human feedback.** Visual conventions should help people understand what has happened, what is happening, and what still needs attention. Feedback should be timely, understandable, and honest.
3. **Evidence before claims.** A polished document or mock-up is not proof that a feature works. Distinguish a written specification, a visual prototype, an implemented feature, and a verified outcome.
4. **One shared meaning.** Common elements—such as task statuses, icons, labels, and interaction patterns—should retain consistent meanings across project documents and the eventual interface.
5. **Learn before scaling.** Use documents and low-fidelity prototypes to test concepts cheaply. Record confusion, accessibility issues, and failures; revise the design in response to evidence.

## Example: the task-status system

The blue-circle, amber-triangle, and red-square status system is an early test of this principle:

- 🔵 **COMPLETE — VERIFIED:** the outcome is finished and checked against the relevant requirement.
- 🟡 **IN PROGRESS / AWAITING VERIFICATION:** work is active, or an outcome exists but has not yet been checked; state which.
- 🔴 **NOT DONE / BLOCKED / FAILED / INTERRUPTED:** the work is not complete; state the specific condition and next action.

The shape and written label accompany the colour so meaning does not depend on colour perception alone. These markers in a document are visual prototypes, not functioning software controls.

See the [Shared Task Status and Colour System](Task_Status_and_Colour_System.md) for operational definitions and pilot tests.

## How we will evaluate it

During the documentation pilot, ask:

- Can people identify task states accurately and quickly?
- Does the design make progress and unfinished work clearer without adding clutter?
- Are the same concepts represented consistently across documents?
- Can people understand the system without relying on colour alone?
- Does a later interface preserve the intent of the document prototype, and does testing support that choice?

Record observations rather than assuming the principle works merely because the design looks consistent.

## Scope and limits

Philosophical coherence is a design aim, not a substitute for usability testing, accessibility checks, technical verification, or user choice. Consistency should not be preserved when evidence shows that a pattern is confusing, unsafe, or inaccessible. The purpose is a coherent and useful experience—not uniformity for its own sake.
