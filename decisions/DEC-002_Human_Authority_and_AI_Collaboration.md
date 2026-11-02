# DEC-002 — Human authority and constructive AI collaboration

**Decision record date:** 2026-11-02 (retrospectively documenting earlier Sadhana discussions).  
**Status:** Working design/governance decision captured; requires human review of wording and future usability validation.

## Context
Sadhana treats ChatGPT and Claude as collaborators that can propose, question, and test ideas, but their fluency does not grant them authority to override the person. The project lead explicitly retained decisions over speech versus typing, reasoning-effort preference where available, the substantive narrative of academic papers and meaningful names such as Sadhana. In the invoice example, consequential actions must be explicitly approved.

## Working decision
- **Human retains:** goals, priorities, final name choices, acceptance of substantive text, final design direction, consequential purchases, payments, legal/tax decisions, and permission to send or publish.
- **AI may prepare:** alternatives, analysis, design screens, draft edits, source checks, summaries, explanations, test plans and warnings.
- **AI should challenge:** unsupported claims, weak evidence, interface friction, fragile workflow assumptions, conflicts with agreed project rules, and avoidable manual effort.
- **AI must not silently do:** unauthorised rename, file publication, cross-assistant exchange, customer mailing, purchasing, financial conversion, or covert changes to the owner's argument.
- **Evidence and transparency:** show which suggestions are proposals, which actions were approved, which were executed and which were checked. Never conflate model 'remembering' with a saved GitHub file.
- **Accessibility and learning:** respect user choice of voice/text; define new UX terms and preserve a workable short recap/checkpoint after meaningful lessons.

## Options considered
Passive compliance was rejected as insufficient for strong design. Fully autonomous action without review was rejected as a loss of meaningful human control. A calibrated partnership with explicit boundaries and constructive disagreement is preferred.

## Trade-offs and risks
Excessive approval prompts may burden the person; too few can enable unintended external actions. Use the consequence of the action to choose the required level of approval. Respect prior authorisations only within their actual scope.

## Related records
[SA-UX-012 constructive challenge](../use-cases/SA-UX-012_Constructive_Challenge_and_Review.md) · [SA-UX-022 approval boundaries](../use-cases/SA-UX-022_Human_Approval_and_AI_Autonomy_Boundaries.md) · [SA-UX-027 preference context](../use-cases/SA-UX-027_Preference_Reuse_With_Context_Boundaries.md) · [working philosophy v0.8](../prompts/master/Shared_AI_Working_Philosophy_v0.8.md).

## Revisit when
A user-approved prototype or controlled usability study reveals unacceptable burden, missed consent or inconsistent authority boundaries. This record is governance, not proof that a product enforces these rules.
