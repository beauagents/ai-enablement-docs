---
doc_id: ws.20
title: WS20: Human-Readable and AI-Chunked Documentation Schemas
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

# WS20: Human-Readable and AI-Chunked Documentation Schemas

**Status:** scaffold. Research not started. Work arrives as separate commits (see [[Template-Workstream-Commit]]).

## Scope

Define the vault schema, chunk schema, metadata, identifiers and machine-readable maps.

## Key questions

1. How are chunk boundaries chosen and tested?
2. How are identifiers kept stable across renames?
3. How are role and sensitivity labels applied?
4. How is the llms.txt map generated and validated?
5. How is divergence between the human and AI views detected?

## Option families to compare

[RECOMMENDATION: compare all credible options. Do not select.]

- Heading-based chunks
- Fixed-size chunks
- Parent-child chunks
- Semantic chunks

## Seed sources

- [[SRC-llmstxt-proposal]]
- [[SRC-obsidian-internal-links]]
- [[SRC-fair-principles]]

These are starting points only. Each workstream must extend the registry ([[Source-Registry]]) with parsed records and archive manifests ([[Citation-Rules-Human]]) before any claim is marked FACT.

## Required outputs

- Schema specifications
- Chunking parameter experiments
- Divergence checks

## Acceptance criteria for this workstream

- Every FACT carries a wikilink to a parsed source record whose archive manifest exists.
- All credible options are listed with advantages, drawbacks and failure modes.
- Decisions required from the Human or governance chain are listed in [[Open-Questions]] and not made here.
- Provider names appear only as evidence inside source records and never in architecture text.
- Related vault notes and AI chunks are updated together ([[AI-Corpus-Overview]]).

Back to [[Workstream-Index]].
