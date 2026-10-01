---
chunk_id: gov-emergency-materiality-003
parent_document: vault/02-Governance/Emergency-Materiality.md
heading_path: Emergency Materiality > Sources
document_version: 0.1.0
status: scaffold
authority: normative-draft
audience:
  - ceo-agent
access_scope:
  - governance
sensitivity: internal
labels_status: provisional
source_ids:
  - SRC-finops-anomaly-management
  - SRC-fowler-circuit-breaker
parent_section_hash: abc24ac0b03c7502
effective_date:
supersedes:
review_required: true
---

Parent: [[Emergency-Materiality#Sources]]

- [FACT] Anomaly management is described as detecting, identifying, alerting on and managing unexpected cost and usage irregularities. Context-relevant thresholds and cost allocation metadata appear at the middle maturity level. See [[SRC-finops-anomaly-management]].
- [FACT] A circuit breaker can trip on failure frequency over time and can use different thresholds for different errors. See [[SRC-fowler-circuit-breaker]].
