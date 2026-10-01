---
doc_id: ws.17
title: WS17: Cost Governance and Resource Arbitrage
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

# WS17: Cost Governance and Resource Arbitrage

**Status:** scaffold. Research not started. Work arrives as separate commits (see [[Template-Workstream-Commit]]).

## Scope

Specify budgets, anomaly response, acquisition policy and neutral arbitrage rules.

## Key questions

1. How are anomaly thresholds made context-relevant?
2. How are limits tied to circuit breakers?
3. How is the subscription and credit inventory governed?
4. What portability and exit checks apply to a lower-cost route?
5. How are proposals from the CFO role reviewed and signed?

## Option families to compare

[RECOMMENDATION: compare all credible options. Do not select.]

- Budget caps
- Anomaly-based alerting
- Showback and allocation tags
- Acquisition scoring

## Seed sources

- [[SRC-finops-anomaly-management]]
- [[SRC-fowler-circuit-breaker]]

These are starting points only. Each workstream must extend the registry ([[Source-Registry]]) with parsed records and archive manifests ([[Citation-Rules-Human]]) before any claim is marked FACT.

## Required outputs

- Cost control framework
- Acquisition policy options
- Approval thresholds model

## Acceptance criteria for this workstream

- Every FACT carries a wikilink to a parsed source record whose archive manifest exists.
- All credible options are listed with advantages, drawbacks and failure modes.
- Decisions required from the Human or governance chain are listed in [[Open-Questions]] and not made here.
- Provider names appear only as evidence inside source records and never in architecture text.
- Related vault notes and AI chunks are updated together ([[AI-Corpus-Overview]]).

Back to [[Workstream-Index]].
