---
chunk_id: visibility-observability-vs-audit-000
parent_document: vault/05-Visibility/Observability-vs-Audit.md
heading_path: Observability versus Audit
document_version: 0.1.0
status: scaffold
authority: informative
audience:
  - ceo-agent
  - cto-agent
  - coo-agent
access_scope:
  - visibility
sensitivity: internal
labels_status: provisional
source_ids:
  - SRC-nist-sp800-53
  - SRC-opentelemetry-observability-primer
  - SRC-w3c-prov-overview
parent_section_hash: 23ea7e0bc4f53970
effective_date:
supersedes:
review_required: true
---

Parent: [[Observability-vs-Audit]]

Both are required. They answer different questions.

| | Observability | Audit |
|---|---|---|
| Question | How is the system behaving, and why? | Who did what, when, why and under which authority? |
| Content | Traces, metrics, logs | Attributable, append-only records |
| Typical use | Troubleshooting, reliability | Accountability, evidence |
| Completeness | May be sampled or aggregated | Required for significant actions |

[USER REQUIREMENT] Visibility must be full across both. Neither chat transcripts nor operational telemetry alone satisfy it.

[FACT] OpenTelemetry describes telemetry as data emitted from a system, including traces, metrics and logs, and describes a distributed trace as the path of a single request across services. See [[SRC-opentelemetry-observability-primer]].

[FACT] SP 800-53 Rev. 5 includes an Audit and Accountability control family. See [[SRC-nist-sp800-53]]. Control text is [UNVERIFIED] until parsed in [[WS14-Observability-Auditability-and-Evidence]].

[FACT] W3C PROV is a family of documents defining a provenance model for interoperable provenance interchange. See [[SRC-w3c-prov-overview]]. Adoption is not decided.
