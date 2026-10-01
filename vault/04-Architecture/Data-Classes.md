---
doc_id: arch.data-classes
title: Data Classes
status: scaffold
authority: informative
audience:
  - human
  - ceo-agent
access_scope:
  - arch
sensitivity: internal
owner: human-principal
version: 0.1.0
created: 2026-10-01
last_reviewed:
review_required: true
supersedes:
---

# Data Classes

The system distinguishes data by what it is and what may happen to it.

| Class | Meaning |
|---|---|
| Canonical | The authoritative copy of organizational memory, knowledge and records. |
| Derived | Computed from canonical data and rebuildable (for example indexes and projections). |
| Backup | Independent copies held for recovery. |
| Audit | Append-only, attributable records of significant actions. |
| Working | Short-lived worker state that is not authoritative. |
| Approved | Rules, playbooks and decisions that are operationally immutable and changed only by signed supersession. |

## Rules

- [USER REQUIREMENT] The foundation must never lose data.
- [USER REQUIREMENT] Backups follow a 3-2-1 style approach with at least one local copy. Details are to be researched in [[WS15-Backup-Recovery-and-Continuity]].
- [USER DECISION] Sensitivity is classified from the start. Specific regulations are not hard-coded, and sensitive data is not placed anywhere without appropriate agreements. [RECOMMENDATION: enforce by harness, see [[WS08-Policy-Decision-and-Enforcement]]]
- Deletion of canonical data requires the Human's authorization.

Seed source for provenance: [[SRC-w3c-prov-overview]]. Lifecycle research: [[WS12-Data-Knowledge-and-Memory-Lifecycle]].
