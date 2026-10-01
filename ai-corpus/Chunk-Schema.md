---
doc_id: corpus.chunk-schema
title: Chunk Schema
status: scaffold
authority: informative
audience:
  - human
  - ceo-agent
access_scope:
  - corpus
sensitivity: internal
owner: human-principal
version: 0.1.0
created: 2026-10-01
last_reviewed:
review_required: true
supersedes:
---

# Chunk Schema

Fields in each chunk's front matter. This describes documentation metadata. It is not executable code.

| Field | Meaning |
|---|---|
| chunk_id | Stable identifier made of the parent document id and a sequence number. Dots in document ids become hyphens so file names stay portable. |
| parent_document | Path of the authoritative vault note. |
| heading_path | Title and heading trail of the section. |
| document_version | Version of the parent document at generation time. |
| status | scaffold, researched, reviewed or accepted. |
| authority | informative or normative-draft. Normative status is conferred only by signed acceptance. |
| audience | Roles allowed to retrieve the chunk. |
| access_scope | Topical scope labels. |
| sensitivity | Sensitivity class of the content. |
| labels_status | provisional until role definitions exist ([[WS06-Role-Scoped-Memory]]). |
| source_ids | Source identifiers cited in the chunk. |
| parent_section_hash | SHA-256 hash of the parent section text. |
| effective_date, supersedes | Supersession information. |
| review_required | Whether the chunk needs review before reliance. |

## Rules

- A chunk reproduces its section unchanged. It does not paraphrase.
- A chunk never merges text from different access scopes.
- Regeneration after a vault change replaces the chunk file. The previous version remains in Git history.
- Stable IDs survive file renames. Renames are recorded.
