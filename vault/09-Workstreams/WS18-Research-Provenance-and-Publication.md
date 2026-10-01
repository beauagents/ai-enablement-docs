---
doc_id: ws.18
title: WS18: Research Provenance and Publication Pipeline
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

# WS18: Research Provenance and Publication Pipeline

**Status:** scaffold. Research not started. Work arrives as separate commits (see [[Template-Workstream-Commit]]).

## Scope

Define provenance, authorship rules, disclosure and the Human-authorized publication path.

## Key questions

1. What do publication ethics bodies require about AI contribution?
2. How are contributions recorded?
3. How are novelty and prior art checked?
4. How are findability and reuse supported?
5. How are rights and confidentiality checked before release?

## Option families to compare

[RECOMMENDATION: compare all credible options. Do not select.]

- Repository paper
- Preprint
- Dataset or benchmark release
- Journal or conference submission

## Seed sources

- [[SRC-cope-ai-authorship]]
- [[SRC-niso-credit]]
- [[SRC-fair-principles]]
- [[SRC-w3c-prov-overview]]

These are starting points only. Each workstream must extend the registry ([[Source-Registry]]) with parsed records and archive manifests ([[Citation-Rules-Human]]) before any claim is marked FACT.

## Required outputs

- Pipeline gates
- Contribution record model
- Disclosure rules

## Acceptance criteria for this workstream

- Every FACT carries a wikilink to a parsed source record whose archive manifest exists.
- All credible options are listed with advantages, drawbacks and failure modes.
- Decisions required from the Human or governance chain are listed in [[Open-Questions]] and not made here.
- Provider names appear only as evidence inside source records and never in architecture text.
- Related vault notes and AI chunks are updated together ([[AI-Corpus-Overview]]).

Back to [[Workstream-Index]].
