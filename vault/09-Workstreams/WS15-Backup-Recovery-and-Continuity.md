---
doc_id: ws.15
title: WS15: Backup, Recovery and Continuity Models
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

# WS15: Backup, Recovery and Continuity Models

**Status:** scaffold. Research not started. Work arrives as separate commits (see [[Template-Workstream-Commit]]).

## Scope

Define recovery objectives, independent copies, restore testing and continuity under provider failure.

## Key questions

1. How are copies separated by failure domain?
2. How is a one-local-copy requirement met?
3. How are restores tested on a schedule?
4. How are metadata and indexes needed for restore protected?
5. How is continuity maintained if a provider is lost?

## Option families to compare

[RECOMMENDATION: compare all credible options. Do not select.]

- 3-2-1 copies
- Immutable snapshots
- Cross-provider replication
- Cold archive

## Seed sources

- [[SRC-nist-sp800-61]]

These are starting points only. Each workstream must extend the registry ([[Source-Registry]]) with parsed records and archive manifests ([[Citation-Rules-Human]]) before any claim is marked FACT.

## Required outputs

- Recovery objectives framework
- Restore-test criteria
- Continuity scenarios

## Acceptance criteria for this workstream

- Every FACT carries a wikilink to a parsed source record whose archive manifest exists.
- All credible options are listed with advantages, drawbacks and failure modes.
- Decisions required from the Human or governance chain are listed in [[Open-Questions]] and not made here.
- Provider names appear only as evidence inside source records and never in architecture text.
- Related vault notes and AI chunks are updated together ([[AI-Corpus-Overview]]).

Back to [[Workstream-Index]].
