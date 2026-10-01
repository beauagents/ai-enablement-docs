---
doc_id: citations.rules-human
title: Citation Rules (Human Vault)
status: scaffold
authority: normative-draft
audience:
  - human
  - ceo-agent
access_scope:
  - citations
sensitivity: internal
owner: human-principal
version: 0.1.0
created: 2026-10-01
last_reviewed:
review_required: true
supersedes:
---

# Citation Rules (Human Vault)

[USER REQUIREMENT] Citations are allowed and expected, but each one must resolve to a fully parsed record held in this repository. Obsidian wikilinks are required in the vault.

## The evidence chain

```
claim  ->  wikilink  ->  parsed source record  ->  archive manifest  ->  original or versioned location
```

1. **Claim.** A sentence in a vault note, labelled per [[Claim-Labels]].
2. **Wikilink.** `[[SRC-<slug>]]`, optionally with a heading, block or alias: `[[SRC-<slug>#Parsed evidence]]`, `[[SRC-<slug>#^ev-1]]`, `[[SRC-<slug>|short name]]`. Obsidian supports links to notes, headings and blocks ([[SRC-obsidian-internal-links]]).
3. **Parsed source record.** A Markdown note in `sources/records/` containing metadata, summary, parsed evidence, evidence locations, limitations, conflicts, rights, relationships and workstream usage. See [[Template-Source-Record]].
4. **Archive manifest.** A Markdown note in `sources/archive/` stating what has been captured, how, where, with what integrity hash, or why nothing has been captured. See [[Template-Archive-Manifest]].
5. **Original or versioned location.** The canonical URL or identifier, plus a versioned snapshot when rights permit.

## Rules

- A claim is not labelled FACT until its record and manifest exist and the record's evidence block supports the claim.
- Where a claim relies on a source that has been summarized but not fully parsed, the claim is labelled UNVERIFIED or limited to what the evidence block states.
- Full source files are kept only when licensing and access rights permit. Restricted or copyrighted sources get a parsed record and an archive pointer, not a reproduction of the full text.
- Accepted records are not silently replaced. A new version supersedes the old one with both retained ([[Decisions-Register]]).
- Conflicts between sources are recorded in both records and in the citing note.
- Vendor-authored material is classed and weighted by [[Source-Quality-Classes]].
- Agent chunks carry the same source identifiers and wikilinks ([[Citation-Rules-Agent]]).

## Registry

All sources are listed in [[Source-Registry]].

## Capture status in this scaffold

The seed records were extracted from the page text on the retrieval date shown in each record. Full-text parsing and archive capture are pending and will be done by the workstreams. Each manifest states this plainly.
