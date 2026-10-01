---
doc_id: gov.change-authority
title: Change Authority
status: scaffold
authority: normative-draft
audience:
  - human
  - ceo-agent
access_scope:
  - governance
sensitivity: internal
owner: human-principal
version: 0.1.0
created: 2026-10-01
last_reviewed:
review_required: true
supersedes:
---

# Change Authority

[USER REQUIREMENT] Not every rule change needs the Human.

| Change scope | Who signs |
|---|---|
| Human–CEO contract, Human authority, ownership, global or organization-wide policy | Human and CEO |
| One team's rules, inside delegated authority | CEO plus the responsible executive (for example CTO, CFO or COO) |
| Rules crossing team boundaries | Each affected authority |
| Session-only override by the Human | Human alone ([[Override-Lifecycle]]) |

## Principles

- Signatories follow affected domains, not title alone.
- A team acts autonomously inside already approved rules and delegated authority.
- Changes use signed supersession. Prior versions are retained ([[Decisions-Register]]).
- Separation of duties and least privilege limit conflicting authority while allowing the permissions each role needs. [FACT] [[SRC-nist-sp800-53]] lists an Access Control family among its 20 control families. [UNVERIFIED] Which specific controls address separation of duties and least privilege, and what they require, will be parsed in [[WS03-Delegation-and-Signature-Authority]].

## Research to complete

Comparative study of approval matrices, delegated authority, separation of duties, policy exceptions and temporary waivers. The final model is a Human decision.
