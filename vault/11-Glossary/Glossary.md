---
doc_id: glossary.terms
title: Glossary
status: scaffold
authority: informative
audience:
  - human
  - ceo-agent
access_scope:
  - glossary
sensitivity: internal
owner: human-principal
version: 0.1.0
created: 2026-10-01
last_reviewed:
review_required: true
supersedes:
---

# Glossary

Plain-language definitions. Technical roles may add detail in their own vocabulary layers ([[Role-Scoped-Memory]]).

| Term | Meaning |
|---|---|
| Human principal | The owner, funder and highest authority of the system. |
| CEO Agent | The highest delegated agent. It reports to the Human and holds bounded emergency authority. |
| Executive agent | A delegated agent with domain authority, for example technology, finance or operations. |
| Worker | A disposable executor of tasks that owns no durable data. |
| Lease | A time-limited claim a worker holds on a task. Expiry allows replacement. |
| Checkpoint | State stored outside a worker so a replacement can resume. |
| Canonical data | The authoritative copy of organizational records. See [[Data-Classes]]. |
| Derived data | Data computed from canonical data and rebuildable. |
| Supersession | Replacing an approved item with a new signed version while retaining the old. |
| Role-scoped view | A projection of a record suited to one role's duties and vocabulary. |
| Collaboration record | The human-readable record of discussions and decisions. See [[Collaboration-Record]]. |
| Audit record | An attributable, append-only record of a significant action. |
| Observability | Understanding system behavior through traces, metrics and logs. |
| Circuit breaker | A control that stops calls or activity after failures reach a threshold. See [[SRC-fowler-circuit-breaker]]. |
| Credential broker | The component that holds administrative credentials and issues scoped, short-lived access. |
| Break-glass | Exceptional access, separate from default access, that always alerts the Human. |
| Idempotent | Safe to repeat without repeating the effect. |
| Arbitrage | Obtaining a capability by a lower-cost or higher-value route without hiding risk. See [[Resource-Acquisition-Policy]]. |
| Chunk | A small Markdown unit of the AI corpus linked to a parent section. See [[Chunk-Schema]]. |
| Wikilink | An Obsidian-style link written with double square brackets. |
| Source record | A parsed Markdown note describing one cited source. |
| Archive manifest | A note stating what has been captured for a source and where. |
| Workstream | A research area completed as separate commits. See [[Workstream-Index]]. |
| Overlay | A later provider mapping that does not redefine neutral contracts. |
