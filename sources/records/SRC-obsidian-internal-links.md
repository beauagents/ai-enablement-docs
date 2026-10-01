---
source_id: SRC-obsidian-internal-links
title: "Internal links - Obsidian Help"
creators:
  - Obsidian Help
url: https://help.obsidian.md/links
date_or_version: "not stated on page"
kind: product-documentation
quality_class: Q5
retrieved: 2026-10-01
parse_status: summary-extracted
capture_status: not-captured
rights_status: unverified
archive_manifest: "[[ARC-obsidian-internal-links]]"
supersedes:
superseded_by:
used_by_workstreams:
  - WS20
  - WS21
---

# Source record: Internal links - Obsidian Help

## Metadata

| Field | Value |
|---|---|
| Source ID | SRC-obsidian-internal-links |
| Title | Internal links - Obsidian Help |
| Creators or publisher | Obsidian Help |
| URL | <https://help.obsidian.md/links> |
| Date or version | not stated on page |
| Kind | product-documentation |
| Quality class | Q5. Product documentation. Used only to document linking syntax for the vault format. See [[Source-Quality-Classes]]. |
| Retrieved | 2026-10-01 |

## Summary

Obsidian supports Wikilink and Markdown formats for linking to notes, attachments, and other files. Internal links can target files, headings, subheadings, and blocks, and links can include custom display text. Obsidian can automatically update internal links when files are renamed, and linked files can be previewed when Page preview is enabled.

Extraction note: the summary and evidence below were extracted from the retrieved page text on 2026-10-01 by an AI assistant. They state what the page states, they have not been independently verified, and they need a second-pass review before any claim beyond the evidence block is labelled FACT.

## Parsed evidence

- Wikilink examples include `[[Three laws of motion]]` and `[[Three laws of motion.md]]`; Markdown examples include `[Three laws of motion](Three%20laws%20of%20motion)` and `[Three laws of motion](Three%20laws%20of%20motion.md)`. ^ev-1
- Folder paths start at the vault root and use forward slashes, such as `[[Projects/Three laws of motion]]`. ^ev-2
- Headings can be linked with `#`, subheadings can use multiple hash symbols, and headers can be searched across the vault with `[[## header]]`. ^ev-3
- Blocks can be linked with `#^` and a unique block identifier, and blocks can be searched across the vault with `[[^^block]]`. ^ev-4
- Block identifiers can contain only Latin letters, numbers, and dashes, and block references are specific to Obsidian rather than standard Markdown. ^ev-5
- An exclamation mark before an internal link embeds the linked content, while excluded files are deprioritized in link suggestions. ^ev-6

## Evidence locations

- Page: <https://help.obsidian.md/links>. Section-level locators are pending a full parse.

## Limitations

The page does not state a publication date or version, and it does not identify individual authors. It also states that links to specific parts of quotations, callouts, and tables are not supported.

- Parse status is summary-extracted. The full text has not been parsed into this record.

## Conflicts

None recorded. No cross-source comparison has been performed yet.

## Rights and access

Rights status: unverified. No full text is reproduced here. See [[ARC-obsidian-internal-links]] for capture status.

## Relationships

- Archive manifest: [[ARC-obsidian-internal-links]]
- Registry: [[Source-Registry]]
- Cited by vault notes: [[Citation-Rules-Human]], [[WS20-Documentation-Schemas]], [[WS21-Repository-Governance-and-Supersession]]

## Workstream usage

- [[WS20-Documentation-Schemas]]
- [[WS21-Repository-Governance-and-Supersession]]

## Verification log

| Date | Action | Result |
|---|---|---|
| 2026-10-01 | Page text retrieved and key statements extracted | summary-extracted |
