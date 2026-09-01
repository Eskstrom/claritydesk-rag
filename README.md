# ClarityDesk RAG

## Product brief

A support assistant that answers questions from an approved knowledge base, shows supporting passages, estimates confidence, and routes unsupported questions to a human review queue.

## Why this belongs in your portfolio

It reflects your deployment and support-operations experience while following the RAG/evaluation pattern visible in strong AI-product portfolios.

## MVP

- Ingest a small public or synthetic documentation set.
- Retrieve source passages and generate cited answers.
- Display unsupported-answer and low-confidence states.
- Create an escalation record with the question, sources considered, and reason.

## Success measures

- Citation coverage for all substantive answers.
- A test set covering answerable, ambiguous, and unsupported questions.
- Clear abstention behavior when evidence is weak.

## Suggested stack

Python, FastAPI, Chroma/pgvector, React or Streamlit, an LLM API.

## Guardrails

No private support data. Keep the demo domain non-medical and non-financial.

## Chat kickoff

“Build ClarityDesk RAG from this brief. Prioritize source grounding, abstention, and a small evaluation set before adding styling.”
