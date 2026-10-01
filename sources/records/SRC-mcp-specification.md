---
source_id: SRC-mcp-specification
title: "Specification"
creators:
  - Model Context Protocol
url: https://modelcontextprotocol.io/specification
date_or_version: "2026-07-28"
kind: specification
quality_class: Q1
retrieved: 2026-10-01
parse_status: summary-extracted
capture_status: not-captured
rights_status: unverified
archive_manifest: "[[ARC-mcp-specification]]"
supersedes:
superseded_by:
used_by_workstreams:
  - WS09
---

# Source record: Specification

## Metadata

| Field | Value |
|---|---|
| Source ID | SRC-mcp-specification |
| Title | Specification |
| Creators or publisher | Model Context Protocol |
| URL | <https://modelcontextprotocol.io/specification> |
| Date or version | 2026-07-28 |
| Kind | specification |
| Quality class | Q1. Open specification maintained by its governing project. It is not a formal standards-body document. See [[Source-Quality-Classes]]. |
| Retrieved | 2026-10-01 |

## Summary

The Model Context Protocol (MCP) is an open protocol for integrating LLM applications with external data sources and tools. It uses JSON-RPC 2.0 messages to enable communication between hosts, clients, and servers. MCP standardizes features including resources, prompts, tools, elicitation, configuration, progress tracking, cancellation, and error reporting. The specification also describes security and trust considerations and optional extensions that require explicit support from both client and server.

Extraction note: the summary and evidence below were extracted from the retrieved page text on 2026-10-01 by an AI assistant. They state what the page states, they have not been independently verified, and they need a second-pass review before any claim beyond the evidence block is labelled FACT.

## Parsed evidence

- MCP enables applications to share contextual information with language models, expose tools and capabilities to AI systems, and build composable integrations and workflows. ^ev-1
- Hosts are LLM applications that initiate connections, clients are connectors within host applications, and servers provide context and capabilities. ^ev-2
- Servers may offer resources, prompts, and tools; clients may offer elicitation. ^ev-3
- The base protocol uses JSON-RPC message format, stateless self-contained requests, and per-request capability negotiation. ^ev-4
- Optional extensions include Tasks, Skills over MCP, and MCP Apps. ^ev-5
- Hosts must obtain explicit user consent before exposing user data to servers or invoking tools. ^ev-6

## Evidence locations

- Page: <https://modelcontextprotocol.io/specification>. Section-level locators are pending a full parse.

## Limitations

This page does not establish detailed requirements for each protocol component; it directs readers to separate Architecture, Base Protocol, Server Features, and Client Features pages. It states that MCP itself cannot enforce the listed security principles at the protocol level.

- Parse status is summary-extracted. The full text has not been parsed into this record.

## Conflicts

None recorded. No cross-source comparison has been performed yet.

## Rights and access

Rights status: unverified. No full text is reproduced here. See [[ARC-mcp-specification]] for capture status.

## Relationships

- Archive manifest: [[ARC-mcp-specification]]
- Registry: [[Source-Registry]]
- Cited by vault notes: [[Tool-Gateway]], [[WS09-Tool-Protocols-and-Gateway]]

## Workstream usage

- [[WS09-Tool-Protocols-and-Gateway]]

## Verification log

| Date | Action | Result |
|---|---|---|
| 2026-10-01 | Page text retrieved and key statements extracted | summary-extracted |
