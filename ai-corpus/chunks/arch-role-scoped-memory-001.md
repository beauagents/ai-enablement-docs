---
chunk_id: arch-role-scoped-memory-001
parent_document: vault/04-Architecture/Role-Scoped-Memory.md
heading_path: Role-Scoped Memory > Concepts
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
parent_section_hash: 8b7b828211f746fb
effective_date:
supersedes:
review_required: true
---

Parent: [[Role-Scoped-Memory#Concepts]]

- **One record, many views.** A fact is stored once. Each role receives a projection with the fields, detail level and wording suited to its duties.
- **Role vocabulary.** The Human and CEO receive plain-language summaries. Technical terms go to the roles that need them.
- **Access is not use.** A higher role may be permitted to read lower-role data. That does not load it into context. Reading requires a purpose, and access is logged.
- **Interface-only exposure.** A role that consumes a capability sees the contract (for example "an object store with a given endpoint and bucket") and not the architecture behind it.
- **Enforcement by the harness.** Views are enforced at retrieval and tool boundaries, not by agents' good intentions.
