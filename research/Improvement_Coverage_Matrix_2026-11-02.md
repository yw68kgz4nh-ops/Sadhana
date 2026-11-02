# Sadhana — ChatGPT and Claude improvement coverage matrix

**Recorded:** 2026-11-02. **Status:** 🟠 Working audit and prioritisation document.
**Scope:** Mapped **27** current use-case IDs. These IDs represent drafted improvement records; some overlap and are not necessarily 27 independent product defects.

## Coverage by research theme
| Theme | Use-case IDs | What is covered | Evidence / test status |
|---|---|---|---|
| Correct conversation, resumption, preview | 001, 006, 010, 013, 025 | Active project/thread, long-press preview, recent chat list, last confirmed checkpoint and return from search | Reports and proposals; user studies pending |
| Project structure, findability, naming | 002, 003, 016, 018 | Project vs Library vs GitHub, authoritative file paths, renaming, version checks | GitHub file operations confirmed for current work; ChatGPT UI limitations need reproducing |
| Reliable AI execution and feedback | 004, 009, 014, 020, 023, 026 | Capability checks, truthful running state, progress, delay/failure, visual dashboard and optional completion notification | Written specs only; no live task-state integration built |
| Usage/voice/cross-device interruptions | 005, 007, 008, 015, 021 | Read aloud, limits, mic greyed out, phone/PC consistency, warning and recovery | User reports, not a known root cause |
| AI-to-AI document sharing and source control | 011, 017 | Manifest, complete cross-assistant transfer, provenance, critique without lost content | Connector capability depends on authorisation and available products |
| Co-design, preferences and human authority | 012, 022, 027 | Independent critique, human decisions, scope-aware preference reuse | Working principle, not empirical improvement |
| Document workflow and final output | 019, 024 | Invoice/PO validation, approved financial actions and clean final documents | Detailed design briefs; not implemented |

## Consolidation queue — do not blindly delete use cases
1. **001 / 010 / 013 / 025:** keep separate user journeys for identity, project discoverability, session resume and search return, but share one coherent navigation architecture.
2. **002 / 016 / 018:** distinguish location clarity, project hierarchy, and version authority. Cross-link instead of counting the same confusion twice.
3. **007 / 015 / 021:** separate limit-warning UX, task planning, and device-specific disabled-input explanation; use a shared failure-state test matrix.
4. **009 / 014 / 020 / 023 / 026:** one underlying task lifecycle supports status communication, cross-device sync, delay behaviour, dashboard and notifications.
5. **011 / 017:** cross-assistant exchange includes document completeness; likely one product epic with multiple testable use cases.
6. **012 / 022 / 027:** distinguish critique, permission boundaries and preference source/validity.
7. **019 / 024:** separate assisted business-workflow error prevention from status metadata in final outputs.

## What is captured and what is not
**Captured:** the 27 named documents in the [use-case index](../use-cases/README.md), the [floating-island specification](design-specs/Floating_Island_Task_State_UI_v0.1.md), the [invoice/purchase-order wizard design brief](case-studies/Assisted_Invoice_PO_Wizard_Requirements_v0.1.md), and Week 1's actual design-exercise summary.

**Not yet independently established:** prevalence of any ChatGPT or Claude defect; full original conversation excerpts; exact original 13-prompt wording; usable prototypes; test results, university assessment or confirmed product impact. The repository remains public, so project evidence must avoid confidential material.

## Suggested prioritisation for the next study
1. Prototype **wrong-thread prevention and return** (001/006/010/013/025).
2. Test **honest task states** (009/020/023), including no false background continuation.
3. Test **document wizard error handling** (019/022).
4. Compare **cross-device continuity and voice controls** (008/014/021).
5. Evaluate **complete AI-to-AI exchange** with manifest checking (011/017).

**Provenance:** Synthesised from existing GitHub files and project discussion summaries, not a verbatim source-transcript census. Priority reflects risk and relevance, not measured effect size.
