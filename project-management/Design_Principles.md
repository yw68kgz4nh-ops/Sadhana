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


## Philosophical rationale for the three status shapes

The shapes give the status system a memorable visual metaphor. These meanings are Sadhana's chosen design interpretation; they are not universal truths about geometry.

- **Circle — completion as a coherent whole.** A closed, continuous loop can suggest wholeness and continuity: the work is treated as a complete unit. The circle does not prove correctness; the status is blue only after the outcome has been checked against its requirements.
- **Triangle — development towards an aim.** The upward-pointing apex can suggest direction, building, and movement towards a goal. Amber means in progress or awaiting verification, not automatically that progress is good or nearly finished.
- **Square — boundary, stop, or obstacle.** Its firm edges and corners can serve as a metaphor for a constraint or unresolved issue that needs attention. A square is not inherently negative; the red label identifies the actual condition, such as blocked, failed, or not done.

## Psychological rationale for colour

Research finds systematic associations between colours and emotion, but colour associations are not fixed instructions and do not guarantee that a viewer will feel a particular emotion. A 2025 systematic review by Jonauskaite and Mohr synthesised 132 studies involving 42,266 participants across 64 countries. It found recurring associations—for example, blue with lower-arousal positive emotions and red with high-arousal emotions that can be positive or negative. The review also stresses that association does not necessarily mean a colour causes a corresponding feeling in a real situation.

Schloss's 2024 paper, *Color Semantics in Human Cognition*, explains that colour meaning depends on context and on the concepts a viewer brings to an image; associations can sometimes conflict. For Sadhana, this means we should use colour as a quick visual cue, not as the sole carrier of meaning. The explicit status label and distinct shape must reinforce it, and users must be able to understand the status without relying on colour alone.

Our blue, amber, and red mapping is a practical convention inspired by familiar status and warning systems, not a claim that psychology proves these exact colours are best. We should test the mapping with real Sadhana tasks, including whether people interpret it correctly, whether it remains legible for people with colour-vision differences, and whether the symbols and words reduce ambiguity.

### Research references

- Jonauskaite, D., & Mohr, C. (2025). “Do we feel colours? A systematic review of 128 years of psychological research linking colours and emotions.” *Psychonomic Bulletin & Review, 32*, 1457–1486. https://doi.org/10.3758/s13423-024-02615-z
- Schloss, K. B. (2024). “Color Semantics in Human Cognition.” *Current Directions in Psychological Science, 33*(1), 58–67. https://doi.org/10.1177/09637214231208189
