---
doc_id: ws.13
title: WS13: Search, Retrieval and Indexing Architecture
status: scaffold
authority: informative
audience:
  - human
  - ceo-agent
access_scope:
  - workstream
sensitivity: internal
owner: human-principal
version: 0.1.0
created: 2026-10-01
last_reviewed:
review_required: true
supersedes:
---

# WS13: Search, Retrieval and Indexing Architecture

**Status:** scaffold. Research not started. Work arrives as separate commits (see [[Template-Workstream-Commit]]).

## Scope

Compare retrieval approaches and index governance, including role filtering before retrieval.

## Key questions

1. How are role and sensitivity filters applied before retrieval?
2. How are chunk sizes and overlaps tested?
3. How do parent-child retrieval patterns behave?
4. How are indexes rebuilt and verified?
5. How are citations preserved through retrieval?

## Option families to compare

[RECOMMENDATION: compare all credible options. Do not select.]

- Keyword search
- Vector search
- Hybrid search
- Graph-based retrieval
- Parent-child chunk retrieval

## Seed sources

- [[SRC-llmstxt-proposal]]

These are starting points only. Each workstream must extend the registry ([[Source-Registry]]) with parsed records and archive manifests ([[Citation-Rules-Human]]) before any claim is marked FACT.

## Required outputs

- Retrieval comparison
- Index governance rules
- Evaluation methods

## Acceptance criteria for this workstream

- Every FACT carries a wikilink to a parsed source record whose archive manifest exists.
- All credible options are listed with advantages, drawbacks and failure modes.
- Decisions required from the Human or governance chain are listed in [[Open-Questions]] and not made here.
- Provider names appear only as evidence inside source records and never in architecture text.
- Related vault notes and AI chunks are updated together ([[AI-Corpus-Overview]]).

Back to [[Workstream-Index]].
