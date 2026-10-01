---
source_id: SRC-llmstxt-proposal
title: "The /llms.txt file, v2"
creators:
  - Jeremy Howard
url: https://llmstxt.org/
date_or_version: "Version 2; published September 3, 2024; modified August 10, 2026"
kind: proposal
quality_class: Q6
retrieved: 2026-10-01
parse_status: summary-extracted
capture_status: not-captured
rights_status: unverified
archive_manifest: "[[ARC-llmstxt-proposal]]"
supersedes:
superseded_by:
used_by_workstreams:
  - WS13
  - WS20
---

# Source record: The /llms.txt file, v2

## Metadata

| Field | Value |
|---|---|
| Source ID | SRC-llmstxt-proposal |
| Title | The /llms.txt file, v2 |
| Creators or publisher | Jeremy Howard |
| URL | <https://llmstxt.org/> |
| Date or version | Version 2; published September 3, 2024; modified August 10, 2026 |
| Kind | proposal |
| Quality class | Q6. Proposal by an individual author without a formal standards process. See [[Source-Quality-Classes]]. |
| Retrieved | 2026-10-01 |

## Summary

The page proposes using an `/llms.txt` Markdown file to provide concise, LLM-friendly information about a website, along with links to more detailed Markdown content. An `llms.txt` file may be placed at a site root or any subpath and covers URLs under that path. The proposal also recommends clean Markdown versions of relevant pages and standard link relations, including `rel="alternate" type="text/markdown"` and `rel="describedby"`. The specification is presented as open for community input and is hosted in a GitHub repository for version control and public discussion.

Extraction note: the summary and evidence below were extracted from the retrieved page text on 2026-10-01 by an AI assistant. They state what the page states, they have not been independently verified, and they need a second-pass review before any claim beyond the evidence block is labelled FACT.

## Parsed evidence

- An `llms.txt` file contains an H1 project or site name, an optional blockquote summary, optional non-heading Markdown detail sections, and optional H2-delimited file-list sections. ^ev-1
- Each file-list entry must contain a Markdown hyperlink and may include a colon followed by notes about the file. ^ev-2
- An `llms.txt` file at `/docs/llms.txt` covers everything under `/docs/`, and agents should use the most specific applicable file. ^ev-3
- Pages with information agents might need should provide clean Markdown versions using either an appended `.md` extension or a replaced extension; URLs without file names should use `index.html.md` or `index.md`. ^ev-4
- The proposal recommends `rel="alternate" type="text/markdown"` for Markdown page versions and `rel="describedby"` for the applicable `llms.txt` file, provided through HTML `<link>` elements or an HTTP `Link:` header. ^ev-5
- Directories and integrations listed include llmstxt.site, directory.llmstxt.cloud, llmstxthub.com, Mintlify, GitBook, Yoast SEO, AIOSEO, Wix, VitePress, Docusaurus, Drupal, PHP, VS Code PagePilot, and an MCP server. ^ev-6

## Evidence locations

- Page: <https://llmstxt.org/>. Section-level locators are pending a full parse.

## Limitations

The page presents `llms.txt` as a proposal and says its specification is open for community input; it does not establish mandatory adoption. It describes the GitHub repository as an informal overview rather than stating that the proposal is an official web standard.

- Parse status is summary-extracted. The full text has not been parsed into this record.

## Conflicts

None recorded. No cross-source comparison has been performed yet.

## Rights and access

Rights status: unverified. No full text is reproduced here. See [[ARC-llmstxt-proposal]] for capture status.

## Relationships

- Archive manifest: [[ARC-llmstxt-proposal]]
- Registry: [[Source-Registry]]
- Cited by vault notes: [[AI-Corpus-Overview]], [[WS13-Search-Retrieval-and-Indexing]], [[WS20-Documentation-Schemas]]

## Workstream usage

- [[WS13-Search-Retrieval-and-Indexing]]
- [[WS20-Documentation-Schemas]]

## Verification log

| Date | Action | Result |
|---|---|---|
| 2026-10-01 | Page text retrieved and key statements extracted | summary-extracted |
