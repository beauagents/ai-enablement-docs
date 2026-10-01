---
doc_id: resource.cost-governance
title: Cost Governance
status: scaffold
authority: informative
audience:
  - human
  - ceo-agent
access_scope:
  - resource
sensitivity: internal
owner: human-principal
version: 0.1.0
created: 2026-10-01
last_reviewed:
review_required: true
supersedes:
---

# Cost Governance

[USER REQUIREMENT] Limits may sit above standard levels with cost in mind, and the system must never break silently. A budget range is a Human decision recorded in [[Decisions-Register]].

## Roles

- The CFO role proposes spending. Proposals include alternatives and risks.
- The CEO and the Human sign off on proposals ([[Change-Authority]]).
- A proposal for a paid capability follows the [[Resource-Acquisition-Policy]].

## Controls to specify

- Budgets and rate limits per role, team and task.
- Concurrency and spend-rate limits tied to circuit breakers.
- Loud alerts on approach to and breach of any limit.
- Anomaly detection against baselines ([[Emergency-Materiality]]).
- Temporary overrun authority for the CEO in emergencies ([[Emergency-Authority]]).

## Sources

[[SRC-finops-anomaly-management]], [[SRC-fowler-circuit-breaker]]. Detailed research: [[WS17-Cost-Governance-and-Resource-Arbitrage]].
