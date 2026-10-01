---
chunk_id: arch-data-classes-000
parent_document: vault/04-Architecture/Data-Classes.md
heading_path: Data Classes
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
source_ids: []
parent_section_hash: 27daebdd80b7bd55
effective_date:
supersedes:
review_required: true
---

Parent: [[Data-Classes]]

The system distinguishes data by what it is and what may happen to it.

| Class | Meaning |
|---|---|
| Canonical | The authoritative copy of organizational memory, knowledge and records. |
| Derived | Computed from canonical data and rebuildable (for example indexes and projections). |
| Backup | Independent copies held for recovery. |
| Audit | Append-only, attributable records of significant actions. |
| Working | Short-lived worker state that is not authoritative. |
| Approved | Rules, playbooks and decisions that are operationally immutable and changed only by signed supersession. |
