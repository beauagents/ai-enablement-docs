---
doc_id: ws.06
title: WS06: Role-Scoped Memory and Information Barriers
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

# WS06: Role-Scoped Memory and Information Barriers

**Status:** scaffold. Research not started. Work arrives as separate commits (see [[Template-Workstream-Commit]]).

## Scope

Design role projections, vocabulary mapping and information barriers over a single canonical record.

## Key questions

1. How are projections defined, and who approves them?
2. How is vocabulary mapped between roles?
3. How is access logged and justified without loading data into context?
4. How are barriers enforced at retrieval time?
5. How is leakage between roles tested?

## Option families to compare

[RECOMMENDATION: compare all credible options. Do not select.]

- Projection by view definitions
- Per-role indexes
- Attribute-based filtering at retrieval
- Separate stores per tier

## Seed sources

- [[SRC-nist-sp800-53]]

These are starting points only. Each workstream must extend the registry ([[Source-Registry]]) with parsed records and archive manifests ([[Citation-Rules-Human]]) before any claim is marked FACT.

## Required outputs

- Projection model
- Vocabulary layer design
- Leakage test criteria

## Acceptance criteria for this workstream

- Every FACT carries a wikilink to a parsed source record whose archive manifest exists.
- All credible options are listed with advantages, drawbacks and failure modes.
- Decisions required from the Human or governance chain are listed in [[Open-Questions]] and not made here.
- Provider names appear only as evidence inside source records and never in architecture text.
- Related vault notes and AI chunks are updated together ([[AI-Corpus-Overview]]).

Back to [[Workstream-Index]].
