---
doc_id: arch.role-scoped-memory
title: Role-Scoped Memory
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

# Role-Scoped Memory

[USER REQUIREMENT] What a higher role knows is not echoed to lower roles. Each role sees data processed for its own duties, in its own vocabulary.

## Concepts

- **One record, many views.** A fact is stored once. Each role receives a projection with the fields, detail level and wording suited to its duties.
- **Role vocabulary.** The Human and CEO receive plain-language summaries. Technical terms go to the roles that need them.
- **Access is not use.** A higher role may be permitted to read lower-role data. That does not load it into context. Reading requires a purpose, and access is logged.
- **Interface-only exposure.** A role that consumes a capability sees the contract (for example "an object store with a given endpoint and bucket") and not the architecture behind it.
- **Enforcement by the harness.** Views are enforced at retrieval and tool boundaries, not by agents' good intentions.

## Example (illustrative only)

A storage fault could appear to a technical role as detailed diagnostics. It could appear to an executive as "one backup copy is unhealthy, repair underway". The Human sees "backups are fine, one thing is being repaired".

## Research to complete

Information barriers, projection design, vocabulary mapping, memory-poisoning defenses and knowledge promotion rules are covered in [[WS06-Role-Scoped-Memory]] and [[WS12-Data-Knowledge-and-Memory-Lifecycle]].
