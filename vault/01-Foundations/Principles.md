---
doc_id: foundation.principles
title: Principles
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

# Principles

These principles are drawn from stated Human requirements. Each is recorded in [[Requirements-Register]]. Research in the workstreams may refine wording. It may not remove a principle without a signed supersession ([[Decisions-Register]]).

## 1. The Human is the principal

The Human owns, funds and directs the system and is the highest authority. The CEO Agent is the highest delegated agent and remains subordinate. See [[Authority-Model]].

## 2. Data belongs to the Human, not to workers

Agents and workers use infrastructure. They do not own memory, knowledge, databases or records. Durable state lives in one governed place so that every worker is disposable. See [[Execution-and-Replacement]] and [[Data-Classes]].

## 3. Workers are replaceable

When a worker fails, a replacement resumes from checkpointed state held outside the worker. No worker-local context is the only copy of anything.

## 4. Approved material is operationally immutable

Processed and approved material (rules, playbooks, decisions) is not edited in place. Changes occur by signed supersession. Deletion requires the Human's authorization. See [[Decisions-Register]].

## 5. Least privilege, brokered

A credential broker holds administrative credentials. Agents receive the least access needed, scoped to a task and limited in time. Anything above least-needed requires approval. See [[Credential-Broker]].

## 6. Information is scoped by role

Each role receives only the information, detail and vocabulary its duties require. Higher roles may be able to access lower-role data. Access is logged and does not mean the data is loaded into context. See [[Role-Scoped-Memory]].

## 7. Full visibility, two records

A human-readable collaboration record and a backend evidence record both exist for all significant activity. See [[Collaboration-Record]] and [[Observability-vs-Audit]].

## 8. Failure is loud

No limit, error or policy breach may fail silently. Every limit has an alert path.

## 9. Roles are functional contracts

Titles such as CEO or CTO describe mandates, authority, duties and accountability. They do not describe simulated characters. See [[Operational-Roles]].

## 10. Accountability over apology

Failures produce accountability records and corrective action. See [[Accountability-Records]].

## 11. Claims need evidence

Every substantive claim carries a label ([[Claim-Labels]]) and a citation chain that resolves locally ([[Citation-Rules-Human]]).

## 12. Neutral first

The main branch names no provider. Provider mappings come only after the neutral set is scaffolded, researched, reviewed and accepted. See [[Layer-Taxonomy]] and the adapter workstream in [[Workstream-Index]].
