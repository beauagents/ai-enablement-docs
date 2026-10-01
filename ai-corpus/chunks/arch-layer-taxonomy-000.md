---
chunk_id: arch-layer-taxonomy-000
parent_document: vault/04-Architecture/Layer-Taxonomy.md
heading_path: Layer Taxonomy
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
parent_section_hash: 11c5531ff7cf723c
effective_date:
supersedes:
review_required: true
---

Parent: [[Layer-Taxonomy]]

This is a candidate taxonomy using generic capability names. It is a starting point for [[WS01-Layer-Taxonomy-and-Boundaries]]. Layers, names and boundaries are not final.

| Candidate layer | Capability described (generic) |
|---|---|
| Interaction | Channels through which the Human and agents exchange messages, approvals and notifications. |
| Governance and policy | Rules, delegation, approval workflow, signature and supersession records. |
| Identity and credentials | Workload identity, credential broker, short-lived scoped access. |
| Agent runtime | Where agents and workers run, are scheduled, leased, replaced and quarantined. |
| Orchestration | Durable workflows, checkpoints, retries, idempotent effects. |
| Tool gateway | Mediated access to external tools and services using open tool protocols. |
| Models | Access to language and other models, with routing, quotas and data-handling controls. |
| Memory and knowledge | Role-scoped views over canonical stores, with provenance. |
| Retrieval | Indexing and search over governed content. |
| Durable data | Canonical, derived, backup and audit stores. |
| Observability | Traces, metrics, logs, cost telemetry. |
| Audit and evidence | Append-only, attributable records of significant actions. |
| Resilience | Backup, recovery, failover and continuity. |
| Resource governance | Cost control, acquisition policy, anomaly response. |
| Evaluation | Tests, red-teaming, conformance and reward-integrity checks. |
