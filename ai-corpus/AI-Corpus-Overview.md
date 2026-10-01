---
doc_id: corpus.overview
title: AI Corpus Overview
status: scaffold
authority: informative
audience:
  - human
  - ceo-agent
access_scope:
  - corpus
sensitivity: internal
owner: human-principal
version: 0.1.0
created: 2026-10-01
last_reviewed:
review_required: true
supersedes:
---

# AI Corpus Overview

The AI corpus is a set of small Markdown chunks projected from the vault. It carries no separate facts. The vault notes are authoritative.

## Design

- Chunks follow Markdown headings, not arbitrary token counts. Each chunk keeps the wikilinks and source identifiers of its parent section.
- Each chunk links to its parent note and heading.
- Each chunk records a hash of its parent section. A mismatch with the current section signals divergence ([[Chunk-Schema]]).
- Role and sensitivity labels allow filtering before retrieval ([[Retrieval-Rules]]).
- Chunk size and overlap are parameters to test ([[WS20-Documentation-Schemas]]).
- Machine-readable maps: `llms.txt` at the repository root and [[Chunk-Index]].

## Labels in this scaffold

[UNRESOLVED] Role audiences and access scopes on chunks are provisional. They are defined properly in [[WS06-Role-Scoped-Memory]]. Workers receive no chunks by default.

## Convention note

[FACT] `llms.txt` is a proposal for a Markdown file giving concise background and links to LLM-friendly content ([[SRC-llmstxt-proposal]]). An expanded full-text variant is a community convention and is not part of the core proposal. If one is produced it will be labelled as such.
