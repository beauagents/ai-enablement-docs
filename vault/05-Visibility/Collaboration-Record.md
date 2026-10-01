---
doc_id: visibility.collaboration-record
title: Collaboration Record
status: scaffold
authority: informative
audience:
  - human
  - ceo-agent
access_scope:
  - visibility
sensitivity: internal
owner: human-principal
version: 0.1.0
created: 2026-10-01
last_reviewed:
review_required: true
supersedes:
---

# Collaboration Record

[USER REQUIREMENT] Approved actions need full visibility in a human-readable discussion record as well as in backend observability.

## Definition

The collaboration record holds proposals, objections, approvals, decisions and status updates in threads, desks, rooms or boards. In this documentation it is called a **collaboration and notification channel**.

## Rules

- Executives may collaborate in shared threads. The Human need not read everything. The Human can inspect any thread.
- Channels may be human-to-agent, agent-to-agent or webhook-driven notifications.
- The collaboration record never replaces backend evidence ([[Observability-vs-Audit]]).
- A thread carries no authority by itself. Authority comes from signed decisions ([[Change-Authority]]).
- Thread visibility respects role scoping ([[Role-Scoped-Memory]]).
