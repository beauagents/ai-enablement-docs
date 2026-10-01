---
doc_id: ws.21
title: WS21: Repository Governance, Review and Supersession
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

# WS21: Repository Governance, Review and Supersession

**Status:** scaffold. Research not started. Work arrives as separate commits (see [[Template-Workstream-Commit]]).

## Scope

Define review, acceptance, supersession and archival rules for the repository itself.

## Key questions

1. How is a document moved from scaffold to accepted?
2. How are signed supersessions recorded?
3. How are commit and review rules enforced?
4. How are source archives versioned?
5. How are provider overlays introduced without changing neutral contracts?

## Option families to compare

[RECOMMENDATION: compare all credible options. Do not select.]

- Branch-per-provider
- Directory-per-provider
- Hybrid
- Separate repository per provider

## Seed sources

- [[SRC-w3c-prov-overview]]
- [[SRC-obsidian-internal-links]]

These are starting points only. Each workstream must extend the registry ([[Source-Registry]]) with parsed records and archive manifests ([[Citation-Rules-Human]]) before any claim is marked FACT.

## Required outputs

- Review workflow
- Supersession records
- Overlay rules

## Acceptance criteria for this workstream

- Every FACT carries a wikilink to a parsed source record whose archive manifest exists.
- All credible options are listed with advantages, drawbacks and failure modes.
- Decisions required from the Human or governance chain are listed in [[Open-Questions]] and not made here.
- Provider names appear only as evidence inside source records and never in architecture text.
- Related vault notes and AI chunks are updated together ([[AI-Corpus-Overview]]).

Back to [[Workstream-Index]].
