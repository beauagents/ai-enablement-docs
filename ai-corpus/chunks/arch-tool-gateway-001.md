---
chunk_id: arch-tool-gateway-001
parent_document: vault/04-Architecture/Tool-Gateway.md
heading_path: Tool Gateway > Required properties (requirements, not designs)
document_version: 0.1.0
status: scaffold
authority: informative
audience:
  - ceo-agent
  - cto-agent
access_scope:
  - arch
sensitivity: internal
labels_status: provisional
source_ids:
  - SRC-mcp-specification
parent_section_hash: 6d18c6f447a4f1bc
effective_date:
supersedes:
review_required: true
---

Parent: [[Tool-Gateway#Required properties (requirements, not designs)]]

- Each tool has a profile: allowed scopes, maximum rate and reachable endpoints.
- Permissions are checked at call time, not only when a tool is configured.
- Tool inputs and outputs from external sources are treated as untrusted.
- The gateway logs every call with the invoking identity and authority.
- Open tool protocols are preferred where they meet requirements. A candidate is [[SRC-mcp-specification]]: an open protocol using JSON-RPC 2.0 in which hosts must obtain explicit user consent before exposing user data to servers or invoking tools. Selection is not made here.
