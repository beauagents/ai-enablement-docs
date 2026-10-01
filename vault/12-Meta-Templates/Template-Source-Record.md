---
doc_id: template.source-record
title: Template: Source Record
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

# Template: Source Record

Structural template for the documentation itself. Copy to `sources/records/SRC-<slug>.md`.

```markdown
---
source_id: SRC-<slug>
title:
creators: []
publisher:
url:
date_or_version:
kind: standard | specification | guidance | preprint | practitioner-article | product-documentation | proposal
quality_class: Q1 | Q2 | Q3 | Q4 | Q5 | Q6
retrieved: YYYY-MM-DD
parse_status: summary-extracted | section-parsed | fully-parsed
capture_status: not-captured | pointer-only | snapshot-held
rights_status: unverified | permits-full-copy | pointer-only
archive_manifest: "[[ARC-<slug>]]"
supersedes:
superseded_by:
used_by_workstreams: []
---

# Source record: <title>

## Metadata
## Summary
## Parsed evidence
- Statement taken from the source. ^ev-1
## Evidence locations
## Limitations
## Conflicts
## Rights and access
## Relationships
## Workstream usage
## Verification log
```
