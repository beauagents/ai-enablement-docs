---
doc_id: template.chunk
title: Template: AI Chunk
status: scaffold
authority: informative
audience:
  - human
  - ceo-agent
access_scope:
  - template
sensitivity: internal
owner: human-principal
version: 0.1.0
created: 2026-10-01
last_reviewed:
review_required: true
supersedes:
---

# Template: AI Chunk

Structural template. See [[Chunk-Schema]] for field meanings.

```markdown
---
chunk_id: <area>-<document>-<nnn>
parent_document: <path>
heading_path: <Title > Heading>
document_version:
status:
authority:
audience: []
access_scope: []
sensitivity:
labels_status: provisional | defined
source_ids: []
parent_section_hash:
effective_date:
supersedes:
review_required:
---

Parent: [[<Note>#<Heading>]]

<section text, including its wikilinks, unchanged>
```
