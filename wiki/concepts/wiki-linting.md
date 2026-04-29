---
title: Wiki linting
type: concept
tags: [wiki-maintenance, quality-control, llm-wiki]
sources:
  - wiki/sources/llm-wiki-karpathy-gist.md
created: 2026-04-29
updated: 2026-04-29
status: active
---

# Wiki linting

Wiki linting is the periodic maintenance process where the agent checks the wiki for quality, consistency, and navigability problems.

## Checks

- contradictions between pages or sources
- stale claims superseded by newer sources
- orphan pages with no inbound links
- missing cross-references
- important concepts that lack pages
- pages missing sources or frontmatter
- unclear naming or duplicate concepts

## Output

A lint pass may produce direct fixes, open questions, contradiction records, or a prioritized maintenance list.

## Related

- [[concepts/llm-wiki|LLM Wiki]]
- [[sources/llm-wiki-karpathy-gist|LLM Wiki pattern]]
