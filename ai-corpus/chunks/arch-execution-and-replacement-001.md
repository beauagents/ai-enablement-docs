---
chunk_id: arch-execution-and-replacement-001
parent_document: vault/04-Architecture/Execution-and-Replacement.md
heading_path: Execution and Replacement > Required properties
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
parent_section_hash: 4a3694fe39ddab4d
effective_date:
supersedes:
review_required: true
---

Parent: [[Execution-and-Replacement#Required properties]]

- Workers hold leases. A lease expiry or failed health check triggers replacement.
- State needed to resume is checkpointed outside the worker.
- External side effects are idempotent, so a resumed task does not repeat them.
- Workers cannot modify material already processed into approved rules or playbooks ([[Principles]]).
- Replacement is visible in the [[Collaboration-Record]] and recorded as evidence.
- Autoscaling is bounded by approved limits and circuit breakers ([[Cost-Governance]], [[Emergency-Materiality]]).
- Repeated replacement of the same task is a signal, not a cure. It is surfaced.
