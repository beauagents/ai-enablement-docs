---
doc_id: template.archive-manifest
title: Template: Archive Manifest
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

# Template: Archive Manifest

Structural template. Copy to `sources/archive/ARC-<slug>.md`.

```markdown
---
archive_id: ARC-<slug>
source_record: "[[SRC-<slug>]]"
original_url:
capture_method: none | page-snapshot | file-download | pointer
capture_status: not-captured | pointer-only | snapshot-held
captured_at:
versioned_location:
content_hash:
hash_algorithm:
rights_status: unverified | permits-full-copy | pointer-only
non_capture_reason:
---

# Archive manifest: <slug>

## Status
## What is held locally
## What is pending
## Integrity
## Restrictions
## History
```
