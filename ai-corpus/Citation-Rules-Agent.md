---
doc_id: corpus.citation-rules-agent
title: Citation Rules (Agent Corpus)
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

# Citation Rules (Agent Corpus)

Agents follow the same evidence chain as the human vault ([[Citation-Rules-Human]]).

- Chunks keep source wikilinks such as `[[SRC-<slug>]]`.
- An agent resolves a citation to the parsed record first, then to the archive manifest.
- An agent does not cite a source it has not resolved to a record in this repository.
- If the record's parse status is summary-extracted only, the agent restricts the claim to what the evidence block states and labels the rest UNVERIFIED.
- Agents do not edit source records or manifests. Changes go through the commit process ([[Template-Workstream-Commit]]).
