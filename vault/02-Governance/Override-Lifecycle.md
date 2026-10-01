---
doc_id: gov.override-lifecycle
title: Override Lifecycle
status: scaffold
authority: normative-draft
audience:
  - human
  - ceo-agent
access_scope:
  - governance
sensitivity: internal
owner: human-principal
version: 0.1.0
created: 2026-10-01
last_reviewed:
review_required: true
supersedes:
---

# Override Lifecycle

[USER REQUIREMENT] The Human may supersede any rule for the current session. Every override is recorded and classified so it does not silently become permanent or silently vanish.

| Classification | Effect | Required review |
|---|---|---|
| Session override | Applies to the identified session or task. Expires automatically. | Record only |
| Time-limited exception | Applies until a stated date, event or condition. | Human confirms scope and expiry |
| Standing rule change | Updates future behavior at the Human–CEO level. | Human and CEO review and sign off |
| Emergency direction | Takes effect immediately under Human authority. | Retrospective review and classification |
| Revocation | Ends a rule, delegation or exception. | Human authorization at the Human–CEO level |

## Properties

- An override does not require CEO approval to take effect.
- The CEO may state risks and consequences first, then implements the decision.
- The system explains which rules are affected and what follows from the override.
- Overrides and disagreements are recorded without diminishing the Human's standing.
- An ephemeral override that the Human wants kept is reclassified through the standing-change route, not retained by default.

## Open

Precedence when an override conflicts with a safety or legal prohibition that the system cannot lawfully bypass is [UNRESOLVED]. See [[WS02-Constitutional-Governance]].
