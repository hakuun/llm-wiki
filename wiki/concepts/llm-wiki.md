---
title: LLM Wiki
type: concept
tags: [llm-wiki, knowledge-management, markdown, agent-workflow]
sources:
  - wiki/sources/llm-wiki-karpathy-gist.md
created: 2026-04-29
updated: 2026-04-29
status: active
---

# LLM Wiki

An LLM Wiki is a persistent, agent-maintained Markdown knowledge base built from curated raw sources. Instead of retrieving raw chunks from scratch for every question, the agent incrementally compiles sources into structured pages, cross-links, summaries, contradictions, and syntheses.

## Core Model

- The human curates sources, asks questions, guides emphasis, and makes final judgments.
- The agent reads sources, updates pages, maintains links, records logs, and checks consistency.
- Raw sources stay immutable.
- The wiki evolves as a compiled knowledge layer.
- The schema, such as `CLAUDE.md`, defines how the agent should behave.

## Difference from RAG

RAG usually retrieves source chunks at query time. An LLM Wiki instead preserves prior synthesis as durable Markdown pages. This makes knowledge compound across ingests, queries, and lint passes.

## Core Operations

- **Ingest** — incorporate new raw sources into the wiki.
- **Query** — answer from accumulated pages, then optionally file durable answers.
- **Lint** — inspect the wiki for quality, consistency, gaps, and stale claims.

## This Project's Interpretation

This project uses a layered Markdown-native retrieval structure:

- `wiki/index.md` as the high-level routing map
- section indexes for sources, concepts, entities, syntheses, questions, and contradictions
- frontmatter on substantive pages
- `wiki/log.md` as the operation timeline

This avoids depending on a single monolithic index while postponing heavier search infrastructure until it is actually needed.

## Related

- [[concepts/compounding-knowledge-artifact|Compounding knowledge artifact]]
- [[concepts/wiki-linting|Wiki linting]]
- [[sources/llm-wiki-karpathy-gist|LLM Wiki pattern]]
