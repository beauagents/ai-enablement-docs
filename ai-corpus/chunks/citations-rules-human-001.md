---
chunk_id: citations-rules-human-001
parent_document: vault/08-Citations/Citation-Rules-Human.md
heading_path: Citation Rules (Human Vault) > The evidence chain
document_version: 0.1.0
status: scaffold
authority: normative-draft
audience:
  - ceo-agent
access_scope:
  - citations
sensitivity: internal
labels_status: provisional
source_ids:
  - SRC-obsidian-internal-links
parent_section_hash: f489c987ac06b6f2
effective_date:
supersedes:
review_required: true
---

Parent: [[Citation-Rules-Human#The evidence chain]]

```
claim  ->  wikilink  ->  parsed source record  ->  archive manifest  ->  original or versioned location
```

1. **Claim.** A sentence in a vault note, labelled per [[Claim-Labels]].
2. **Wikilink.** `[[SRC-<slug>]]`, optionally with a heading, block or alias: `[[SRC-<slug>#Parsed evidence]]`, `[[SRC-<slug>#^ev-1]]`, `[[SRC-<slug>|short name]]`. Obsidian supports links to notes, headings and blocks ([[SRC-obsidian-internal-links]]).
3. **Parsed source record.** A Markdown note in `sources/records/` containing metadata, summary, parsed evidence, evidence locations, limitations, conflicts, rights, relationships and workstream usage. See [[Template-Source-Record]].
4. **Archive manifest.** A Markdown note in `sources/archive/` stating what has been captured, how, where, with what integrity hash, or why nothing has been captured. See [[Template-Archive-Manifest]].
5. **Original or versioned location.** The canonical URL or identifier, plus a versioned snapshot when rights permit.
