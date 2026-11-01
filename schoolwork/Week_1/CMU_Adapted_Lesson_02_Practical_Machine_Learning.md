# University Sequence Week 1 — Practical Machine Learning
**Source:** Carnegie Mellon University, Human–AI Interaction 05-318/05-618, public Spring 2026 schedule, Lecture 2: Practical Machine Learning.  
**Source scope:** The university schedule confirms this topic and says the lecture introduces basic machine-learning concepts for students from diverse backgrounds. The explanation, examples, exercise and quiz below are our beginner-friendly adaptation, not copied CMU lecture notes.  
**Status:** 🟠 Lesson taught; exercise and recall check awaiting the learner.  
🟨 marks key terms.

## Goal
Explain how a machine-learning system uses examples to produce a useful output, and why people must check how well that output works.

## 1. AI and machine learning
**Artificial intelligence (AI)** is the broad area of building systems that perform tasks associated with intelligent behaviour. **Machine learning (ML)** is one way to build such systems: instead of writing every decision as a fixed rule, developers train a model to find patterns in examples.

A rule-based system might say, “If a filename contains ‘invoice’, put it in Finance.” It follows that written rule. A machine-learning system might examine many examples of files already labelled “Finance” or “Personal” and learn patterns that help it classify new files. This can handle less obvious cases, but it may also make mistakes.

## 2. The learning cycle
- 🟨 **Data:** The examples used to build or test a system.
- 🟨 **Example:** One item in that data, such as a document and its correct category.
- 🟨 **Label:** The answer attached to a training example, such as “Sadhana coursework.”
- 🟨 **Training:** The process of adjusting a model using training examples so it learns patterns.
- 🟨 **Model:** The learned pattern system used to produce outputs.
- 🟨 **Inference:** Using a trained model on a new input to produce an output.
- 🟨 **Prediction:** The model's output, such as a category or next word. It can be wrong.

Imagine using a model to sort project files. You give it examples of documents and their correct folders. It learns patterns associated with each folder. Later, inference means giving it a document it did not train on and asking which folder fits. The output is a prediction; a person may still need to check it.

## 3. Train and test fairly
A model can appear successful if it is tested on the same examples it learned from. A better check uses separate examples it did not see during training.

- 🟨 **Training data** helps the model learn.
- 🟨 **Test data** checks how well the model handles unfamiliar examples.
- 🟨 **Generalisation** means the model works reasonably well on new examples, not only the practice examples.

If the examples are too narrow or contain errors, the model may repeat those problems. If one kind of document is missing, the model may handle it badly. Evaluation should match the real task and include likely difficult cases.

## 4. Three broad learning approaches
- 🟨 **Supervised learning:** Learns from examples paired with labels. Example: documents paired with their correct folder.
- 🟨 **Unsupervised learning:** Looks for patterns or groups without supplied answer labels. Example: clustering similar documents so a person can inspect the groups.
- 🟨 **Reinforcement learning:** Learns by trying actions and receiving rewards or penalties. Example: a simulated agent learning which actions lead to a goal.

These are broad categories. A product may combine methods, and an LLM's training process is more involved than this short overview.

## 5. How this relates to ChatGPT or Claude
When you ask a language model to analyse a document, it uses patterns learned during earlier training together with the text and instructions in the current conversation to generate a response. The document you just supplied is input for that task; that does not by itself mean the model is permanently retraining on it.

The response is generated output, not proof that the document was understood perfectly or that every claim is correct. For important facts, the interface should make it possible to check sources, correct errors, and decide what to keep. A correction in the current conversation can guide the next response, but do not assume it has changed the model's underlying training.

## Worked example: sorting design research
Suppose you want files sorted into “UX learning,” “Sadhana research,” and “business.”
1. Gather representative documents and have a person assign correct categories.
2. Check labels for mistakes and include ambiguous examples.
3. Train a classifier on some examples.
4. Test it on different examples that were not used for training.
5. Inspect errors. If it mishandles philosophy notes or mixed-topic files, improve the examples or let users choose.
6. When used, show the suggested folder and let the person correct it.

The human-centred design question is not only “How accurate is it?” It is also “What happens when it is uncertain or wrong, and can the person recover?”

## Practical exercise
Imagine a tool that suggests folders for six new Sadhana documents. Answer aloud or in writing:
1. What example information might help it make a suggestion?
2. What would count as the correct answer for the training examples?
3. How could you check it on examples it has not seen?
4. What should the interface do when it is unsure?
5. Which final decisions should remain with you?

## Quick quiz
1. In your own words, how does machine learning differ from a fixed written rule?
2. What is the difference between training data and test data?
3. Why is a model's prediction not automatically a verified fact?
4. If a model sorts the training examples correctly but fails on new files, what has not been shown?

## Revision card
**Machine learning:** A way to build systems that learn patterns from examples.  
**Training:** Learning patterns from training examples.  
**Inference:** Applying a trained model to a new input.  
**Prediction:** The output the model proposes; it can be wrong.  
**Test data:** Separate examples used to check performance on unfamiliar cases.  
**Key check:** Does it work on new, realistic examples—and can the user correct it?

## Status and next step
This lesson introduces core terms; it does not establish mastery. The exercise and quiz remain open until the learner responds. Next, use the learner's answers to clarify examples, then continue to the next published course topic at a suitable pace.
