# SA-UX-006 — Active Thread Indicator and Long-Press Context Preview

**Status:** 🟠 Amber — proposed use case; requires design review and testing.  
**Research area:** ChatGPT UI and UX Improvement Research  
**Type:** Navigation, context awareness, interruption recovery, accessibility

## Problem

When a user returns to ChatGPT after leaving the app or switching tasks, it can be unclear which conversation thread is currently active. A list of conversation titles may not give enough context to distinguish similar or ongoing threads. Opening several threads just to identify them can interrupt the current task, create confusion, or risk losing the user's place.

## User proposal

The user proposed two complementary features:

1. **Active-thread indicator:** visually highlight the conversation the user is currently working in, so it is distinguishable from the other thread titles in the navigation list.
2. **Long-press thread preview:** press and hold a thread in the left-hand conversation list for approximately two to three seconds to request a short summary without navigating into that thread. The preview should explain what the conversation is about, the work most recently undertaken, and the last user input or latest update. The user can preview other threads in the same way, then explicitly choose whether to open one.

The long-press duration is an initial proposal, not a fixed requirement; testing should determine whether it is discoverable and comfortable.

## User story

As a person working across multiple ChatGPT conversations, I want to identify my active thread and preview the purpose and latest state of other threads without opening them, so that I can resume the right work without losing my place.

## Proposed interaction

- Clearly distinguish the active thread in the navigation list using more than colour alone where possible (for example, background, icon, text weight, or an accessible label).
- On desktop, provide a discoverable way to preview a thread without navigating away. The user's proposed interaction is a two-to-three-second long press; alternatives such as a context menu or preview control should be considered for discoverability and accessibility.
- On touch devices, support press-and-hold if it does not conflict with platform conventions, with an accessible alternative.
- Show a concise preview containing:
  - thread title and purpose;
  - brief summary of the current work;
  - most recent user message or a faithful summary of it;
  - latest known update and task status, where available;
  - an explicit action to open the thread.
- Previewing must not change the active thread, interrupt ongoing work, or imply that the summary is complete if the thread context is unavailable.
- If the preview cannot be generated, state that clearly rather than displaying invented or stale information.

## Acceptance criteria

1. The active thread is consistently and clearly identifiable in the conversation list.
2. A user can inspect a different thread's preview without switching away from the current thread.
3. The preview accurately describes the thread's purpose and most recent relevant work, with an appropriate timestamp or freshness cue when available.
4. The preview distinguishes the latest user input from an AI response and does not misrepresent either.
5. Closing or dismissing a preview leaves the active thread and its in-progress state unchanged.
6. The user must deliberately select an open action to navigate to the previewed thread.
7. The feature is usable with keyboard, mouse, touch, and assistive technology; long-press is not the only way to access a preview.
8. The active state is not conveyed by colour alone and remains legible in supported themes and display settings.
9. If the summary is unavailable, stale, or fails to load, the UI communicates that state honestly.
10. The feature does not expose conversation content in an unexpected way, and follows the product's existing privacy and content-access rules.

## Failure cases and risks to test

- Similar thread titles make previews hard to distinguish.
- A preview shows stale context or the wrong “last update.”
- Long-press is undiscoverable or triggers accidentally.
- The gesture conflicts with scrolling, text selection, or other platform behaviour.
- A preview obscures ongoing work or interrupts voice interaction.
- The user mistakes a generated summary for the complete conversation.
- The active-thread highlight is subtle, inaccessible, or confused with another status indicator.
- The current thread changes unexpectedly while a preview is open.
- Thread content appears in a preview where the user does not expect it to be visible.

## Evaluation plan

Run moderated usability tests with people managing several active conversations (including a scenario with around twelve threads). Compare the existing experience with a prototype that has an active-thread indicator and non-navigating previews.

Measure:
- time to identify the correct thread;
- number of threads opened unnecessarily;
- wrong-thread selections;
- task interruptions and recovery time;
- summary accuracy against the actual thread;
- users' confidence about which thread is active;
- discoverability and success using mouse, keyboard, and touch;
- accessibility issues and accidental activations.

Test the long-press proposal against at least one alternative preview affordance before choosing an implementation. Define success thresholds before testing rather than selecting them after seeing results.

## Evidence and links to add during reconciliation

- Link the original conversation or journal entry describing this proposal.
- Link any prototype, screenshots, test notes, and decisions.
- Cross-reference research/ChatGPT_UI_UX_Improvement_Research.md.

## Current assessment

This is a concrete user-originated design proposal, not yet a validated product requirement. Preserve the original idea while testing whether the proposed gesture and preview contents solve the problem with the least friction.
