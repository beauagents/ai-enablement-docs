---
doc_id: foundation.purpose-and-scope
title: Purpose and Scope
status: scaffold
authority: informative
audience:
  - human
  - ceo-agent
access_scope:
  - foundation
sensitivity: internal
owner: human-principal
version: 0.1.0
created: 2026-10-01
last_reviewed:
review_required: true
supersedes:
---

# Purpose and Scope

## Purpose

Document a complete AI enablement system in neutral terms: the layers, contracts, boundaries, data flows, failure models, governance and acceptance criteria that any implementation must satisfy. The documents describe what the system must do and why. They do not choose products.

## Intended operating model

[USER REQUIREMENT] One Human principal owns, funds and directs the system. Replaceable AI workers carry out implementation and operations under delegated authority. The Human retains ownership and custody of all durable data. See [[Authority-Model]] and [[Principles]].

## In scope

- Capability taxonomy and layer boundaries ([[Layer-Taxonomy]]).
- Authority, delegation, override, emergency and change-control rules (Governance notes).
- Role-scoped memory, credentials, tools, execution, durable state and recovery.
- Observability and audit as separate concerns ([[Observability-vs-Audit]]).
- Cost and resource governance, including a neutral acquisition policy ([[Resource-Acquisition-Policy]]).
- Evaluation, conformance and provider-adapter contracts (see [[Workstream-Index]]).
- Citation, archive and supersession rules for the documentation itself.

## Out of scope on the main branch

See [[Non-Goals]].

## Starting state

[USER DECISION] Everything starts fresh. No deployed state, credentials, configuration, databases or operational history is inherited by this documentation. Existing projects may be examined only as capability evidence, and only when a workstream needs them.
