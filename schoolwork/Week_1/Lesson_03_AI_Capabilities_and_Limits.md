# Lesson 3 — AI Capabilities, Limitations, and Failure Cases

**Estimated time:** 35–45 minutes  
**Lesson status:** 🔴 Not yet taught or assessed  
**Main question:** How do we design responsibly when an AI system can be useful but can also be wrong?

## 1. Learning outcomes

By the end, you should be able to:
- describe a specific AI capability in relation to a task;
- identify realistic limitations and failure cases;
- distinguish an AI output from verified evidence;
- design a sensible next action for the user when an output is wrong or uncertain.

## 2. Begin with the task, not the technology

“AI can summarise text” is a general capability statement. It does not tell us whether a particular summary will preserve the details a learner needs for an assignment.

For every proposed capability, ask:

- What exact input does the system need?
- What output will it produce?
- What would count as a useful result?
- What mistakes are plausible?
- How would the user notice or correct those mistakes?
- What should happen if the system cannot complete the task?

AI systems differ. Do not assume every model has the same strengths, tools, reliability, or limits.

## 3. Four concepts to keep separate

### Capability

Something the system can do under specified conditions—for example, generate a draft summary from supplied text.

### Limitation

A condition that reduces usefulness or reliability—for example, missing context, unreadable source material, or a task that requires information the system does not have.

### Failure case

A specific way the system or workflow can produce an unacceptable outcome—for example, a summary leaves out a critical exception, or the interface makes an unverified answer look final.

### Recovery

The action available to the person when the result is not good enough—for example, inspect the source, edit the draft, provide missing context, undo a change, or use a non-AI method.

A robust design considers recovery before the failure happens.

## 4. Example: document summarisation

| Design question | Example answer |
|---|---|
| Task | Help a learner find the main points in a long document |
| Possible capability | Produce a concise draft summary |
| Limitation | The system may lack the learner's assignment context |
| Failure case | A key qualification is omitted |
| User impact | The learner may misunderstand the source |
| Recovery | Show source passages, label the summary as a draft, allow correction, and encourage checking important claims |
| Evidence needed | Compare the summary with the original and test whether users can find and correct omissions |

This table does not claim that every summary will fail. It makes the risk visible so that the design can be evaluated.

## 5. A small interaction sketch

<pre>
+--------------------------------------+
| DOCUMENT SUMMARY                     |
|                                      |
| AI draft ready                       |
| Main points:                         |
| 1. ...                               |
| 2. ...                               |
|                                      |
| Possible limitation: details may be  |
| missing from this short summary.     |
|                                      |
| [View source] [Edit] [Regenerate]    |
| [Use original document instead]      |
+--------------------------------------+
</pre>

The design gives the person choices. The controls do not guarantee correctness; they provide ways to inspect and recover. A real prototype would need testing to discover whether users notice and understand these options.

## 6. Risk is about more than model accuracy

A failure can arise from:
- the AI producing an incorrect or incomplete result;
- the user providing ambiguous or incomplete input;
- a missing tool, source, permission, or connection;
- a confusing interface;
- an inaccurate status message;
- the workflow not preserving a change;
- the user misunderstanding what the AI has actually done.

Do not assume every failure is caused by the model. Investigate the full human–AI system.

## 7. Practical exercise — create a failure table

Choose one low-risk AI task. Fill in at least two rows.

| Intended task | Possible failure | How the user might be affected | How the user could detect it | Recovery or fallback |
|---|---|---|---|---|
| Example: summarise a document | Important exception omitted | Learner misunderstands a requirement | Compare with source heading or passage | Open source, correct summary, or read original |
| Your task | … | … | … | … |
| Your task | … | … | … | … |

Make the failure specific. “AI makes mistakes” is too general to guide a design.

## 8. Useful wording for uncertainty

Prefer honest descriptions:
- “Draft generated; not yet checked.”
- “I could not verify this against the source.”
- “The supplied information does not answer this question.”
- “This action failed; no change has been confirmed.”
- “Here is what I changed, and here is what remains.”

Avoid unsupported claims such as:
- “Guaranteed correct.”
- “Everything is saved” when no save was verified.
- “The task is finished” when only part of it is complete.

These examples also apply to the way we work on Sadhana itself: status messages should reflect evidence, not intention.

## 9. Exit check

1. What is the difference between a limitation and a failure case?
2. Why should the user have a way to inspect the original source?
3. Name two causes of failure that do not necessarily mean the AI model itself is defective.
4. What is one sensible fallback if the AI cannot complete the task?

### Tutor notes — check after attempting

1. A limitation is a condition that constrains performance; a failure case describes a specific unacceptable outcome in a task or workflow.
2. It helps the user verify important details and detect omissions or misinterpretations.
3. Examples include unclear input, missing context, unavailable tools, confusing UI, or a failed save/sync.
4. Examples include retrying with clarified input, editing the result, asking for help, or using the original non-AI process.

## 10. Revision card

**Front:** What must an AI interaction design specify besides the ideal result?

**Back:** Relevant limitations, plausible failure cases, how the user can detect problems, and a practical recovery or fallback.

## 11. Learning record

Record the attempted task and whether the learner can explain at least two specific failure cases and corresponding recovery actions. Do not equate listing risks with proving the system is safe.
