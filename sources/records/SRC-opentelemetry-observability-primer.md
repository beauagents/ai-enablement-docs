---
source_id: SRC-opentelemetry-observability-primer
title: "Observability primer"
creators:
  - OpenTelemetry
url: https://opentelemetry.io/docs/concepts/observability-primer/
date_or_version: "April 23, 2026"
kind: specification
quality_class: Q1
retrieved: 2026-10-01
parse_status: summary-extracted
capture_status: not-captured
rights_status: unverified
archive_manifest: "[[ARC-opentelemetry-observability-primer]]"
supersedes:
superseded_by:
used_by_workstreams:
  - WS14
---

# Source record: Observability primer

## Metadata

| Field | Value |
|---|---|
| Source ID | SRC-opentelemetry-observability-primer |
| Title | Observability primer |
| Creators or publisher | OpenTelemetry |
| URL | <https://opentelemetry.io/docs/concepts/observability-primer/> |
| Date or version | April 23, 2026 |
| Kind | specification |
| Quality class | Q1. Open specification project concept page. See [[Source-Quality-Classes]]. |
| Retrieved | 2026-10-01 |

## Summary

Observability lets you understand a system from the outside, ask questions without knowing its inner workings, troubleshoot novel problems, and answer why something is happening. Proper instrumentation requires application code to emit signals such as traces, metrics, and logs, and OpenTelemetry is the mechanism by which application code is instrumented to help make a system observable. Reliability concerns whether a service does what users expect, while metrics, service level indicators, and service level objectives provide measurements and communicate reliability. Distributed tracing records how a request moves through multiple services using logs, spans, and traces.

Extraction note: the summary and evidence below were extracted from the retrieved page text on 2026-10-01 by an AI assistant. They state what the page states, they have not been independently verified, and they need a second-pass review before any claim beyond the evidence block is labelled FACT.

## Parsed evidence

- Telemetry is data emitted from a system and its behavior, including traces, metrics, and logs. ^ev-1
- Metrics are aggregations over time of numeric data about infrastructure or applications, such as system error rate, CPU utilization, and request rate. ^ev-2
- A span represents a single unit of work or operation and contains a name, time-related data, structured log messages, and metadata. ^ev-3
- A distributed trace records the path taken by a single request as it propagates through multiple services. ^ev-4
- A trace consists of one or more spans, with the first span representing the root span. ^ev-5
- Logs are timestamped messages emitted by services or other components and are more useful when included in a span or correlated with a trace and a span. ^ev-6

## Evidence locations

- Page: <https://opentelemetry.io/docs/concepts/observability-primer/>. Section-level locators are pending a full parse.

## Limitations

The page does not establish implementation procedures, product comparisons, or specific reliability targets. It also does not provide a complete reference for all OpenTelemetry concepts beyond the observability topics described.

- Parse status is summary-extracted. The full text has not been parsed into this record.

## Conflicts

None recorded. No cross-source comparison has been performed yet.

## Rights and access

Rights status: unverified. No full text is reproduced here. See [[ARC-opentelemetry-observability-primer]] for capture status.

## Relationships

- Archive manifest: [[ARC-opentelemetry-observability-primer]]
- Registry: [[Source-Registry]]
- Cited by vault notes: [[Observability-vs-Audit]], [[WS14-Observability-Auditability-and-Evidence]]

## Workstream usage

- [[WS14-Observability-Auditability-and-Evidence]]

## Verification log

| Date | Action | Result |
|---|---|---|
| 2026-10-01 | Page text retrieved and key statements extracted | summary-extracted |
