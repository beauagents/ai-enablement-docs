---
chunk_id: arch-credential-broker-001
parent_document: vault/04-Architecture/Credential-Broker.md
heading_path: Credential Broker > Properties
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
parent_section_hash: 9206c1375bdd2d95
effective_date:
supersedes:
review_required: true
---

Parent: [[Credential-Broker#Properties]]

- The broker is the only holder of administrative credentials. Agents never see them.
- Each grant is scoped to a task and expires.
- "Default access" is defined per role.
- Approval requests are phrased in plain language ([[Approval-Notification-Escalation]]).
- Unanswered approvals expire without granting access.
- Break-glass access is separate from default access and always alerts the Human.
- Every grant and use is attributable ([[Observability-vs-Audit]]).
- [INFERENCE] Credentials are keyed by deployment and purpose, not only by a name that could collide.
