# SA-UX-010 — Project Conversation Discoverability

- **Status:** 🟠 Amber — reconstructed from prior project discussions; overlaps intentionally with SA-UX-001 and SA-UX-002 and should be consolidated if evidence shows it is the same problem.
- **Category:** Navigation / information architecture
- **Related records:** SA-UX-001 — Conversation Identity and Continuity; SA-UX-002 — Project and Folder Organisation; SA-UX-006 — Active Thread Indicator and Long-Press Context Preview.

## Intended outcome

A user can quickly find the conversations and resources belonging to a selected project and understand which work is current.

## Observations reported

The user reported difficulty finding newly created chats associated with a project, uncertainty about whether new chats appeared under the selected project, and confusion between the Project area and Library/folder organisation. They wanted a clear list of project conversations rather than having to search across unrelated recent chats. The precise UI cause may vary by platform and should be verified.

## Impact

Lost time, duplicated conversations, uncertainty about where work is stored, and difficulty resuming a multi-session project.

## Proposed improvement

- Provide a clear, project-scoped conversation list with recent activity and meaningful titles.
- Make project membership visible when creating or moving a conversation.
- Offer search and filtering within the selected project.
- Distinguish conversation organisation from file/library organisation.
- Provide clear feedback when an item is added, moved, or not successfully saved.
- Integrate with the active-thread indicator and non-navigating context preview in SA-UX-006.

## Acceptance criteria

1. Users can locate a specified conversation within a project without searching the entire account.
2. Project membership is visible and consistent across supported devices.
3. Creating or moving a conversation produces truthful confirmation of the result.
4. Users can distinguish chats from files and other project resources.
5. Search results identify the relevant project and recent activity where available.
6. The design avoids creating duplicate records as a workaround for poor discoverability.

## Failure cases

- A conversation appears to belong to a project but is not actually stored there.
- Search returns a thread without enough context to identify it.
- Project and Library folders appear to be interchangeable when they are not.
- A new conversation is created but is not visible where the user expects.

## Evaluation plan

Ask participants to find a named project conversation, determine whether it belongs to the project, and resume the task after a break. Measure time, incorrect selections, duplicate creation, and confidence about location.

## Evidence to reconcile

Link the project-tab versus Library discussions and phone/desktop chat-list observations. Keep the issue connected to SA-UX-001 and SA-UX-002 to prevent duplicate, competing records.
