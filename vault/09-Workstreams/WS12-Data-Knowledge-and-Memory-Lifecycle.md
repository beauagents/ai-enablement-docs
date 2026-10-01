---
doc_id: ws.12
title: WS12: Data, Knowledge and Memory Lifecycle
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

# WS12: Data, Knowledge and Memory Lifecycle

**Status:** scaffold. Research not started. Work arrives as separate commits (see [[Template-Workstream-Commit]]).

## Scope

Cover creation, promotion, retention, deletion, provenance and memory-poisoning defenses.

## Key questions

1. How does working memory become approved knowledge?
2. How are retention and deletion rules expressed?
3. How is provenance attached and preserved?
4. How is poisoning of memory and retrieval detected?
5. How are derived data rebuilt from canonical data?

## Option families to compare

[RECOMMENDATION: compare all credible options. Do not select.]

- Tiered memory
- Event-sourced knowledge
- Curated knowledge base with review gate

## Seed sources

- [[SRC-w3c-prov-overview]]
- [[SRC-fair-principles]]

These are starting points only. Each workstream must extend the registry ([[Source-Registry]]) with parsed records and archive manifests ([[Citation-Rules-Human]]) before any claim is marked FACT.

## Required outputs

- Lifecycle model
- Promotion rules
- Poisoning defenses

## Acceptance criteria for this workstream

- Every FACT carries a wikilink to a parsed source record whose archive manifest exists.
- All credible options are listed with advantages, drawbacks and failure modes.
- Decisions required from the Human or governance chain are listed in [[Open-Questions]] and not made here.
- Provider names appear only as evidence inside source records and never in architecture text.
- Related vault notes and AI chunks are updated together ([[AI-Corpus-Overview]]).

Back to [[Workstream-Index]].
