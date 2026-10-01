---
doc_id: arch.tool-gateway
title: Tool Gateway
status: scaffold
authority: informative
audience:
  - human
  - ceo-agent
access_scope:
  - arch
sensitivity: internal
owner: human-principal
version: 0.1.0
created: 2026-10-01
last_reviewed:
review_required: true
supersedes:
---

# Tool Gateway

All external tool and service access passes through a mediating gateway. Agents do not hold direct connections.

## Required properties (requirements, not designs)

- Each tool has a profile: allowed scopes, maximum rate and reachable endpoints.
- Permissions are checked at call time, not only when a tool is configured.
- Tool inputs and outputs from external sources are treated as untrusted.
- The gateway logs every call with the invoking identity and authority.
- Open tool protocols are preferred where they meet requirements. A candidate is [[SRC-mcp-specification]]: an open protocol using JSON-RPC 2.0 in which hosts must obtain explicit user consent before exposing user data to servers or invoking tools. Selection is not made here.

## Threat context

[[SRC-owasp-agentic-top10]] is a peer-reviewed list of top risks for agentic applications. Its individual entries are [UNVERIFIED] until parsed in [[WS16-Security-and-Threat-Models]].

Detailed research: [[WS09-Tool-Protocols-and-Gateway]].
