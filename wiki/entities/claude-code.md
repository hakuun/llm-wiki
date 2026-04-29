---
title: Claude Code
type: entity
tags: [tool, agent, llm]
sources:
  - wiki/sources/llm-wiki-karpathy-gist.md
created: 2026-04-29
updated: 2026-04-29
status: active
---

# Claude Code

Claude Code is an agentic coding CLI that can maintain files in a local project. In this llm-wiki project, it acts as the wiki maintainer: reading raw sources, writing wiki pages, updating indexes, and appending logs.

## Role in this Wiki

- maintain `wiki/` pages
- follow `CLAUDE.md` governance rules
- preserve `raw/` as immutable unless explicitly instructed
- use layered indexes before heavier search tooling

## Related

- [[concepts/llm-wiki|LLM Wiki]]
- [[sources/llm-wiki-karpathy-gist|LLM Wiki pattern]]
