---
title: LLM Wiki pattern
type: source
tags: [llm-wiki, knowledge-management, markdown, obsidian, agent-maintained-wiki]
sources:
  - raw/sources/llm-wiki.md
  - raw/assets/llm_wiki_arch.jpg
created: 2026-04-29
updated: 2026-04-29
status: active
---

# LLM Wiki pattern

Source summary for `raw/sources/llm-wiki.md` and its architecture diagram `raw/assets/llm_wiki_arch.jpg`.

## Summary

The source proposes an LLM-maintained personal or team knowledge base where raw materials are not merely retrieved at query time. Instead, an agent incrementally compiles them into a persistent, interlinked Markdown wiki. The wiki becomes a compounding artifact: summaries, entities, concepts, contradictions, and syntheses are maintained over time instead of rediscovered from scratch.

## Key Claims

- Traditional RAG retrieves chunks at query time but does not naturally accumulate synthesis across sessions.
- An LLM wiki adds a maintained knowledge layer between raw sources and user queries.
- The human should curate sources, direct inquiry, and judge emphasis.
- The LLM should handle summarization, filing, cross-linking, consistency maintenance, and bookkeeping.
- `index.md` and `log.md` are core navigation and provenance files.
- Periodic linting keeps the wiki healthy by finding contradictions, stale claims, orphan pages, missing links, and research gaps.
- The approach works because LLMs can cheaply perform the maintenance work that usually causes human-maintained wikis to decay.

## Architecture

The architecture has three layers:

1. **Raw sources** — immutable source documents and assets; the source of truth.
2. **Wiki** — LLM-generated Markdown pages containing summaries, concepts, entities, comparisons, questions, and syntheses.
3. **Schema** — an agent instruction file such as `CLAUDE.md` that defines structure, conventions, and workflows.

The architecture diagram emphasizes the same design: source ingestion flows through LLM analysis and human discussion, then updates multiple wiki pages, indexes, and logs.

## Operations

### Ingest

A new source is read, summarized, discussed if needed, and integrated into the wiki. One source may update many pages.

### Query

Questions are answered against the accumulated wiki. Valuable answers can themselves become new durable pages.

### Lint

The agent periodically checks for contradictions, stale claims, missing concepts, orphan pages, missing cross-references, and research gaps.

## Relevant Concepts

- [[concepts/llm-wiki|LLM Wiki]]
- [[concepts/compounding-knowledge-artifact|Compounding knowledge artifact]]
- [[concepts/wiki-linting|Wiki linting]]

## Relevant Entities

- [[entities/obsidian|Obsidian]]
- [[entities/claude-code|Claude Code]]

## Limitations and Open Questions

- The source is intentionally abstract and does not prescribe a concrete directory structure.
- It suggests `index.md` is enough at moderate scale, but larger wikis may require section indexes or local search.
- It does not define detailed governance for human approval, conflict resolution, or page lifecycle.

## Useful Quote

> Obsidian is the IDE; the LLM is the programmer; the wiki is the codebase.
