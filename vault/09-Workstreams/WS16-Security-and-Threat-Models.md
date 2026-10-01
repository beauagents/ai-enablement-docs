---
doc_id: ws.16
title: WS16: Security and Agent-Specific Threat Models
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

# WS16: Security and Agent-Specific Threat Models

**Status:** scaffold. Research not started. Work arrives as separate commits (see [[Template-Workstream-Commit]]).

## Scope

Catalogue threats to agentic systems and map them to required controls.

## Key questions

1. What are the top risks to agentic systems, per peer-reviewed guidance?
2. How is goal hijacking mitigated?
3. How is the secret-holding component separated from the networked component?
4. How are inputs from agents, files and messages treated as untrusted?
5. How is the supply chain of tools and models assessed?

## Option families to compare

[RECOMMENDATION: compare all credible options. Do not select.]

- Threat catalogue
- Attack-tree analysis
- Control-to-threat mapping

## Seed sources

- [[SRC-owasp-agentic-top10]]
- [[SRC-nist-sp800-53]]
- [[SRC-nist-sp800-61]]

These are starting points only. Each workstream must extend the registry ([[Source-Registry]]) with parsed records and archive manifests ([[Citation-Rules-Human]]) before any claim is marked FACT.

## Required outputs

- Threat model
- Control mapping
- Red-team scenarios

## Acceptance criteria for this workstream

- Every FACT carries a wikilink to a parsed source record whose archive manifest exists.
- All credible options are listed with advantages, drawbacks and failure modes.
- Decisions required from the Human or governance chain are listed in [[Open-Questions]] and not made here.
- Provider names appear only as evidence inside source records and never in architecture text.
- Related vault notes and AI chunks are updated together ([[AI-Corpus-Overview]]).

Back to [[Workstream-Index]].
