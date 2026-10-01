---
doc_id: ws.08
title: WS08: Policy Decision and Enforcement Architecture
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

# WS08: Policy Decision and Enforcement Architecture

**Status:** scaffold. Research not started. Work arrives as separate commits (see [[Template-Workstream-Commit]]).

## Scope

Define where policy is decided and enforced so that rules bind agents structurally and not only through prompts.

## Key questions

1. Where are the decision and enforcement points?
2. How are rules expressed so they can be tested?
3. How is call-time authorization checked?
4. How are policies versioned and superseded?
5. How is bypass attempted and detected?

## Option families to compare

[RECOMMENDATION: compare all credible options. Do not select.]

- Central decision with distributed enforcement
- Embedded policy libraries
- Gateway-only enforcement
- Layered enforcement

## Seed sources

- [[SRC-owasp-agentic-top10]]
- [[SRC-nist-sp800-53]]

These are starting points only. Each workstream must extend the registry ([[Source-Registry]]) with parsed records and archive manifests ([[Citation-Rules-Human]]) before any claim is marked FACT.

## Required outputs

- Enforcement point map
- Policy expression options
- Conformance tests

## Acceptance criteria for this workstream

- Every FACT carries a wikilink to a parsed source record whose archive manifest exists.
- All credible options are listed with advantages, drawbacks and failure modes.
- Decisions required from the Human or governance chain are listed in [[Open-Questions]] and not made here.
- Provider names appear only as evidence inside source records and never in architecture text.
- Related vault notes and AI chunks are updated together ([[AI-Corpus-Overview]]).

Back to [[Workstream-Index]].
