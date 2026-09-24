# ClarityDesk RAG

**Status: Concept brief.** The features below are proposed; this repository does not yet contain an implemented application or measured results.

[Portfolio](https://eskstrom.github.io/) · [Related projects](https://eskstrom.github.io/?category=tools-play#library)

## Product brief

A support assistant that answers questions from an approved knowledge base, shows supporting passages, estimates confidence, and routes unsupported questions to a human review queue.

## Design focus

Source-grounded support answers with clarification and escalation paths.

## Proposed scope

- Ingest a small public or synthetic documentation set.
- Retrieve source passages and generate cited answers.
- Display unsupported-answer and low-confidence states.
- Create an escalation record with the question, sources considered, and reason.

## Validation targets

- Citation coverage for all substantive answers.
- A test set covering answerable, ambiguous, and unsupported questions.
- Clear abstention behavior when evidence is weak.

## Potential implementation

Python, FastAPI, Chroma/pgvector, React or Streamlit, an LLM API.

## Guardrails

No private support data. Keep the demo domain non-medical and non-financial.

[Implementation planning notes](notes/IMPLEMENTATION-NOTES.md)

<!-- portfolio-future-plans:start -->
## Future plans and PRD direction

*Planning review: 24 September 2026. These are proposed next steps, not completed work or measured outcomes.*

**Priority recommendation:** Deprioritize; consider retirement only if inactive.

Preserve useful material in the private idea backlog or a future Company Brain roadmap instead of committing to another active product roadmap.

### Next scope

- [ ] Save support-answer evaluation and escalation requirements before any retirement decision.
- [ ] Check current use, unique branches/assets and incoming links before proposing archive or deletion.
- [ ] No deletion is authorized by this note and the repository's current status is unchanged.

### Validation and decision criteria

Reopen a PRD only for a distinct support workflow and evidence that the existing retrieval product cannot serve it. Inactivity has not been established; retaining the repository remains an option.
<!-- portfolio-future-plans:end -->
