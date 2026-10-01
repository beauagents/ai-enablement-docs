---
doc_id: foundation.claim-labels
title: Claim Labels
status: scaffold
authority: informative
audience:
  - human
  - ceo-agent
access_scope:
  - foundation
sensitivity: internal
owner: human-principal
version: 0.1.0
created: 2026-10-01
last_reviewed:
review_required: true
supersedes:
---

# Claim Labels

Every substantive statement carries one of these labels when its status is not obvious from context.

| Label | Meaning |
|---|---|
| FACT | Stated by a cited source. A [[Citation-Rules-Human]] chain must resolve. |
| INFERENCE | Derived by the author from facts. The premises are named. |
| RECOMMENDATION | A proposed option with reasons and trade-offs. It is not a decision. |
| UNRESOLVED | A question without enough evidence. It is listed in [[Open-Questions]]. |
| USER DECISION | A decision made by the Human principal. It is recorded in [[Decisions-Register]]. |
| USER REQUIREMENT | A requirement stated by the Human principal. It is recorded in [[Requirements-Register]]. |
| PREVIEW/BETA | The cited capability is pre-GA. This label applies only to provider mappings. |
| UNVERIFIED | A claim that could not be checked against a primary source. |

## Rules

- Researchers do not make architectural decisions. Choices about authority, budget, data placement and risk acceptance belong to the Human principal and the governance chain ([[Change-Authority]]).
- A RECOMMENDATION must name what it trades away.
- Missing evidence is labelled UNVERIFIED. It is never converted into an assumption.
- Promotional or vendor-authored claims are weighted by [[Source-Quality-Classes]].
