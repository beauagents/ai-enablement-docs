---
doc_id: ws.03
title: WS03: Delegation and Signature Authority
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

# WS03: Delegation and Signature Authority

**Status:** scaffold. Research not started. Work arrives as separate commits (see [[Template-Workstream-Commit]]).

## Scope

Model who may approve what, how signatures are produced and verified, and how supersession is recorded.

## Key questions

1. What approval matrices exist in published guidance?
2. How are separation of duties and least privilege expressed as controls?
3. How are signatures produced, verified, revoked and stored?
4. How are temporary waivers and exceptions bounded?
5. How does a cross-team change identify affected authorities?

## Option families to compare

[RECOMMENDATION: compare all credible options. Do not select.]

- Role-based matrix
- Attribute- or relationship-based policy
- Threshold or multi-party signatures
- Delegation tokens with provenance

## Seed sources

- [[SRC-nist-sp800-53]]
- [[SRC-w3c-prov-overview]]

These are starting points only. Each workstream must extend the registry ([[Source-Registry]]) with parsed records and archive manifests ([[Citation-Rules-Human]]) before any claim is marked FACT.

## Required outputs

- Approval matrix options
- Signature and supersession model comparison
- Waiver and exception rules

## Acceptance criteria for this workstream

- Every FACT carries a wikilink to a parsed source record whose archive manifest exists.
- All credible options are listed with advantages, drawbacks and failure modes.
- Decisions required from the Human or governance chain are listed in [[Open-Questions]] and not made here.
- Provider names appear only as evidence inside source records and never in architecture text.
- Related vault notes and AI chunks are updated together ([[AI-Corpus-Overview]]).

Back to [[Workstream-Index]].
