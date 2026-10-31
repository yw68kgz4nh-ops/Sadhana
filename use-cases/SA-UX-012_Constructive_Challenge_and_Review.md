# SA-UX-012 — Constructive Challenge and Review

**Status:** AMBER TRIANGLE — draft requirements recorded; evaluation pending.
**Date:** 2026-10-31

## 1. Intended outcome
ChatGPT and Claude help improve proposals through reasoned critique, alternatives, and checks rather than automatic agreement.

## 2. Context and trigger
Trigger: the user or an assistant proposes a design, explanation, or implementation. The user explicitly requested that both assistants question proposals and double-check work.

## 3. Evidence and provenance
Reconstructed from supplied conversation context, particularly the shared working-philosophy discussion. This records a user preference. It does not establish the behaviour of either product or reproduce a complete original transcript.

## 4. Problem and impact
Uncritical agreement can leave weak assumptions and unsupported claims unexamined. Excessive challenge can also interrupt useful work. Both risks need evaluation.

## 5. Preconditions
Identify the goal, constraints, evidence, and decision owner. Check the current master-prompt index before proposing a new master version; this case does not supersede that prompt.

## 6. Main flow
1. Restate the intended outcome briefly when necessary.
2. Identify the strongest relevant objection or uncertainty.
3. Separate verified evidence from assumptions.
4. Offer a practical alternative and its tradeoffs.
5. Recommend an option with reasons.
6. Test the chosen proposal against acceptance criteria.
7. Record the decision and remaining uncertainties.

## 7. Alternatives
Use a short objection for routine reversible choices; a separate reviewer for consequential design decisions when available. A second assistant's agreement is not independent proof.

## 8. Acceptance criteria
- Material objections identify a specific assumption or failure case.
- Challenges connect to the user's goal and include an actionable response.
- Unsupported certainty and invented references are absent.
- The assistant can revise its own proposal when evidence changes.
- Routine authorised work continues without repeated unnecessary confirmation.
- Review does not claim another assistant participated unless its actual contribution is available.

## 9. Failure and recovery
Contrarianism without evidence: remove the unsupported objection.
Circular agreement: seek an external source or observable test.
Missing context: state the uncertainty and obtain only the input needed.
Disagreement unresolved: preserve the alternatives and decision rationale.

## 10. Evaluation plan
Review three sample design proposals containing explicit assumptions. Record whether review identifies the assumptions, gives feasible alternatives, distinguishes evidence from inference, and improves the revised proposal against predeclared criteria. Record user effort as well as quality. No results yet.

## 11. Related records
[Human–AI partnership research](../research/SA-RESEARCH-001_Human_AI_Working_Partnership.md) and [cross-assistant exchange](SA-UX-011_Cross_Assistant_Work_Exchange.md).

## 12. Next action and completion boundary
Pilot on one Sadhana design proposal and retain before/after versions. This document specifies desired behaviour; it does not demonstrate improved model performance.
