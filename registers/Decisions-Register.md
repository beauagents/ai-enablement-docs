---
doc_id: register.decisions
title: Decisions Register
status: scaffold
authority: normative-draft
audience:
  - human
  - ceo-agent
access_scope:
  - register
sensitivity: internal
owner: human-principal
version: 0.1.0
created: 2026-10-01
last_reviewed:
review_required: true
supersedes:
---

# Decisions Register

Decisions made by the Human principal or by the governance chain. Entries are append-only. A change is a new entry that supersedes an earlier one by ID. The earlier entry is retained.

| ID | Decision | Label | Status | Recorded |
|---|---|---|---|---|
| D-001 | Main branch is provider-neutral. | USER DECISION | Accepted | 2026-10-01 |
| D-002 | Everything starts fresh. Existing deployments and history are out of scope. | USER DECISION | Accepted | 2026-10-01 |
| D-003 | The repository contains documents. There are two synchronized views: a human Obsidian vault and an AI-chunked corpus. | USER DECISION | Accepted | 2026-10-01 |
| D-004 | Citations must resolve through wikilinks to parsed records and archive manifests. | USER DECISION | Accepted | 2026-10-01 |
| D-005 | The researcher does not make architectural decisions and presents all credible options. | USER DECISION | Accepted | 2026-10-01 |
| D-006 | Scaffold first. The 22 research areas are completed as separate commits. | USER DECISION | Accepted | 2026-10-01 |
| D-007 | The repository is private. | USER DECISION | Accepted | 2026-10-01 |

## Supersession format

```
D-0xx supersedes D-0yy. Reason. Signed by: <roles>. Date.
```

Signature mechanisms are not yet defined ([[WS03-Delegation-and-Signature-Authority]]). Until then, the Human's decision in the repository thread is the recorded authority.
