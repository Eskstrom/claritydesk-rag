# ClarityDesk RAG

An AI support assistant that answers product questions from approved documentation, cites its sources, and knows when to hand a conversation to a human.

## Why it exists

Support teams need fast answers without losing customer trust. ClarityDesk is designed around a simple rule: when the knowledge base does not support an answer, it should say so and offer the right next step.

## Planned capabilities

- Ingest and chunk approved support documents
- Retrieve relevant passages for each question
- Generate source-grounded answers with citations
- Detect low-confidence responses and create an escalation record
- Capture feedback for future evaluation

## Architecture

```text
Question → retrieval → grounded response → confidence check → answer or escalation
```

## Roadmap

1. Build a local retrieval pipeline and evaluation dataset.
2. Add a small FastAPI service and a streaming chat interface.
3. Add observability, feedback capture, and review queues.

## Status

Portfolio project in active design. The first milestone focuses on dependable retrieval and transparent citations.