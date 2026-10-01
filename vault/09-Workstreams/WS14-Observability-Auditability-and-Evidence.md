---
doc_id: ws.14
title: WS14: Observability, Auditability and Cryptographic Evidence
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

# WS14: Observability, Auditability and Cryptographic Evidence

**Status:** scaffold. Research not started. Work arrives as separate commits (see [[Template-Workstream-Commit]]).

## Scope

Specify traces, metrics, logs, append-only audit and evidence integrity.

## Key questions

1. What must be audit-grade, and what may be sampled?
2. How is append-only integrity achieved and verified?
3. How is provenance interchanged?
4. How are agent actions attributed?
5. How are evidence retention and legal hold handled?

## Option families to compare

[RECOMMENDATION: compare all credible options. Do not select.]

- Signed append-only log
- Hash-chained records
- Provenance graphs
- Standards-based telemetry

## Seed sources

- [[SRC-opentelemetry-observability-primer]]
- [[SRC-nist-sp800-53]]
- [[SRC-w3c-prov-overview]]

These are starting points only. Each workstream must extend the registry ([[Source-Registry]]) with parsed records and archive manifests ([[Citation-Rules-Human]]) before any claim is marked FACT.

## Required outputs

- Evidence model
- Attribution rules
- Integrity tests

## Acceptance criteria for this workstream

- Every FACT carries a wikilink to a parsed source record whose archive manifest exists.
- All credible options are listed with advantages, drawbacks and failure modes.
- Decisions required from the Human or governance chain are listed in [[Open-Questions]] and not made here.
- Provider names appear only as evidence inside source records and never in architecture text.
- Related vault notes and AI chunks are updated together ([[AI-Corpus-Overview]]).

Back to [[Workstream-Index]].
