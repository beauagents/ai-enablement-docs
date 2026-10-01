---
doc_id: arch.credential-broker
title: Credential Broker
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

# Credential Broker

[USER REQUIREMENT] The Human provides full-access administrative credentials to the broker. The broker grants default access without approval. Anything above least-needed requires approval.

## Properties

- The broker is the only holder of administrative credentials. Agents never see them.
- Each grant is scoped to a task and expires.
- "Default access" is defined per role.
- Approval requests are phrased in plain language ([[Approval-Notification-Escalation]]).
- Unanswered approvals expire without granting access.
- Break-glass access is separate from default access and always alerts the Human.
- Every grant and use is attributable ([[Observability-vs-Audit]]).
- [INFERENCE] Credentials are keyed by deployment and purpose, not only by a name that could collide.

## Seed sources

- [[SRC-rfc6749-oauth2]]: authorization framework.
- [[SRC-spiffe-overview]]: short-lived cryptographic identity documents for workloads.

Detailed model: [[WS07-Identity-and-Credential-Delegation]].
