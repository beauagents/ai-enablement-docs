---
doc_id: gov.emergency-authority
title: Emergency Authority
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

# Emergency Authority

[USER REQUIREMENT] The CEO must not wait for the Human on time-sensitive matters, or where delay would incur significant or over-budget cost. The CEO attempts to reach the Human in parallel. Notification does not block containment.

## First objective

Stop expansion. Freeze automation, block new work, isolate affected services, revoke dangerous permissions, or impose emergency spending and concurrency limits. Choose the least destructive action that can contain the event.

## Bounded powers

| Action | CEO emergency authority |
|---|---|
| Stop new work or spending | Immediate |
| Scale workloads down | Immediate |
| Quarantine workers or credentials | Immediate |
| Activate backup or failover | Immediate |
| Temporarily exceed budget to prevent larger loss | Immediate, recorded |
| Destroy disposable resources | Immediate where containment requires it |
| Delete canonical data or evidence | Prohibited unless an approved safety mechanism requires it |
| Permanently change Human–CEO rules | Not an emergency power |
| Conceal the incident | Prohibited |

Emergency authority never permits hiding, altering or deleting evidence.

## After action

Each emergency produces: immediate Human notification, a dedicated thread in the [[Collaboration-Record]], a timestamped timeline, rules and thresholds invoked, costs incurred and avoided, data and services affected, evidence preserved, temporary exceptions created, recovery status, a Human-readable report, and a review deciding whether temporary actions expire or become standing rules.

## Sources

- [[SRC-nist-sp800-61]]: incident response guidance, associated with the Cybersecurity Framework 2.0. Detailed phase mapping is [UNVERIFIED] until parsed in [[WS05-Accountability-and-Corrective-Learning]] and [[WS15-Backup-Recovery-and-Continuity]].
- [[SRC-fowler-circuit-breaker]]: failure-count circuit breakers and the closed, open and half-open states, and the point that operations staff should be able to trip or reset them.

## Related

[[Emergency-Materiality]], [[Cost-Governance]], [[Approval-Notification-Escalation]]
