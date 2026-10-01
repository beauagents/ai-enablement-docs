---
doc_id: gov.emergency-materiality
title: Emergency Materiality
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

# Emergency Materiality

[USER REQUIREMENT] Resource count alone is not a valid emergency trigger. Two large, privileged, high-cost instances can carry more risk than hundreds of small disposable workers.

## Signals to evaluate (multidimensional)

- Current and projected cost or credit burn.
- Compute, memory, accelerator, storage, network and concurrency consumption.
- Instance type and allocated size.
- Privilege and credential scope.
- Data sensitivity and potential blast radius.
- Failure, retry and replacement rates.
- Service degradation and saturation.
- Deviation from the approved plan or the normal baseline.
- Speed at which the condition is worsening.
- Reversibility and containment time.

## Rules

- Any figure used in an example is labelled illustrative only.
- Actual thresholds are contextual, role-approved and adjustable as usage patterns become known.

## Sources

- [FACT] Anomaly management is described as detecting, identifying, alerting on and managing unexpected cost and usage irregularities. Context-relevant thresholds and cost allocation metadata appear at the middle maturity level. See [[SRC-finops-anomaly-management]].
- [FACT] A circuit breaker can trip on failure frequency over time and can use different thresholds for different errors. See [[SRC-fowler-circuit-breaker]].
