---
doc_id: ws.01
title: WS01: Layer Taxonomy and Boundaries
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

# WS01: Layer Taxonomy and Boundaries

**Status:** scaffold. Research not started. Work arrives as separate commits (see [[Template-Workstream-Commit]]).

## Scope

Define the capability layers, their boundaries, trust zones and contracts, using generic names only.

## Key questions

1. Which layers are necessary, and which are optional?
2. Where are the trust boundaries between layers?
3. Which data class does each layer hold?
4. What is the minimum contract each layer exposes to the others?
5. How does the taxonomy map to widely understood, non-branded terminology?

## Option families to compare

[RECOMMENDATION: compare all credible options. Do not select.]

- Flat capability list
- Layered stack
- Plane-based model (control, data, execution)
- Domain-driven boundaries

## Seed sources

- [[SRC-owasp-agentic-top10]]
- [[SRC-nist-ai-rmf]]

These are starting points only. Each workstream must extend the registry ([[Source-Registry]]) with parsed records and archive manifests ([[Citation-Rules-Human]]) before any claim is marked FACT.

## Required outputs

- Final taxonomy
- Per-layer responsibility and failure-mode notes
- Boundary and contract diagrams (Mermaid)

## Acceptance criteria for this workstream

- Every FACT carries a wikilink to a parsed source record whose archive manifest exists.
- All credible options are listed with advantages, drawbacks and failure modes.
- Decisions required from the Human or governance chain are listed in [[Open-Questions]] and not made here.
- Provider names appear only as evidence inside source records and never in architecture text.
- Related vault notes and AI chunks are updated together ([[AI-Corpus-Overview]]).

Back to [[Workstream-Index]].
