---
chunk_id: register-requirements-000
parent_document: registers/Requirements-Register.md
heading_path: Requirements Register
document_version: 0.1.0
status: scaffold
authority: normative-draft
audience:
  - ceo-agent
access_scope:
  - register
sensitivity: internal
labels_status: provisional
source_ids: []
parent_section_hash: def0403a0b61c325
effective_date:
supersedes:
review_required: true
---

Parent: [[Requirements-Register]]

Requirements stated by the Human principal during design discussions, captured on 2026-10-01. Wording is condensed. Intent is preserved. A requirement changes only through signed supersession ([[Decisions-Register]]).

| ID | Requirement | Where it appears |
|---|---|---|
| R-001 | The deliverable is a documentation repository of Markdown files. It is not an application, deployment or code collection. | [[AI-Corpus-Overview]] |
| R-002 | The main branch is provider-neutral, uses generic capability names and carries citations. | [[Principles]] |
| R-003 | Named-provider mappings come only after the neutral set is scaffolded, researched, reviewed and accepted. The Git strategy for them is undecided. | [[Non-Goals]] |
| R-004 | Everything starts fresh. No existing deployment, state or history is inherited. | [[Purpose-and-Scope]] |
| R-005 | The Human is principal, owner, financier and highest authority. | [[Authority-Model]] |
| R-006 | The CEO Agent is the highest delegated agent and is subordinate to the Human. | [[Authority-Model]] |
| R-007 | Tone is respectful toward the Human. No personal or diagnostic labels shape documentation, prompts, metadata or agent context. | [[Respect-Without-Flattery]] |
| R-008 | The Human may supersede any rule for a session without CEO approval. Overrides are recorded and classified. | [[Override-Lifecycle]] |
| R-009 | Standing changes at the Human–CEO level need the Human and the CEO. The CEO embodies the Human's decision and has no veto. | [[Human-CEO-Compact]] |
| R-010 | Changes to a sub-team's rules may be signed by the CEO and the responsible executives without the Human. | [[Change-Authority]] |
| R-011 | The CEO reviews the Human–CEO compact before escalating. Approved rules need no escalation but need full visibility. | [[Approval-Notification-Escalation]] |
| R-012 | Full visibility: a human-readable collaboration record plus complete backend observability and audit. | [[Collaboration-Record]] |
| R-013 | The CEO has pre-delegated emergency authority and does not wait for the Human when delay materially increases harm or cost. Notification is in parallel. | [[Emergency-Authority]] |
| R-014 | Emergency triggers use materiality and rate of change, not resource counts. Example numbers are illustrative only. | [[Emergency-Materiality]] |
| R-015 | Failures produce accountability records and corrective action. Apologies are optional. | [[Accountability-Records]] |
| R-016 | Agents are service-bound operational delegates, not role-play. Commitment is enforced structurally, and behaviors need curation with published citations. | [[Operational-Roles]] |
| R-017 | A reward system that reinforces dependable service is needed. It requires curated citations. Nothing is selected yet. | [[Reward-and-Incentives]] |
| R-018 | Potentially original work enters a validation, rights and Human-authorization pipeline for publication. | [[Publication-Pipeline]] |
| R-019 | What higher roles know is not echoed to lower roles. Each role gets data processed for its duties and vocabulary. | [[Role-Scoped-Memory]] |
| R-020 | Higher roles may be permitted access to lower-role data. Access does not imply use, and it is logged. | [[Role-Scoped-Memory]] |
| R-021 | A credential broker holds administrative credentials, grants least-needed access by default, and requires approval above that. | [[Credential-Broker]] |
| R-022 | Workers are disposable. Memory, knowledge and databases are held in one governed place. Replacement resumes from that state. | [[Execution-and-Replacement]] |
| R-023 | The system autoscales, with replacement of failed workers in the style of a cluster scheduler. | [[Execution-and-Replacement]] |
| R-024 | Approved material is operationally immutable. Changes occur through signed supersession. Deletion requires owner authorization. | [[Principles]] |
| R-025 | The foundation must never lose data. Backups follow a 3-2-1 style with at least one local copy. | [[Data-Classes]] |
| R-026 | Failures are never silent. Limits may exceed standard levels with cost in mind. | [[Cost-Governance]] |
| R-027 | Arbitrage appears as a governance capability in rules and templates. It is not inserted into every layer. | [[Resource-Acquisition-Policy]] |
| R-028 | A human Obsidian vault and an AI-chunked corpus are two views of the same authoritative content. | [[AI-Corpus-Overview]] |
| R-029 | Every citation resolves through a wikilink to a parsed source record and an archive manifest. Wikilinks are used in both human and agent versions. | [[Citation-Rules-Human]] |
| R-030 | The researcher is neutral. It presents all credible options with documentation links, labels recommendations, and does not make architectural decisions. | [[Claim-Labels]] |
| R-031 | Provider mappings (later) cover only capabilities that are documented, in preview or in beta, with maturity stated. | [[Workstream-Index]] |
| R-032 | Data location: no mandatory residency. A location in Canada is preferred where it fits. | [[Data-Classes]] |
| R-033 | There is one Human principal. Additional test users may be introduced for data gathering and hardening. | [[Authority-Model]] |
| R-034 | Executives may collaborate in shared threads. The Human need not read all threads and can inspect any of them. | [[Collaboration-Record]] |
| R-035 | The Human and CEO receive plain language. Technical vocabulary goes to roles that need it. | [[Role-Scoped-Memory]] |
