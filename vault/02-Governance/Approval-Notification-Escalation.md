---
doc_id: gov.approval-notification-escalation
title: Approval, Notification and Escalation
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

# Approval, Notification and Escalation

Three actions are kept distinct everywhere in this documentation.

| Action | Definition |
|---|---|
| Approval | Authorization required before an action occurs. |
| Notification | Visibility provided without stopping an authorized action. |
| Escalation | Transfer of a decision because authority, risk, conflict or conditions exceed an approved boundary. |

## Rules

- [USER REQUIREMENT] An action covered by an approved rule needs no escalation.
- [USER REQUIREMENT] It still needs the visibility the rule specifies: a thread in the [[Collaboration-Record]] and full backend evidence ([[Observability-vs-Audit]]).
- Unanswered approvals expire. They never auto-approve. [RECOMMENDATION, pending [[WS08-Policy-Decision-and-Enforcement]]]
- Approval requests state, in plain language: what, why, for how long, and at what cost. [RECOMMENDATION]
