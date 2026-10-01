---
doc_id: arch.execution-and-replacement
title: Execution and Replacement
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

# Execution and Replacement

[USER REQUIREMENT] The system autoscales. When a worker or agent fails, a replacement starts and resumes from main memory. The replacement model is comparable in spirit to a cluster scheduler that replaces failed workloads.

## Required properties

- Workers hold leases. A lease expiry or failed health check triggers replacement.
- State needed to resume is checkpointed outside the worker.
- External side effects are idempotent, so a resumed task does not repeat them.
- Workers cannot modify material already processed into approved rules or playbooks ([[Principles]]).
- Replacement is visible in the [[Collaboration-Record]] and recorded as evidence.
- Autoscaling is bounded by approved limits and circuit breakers ([[Cost-Governance]], [[Emergency-Materiality]]).
- Repeated replacement of the same task is a signal, not a cure. It is surfaced.

## Seed source

[[SRC-fowler-circuit-breaker]] describes tripping after repeated failures instead of continuing to call a failing dependency.

Detailed research: [[WS10-Workflow-Orchestration-and-Replaceable-Execution]] and [[WS11-Durable-State-and-Checkpoints]].
