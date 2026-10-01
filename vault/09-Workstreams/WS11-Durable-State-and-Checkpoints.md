---
doc_id: ws.11
title: WS11: Durable State and Checkpoint Semantics
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

# WS11: Durable State and Checkpoint Semantics

**Status:** scaffold. Research not started. Work arrives as separate commits (see [[Template-Workstream-Commit]]).

## Scope

Define what must be checkpointed, consistency expectations and idempotency of external effects.

## Key questions

1. What state is needed to resume a task?
2. What consistency does each data class need?
3. How are idempotency keys defined?
4. How is checkpoint integrity verified?
5. How are checkpoints retained and expired?

## Option families to compare

[RECOMMENDATION: compare all credible options. Do not select.]

- Event sourcing
- Snapshot and log
- Transactional state store
- Workflow history replay

## Seed sources

- [[SRC-w3c-prov-overview]]

These are starting points only. Each workstream must extend the registry ([[Source-Registry]]) with parsed records and archive manifests ([[Citation-Rules-Human]]) before any claim is marked FACT.

## Required outputs

- Checkpoint requirements
- Consistency model comparison
- Recovery acceptance tests

## Acceptance criteria for this workstream

- Every FACT carries a wikilink to a parsed source record whose archive manifest exists.
- All credible options are listed with advantages, drawbacks and failure modes.
- Decisions required from the Human or governance chain are listed in [[Open-Questions]] and not made here.
- Provider names appear only as evidence inside source records and never in architecture text.
- Related vault notes and AI chunks are updated together ([[AI-Corpus-Overview]]).

Back to [[Workstream-Index]].
