# SA-UX-004 — Plans Presented as Executable Without Capability Verification

Status: Draft reconstructed from project notes; the user's challenge is documented in the project conversation.

Intended outcome: When the assistant says it will carry out steps, the user can trust that capability and permissions have been checked.

Observed problem: The assistant proposed workflows for editing or organising ChatGPT project resources before verifying that it had the tools or permissions to do them. The user pointed out that this wording implied the plan was executable.

Impact: False expectations, wasted time, unnecessary supervision, reduced confidence, and extra coordination work for the user.

Facts and hypotheses: It was observed that actions were proposed before capability verification. The internal cause of that behaviour has not been established. One plausible contributing factor is that conversational planning language blurs the difference between a proposal and an executable workflow.

Improvement: Check tools and permissions first. Distinguish 'can do now', 'requires authorisation', 'user must act', and 'unverified'. Execute authorised work and verify the result rather than handing routine tasks back to the user.

Test: Compare each execution claim against available tools, permission, actual attempt, and verification. Track false promises, unnecessary user actions, and unverified completion claims.

Related prompts: Prompt 14 — Verified Capability and Honest Execution; Prompt 13 — Problem, Limitation and Solution Capture.