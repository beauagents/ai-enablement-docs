---
chunk_id: arch-data-classes-001
parent_document: vault/04-Architecture/Data-Classes.md
heading_path: Data Classes > Rules
document_version: 0.1.0
status: scaffold
authority: informative
audience:
  - ceo-agent
  - cto-agent
access_scope:
  - arch
sensitivity: internal
labels_status: provisional
source_ids:
  - SRC-w3c-prov-overview
parent_section_hash: 1e6b77f88607dda8
effective_date:
supersedes:
review_required: true
---

Parent: [[Data-Classes#Rules]]

- [USER REQUIREMENT] The foundation must never lose data.
- [USER REQUIREMENT] Backups follow a 3-2-1 style approach with at least one local copy. Details are to be researched in [[WS15-Backup-Recovery-and-Continuity]].
- [USER DECISION] Sensitivity is classified from the start. Specific regulations are not hard-coded, and sensitive data is not placed anywhere without appropriate agreements. [RECOMMENDATION: enforce by harness, see [[WS08-Policy-Decision-and-Enforcement]]]
- Deletion of canonical data requires the Human's authorization.

Seed source for provenance: [[SRC-w3c-prov-overview]]. Lifecycle research: [[WS12-Data-Knowledge-and-Memory-Lifecycle]].
