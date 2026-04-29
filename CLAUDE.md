# LLM Wiki Governance

This project is an LLM-maintained Markdown wiki. The human curates sources and directs inquiry; the agent maintains the wiki structure, cross-links, summaries, indexes, and logs.

## Directory Roles

- `raw/sources/` — immutable source documents. Read-only for the agent.
- `raw/assets/` — immutable source assets such as images and screenshots. Read-only for the agent.
- `wiki/` — agent-maintained knowledge layer. The agent may create and update files here.
- `wiki/index.md` — high-level routing map. Keep it short.
- `wiki/log.md` — append-only operation timeline.
- Section indexes such as `wiki/concepts/index.md` and `wiki/sources/index.md` — detailed catalogs for each section.

## Ownership Boundaries

- The human owns source selection, research direction, emphasis, and final judgment.
- The agent owns wiki maintenance: summaries, links, indexing, page updates, consistency checks, and logs.
- The agent must not modify files under `raw/` unless the human explicitly asks.
- The wiki is a compiled, evolving artifact. It may be rewritten to improve clarity, structure, or consistency.

## Retrieval Strategy

Use layered Markdown-native retrieval before adding heavier tooling:

1. Read `wiki/index.md` to choose the relevant section.
2. Read section indexes, such as `wiki/sources/index.md` or `wiki/concepts/index.md`.
3. Use text search over `wiki/` when index navigation is insufficient.
4. Only propose search engines such as qmd, SQLite FTS, or MCP search after the Markdown-native approach becomes insufficient.

Do not rely on one monolithic `wiki/index.md` as the wiki grows.

## Page Frontmatter

Every substantive wiki page should use YAML frontmatter when practical:

```yaml
---
title: Page Title
type: source | concept | entity | synthesis | question | contradiction | index | log
tags: []
sources: []
created: YYYY-MM-DD
updated: YYYY-MM-DD
status: active | draft | superseded | unresolved | resolved
---
```

Use stable page names. Prefer descriptive kebab-case filenames for English terms. Chinese filenames are acceptable for Chinese-first topics. Preserve important aliases inside the page body.

## Ingest Workflow

When the human asks to ingest a source:

1. Read the relevant raw source and any referenced local assets.
2. Identify key claims, entities, concepts, uncertainty, contradictions, and useful quotes.
3. If the source is complex or the emphasis is unclear, discuss takeaways with the human before writing many pages.
4. Create or update a source page in `wiki/sources/`.
5. Create or update relevant concept, entity, synthesis, question, or contradiction pages.
6. Update affected section indexes.
7. Update `wiki/index.md` only if a high-level routing or core-page change is needed.
8. Append an entry to `wiki/log.md` with the operation and changed pages.

## Query Workflow

When answering questions about the wiki:

1. Prefer the wiki layer over raw sources for accumulated knowledge.
2. Use raw sources when verifying claims, resolving uncertainty, or filling gaps.
3. Cite relevant wiki pages and raw sources when making substantive claims.
4. If an answer has durable value, offer to file it under `wiki/questions/` or `wiki/syntheses/`.

## Lint Workflow

Periodically, or when asked, inspect the wiki for:

- orphan pages
- missing section-index entries
- stale or superseded claims
- contradictions between pages or sources
- important concepts without pages
- pages lacking sources or frontmatter
- inconsistent naming or weak cross-links

Prefer small, focused fixes. Record lint operations in `wiki/log.md`.

## Evidence and Uncertainty

- Do not present speculation as fact.
- Important claims should point to a source page, raw source, or explicit uncertainty note.
- Preserve unresolved conflicts instead of smoothing them over.
- If sources disagree, record the disagreement in the relevant page and, when useful, in `wiki/contradictions/`.

## Style

- Write concise Markdown.
- Use Obsidian wikilinks for internal links, such as `[[concepts/llm-wiki|LLM Wiki]]`.
- Keep indexes scannable: path, title, one-line summary, and key tags are usually enough.
- Avoid unnecessary comments or meta-explanations inside wiki pages.
