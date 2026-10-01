---
source_id: SRC-fowler-circuit-breaker
title: "Circuit Breaker"
creators:
  - Martin Fowler
url: https://martinfowler.com/bliki/CircuitBreaker.html
date_or_version: "6 March 2014"
kind: practitioner-article
quality_class: Q4
retrieved: 2026-10-01
parse_status: summary-extracted
capture_status: not-captured
rights_status: unverified
archive_manifest: "[[ARC-fowler-circuit-breaker]]"
supersedes:
superseded_by:
used_by_workstreams:
  - WS10
  - WS17
---

# Source record: Circuit Breaker

## Metadata

| Field | Value |
|---|---|
| Source ID | SRC-fowler-circuit-breaker |
| Title | Circuit Breaker |
| Creators or publisher | Martin Fowler |
| URL | <https://martinfowler.com/bliki/CircuitBreaker.html> |
| Date or version | 6 March 2014 |
| Kind | practitioner-article |
| Quality class | Q4. Named-expert practitioner article. See [[Source-Quality-Classes]]. |
| Retrieved | 2026-10-01 |

## Summary

The Circuit Breaker pattern wraps protected calls, monitors failures, and stops making calls after failures reach a threshold. An open circuit returns an error without invoking the protected call, helping prevent resource exhaustion and cascading failures. A self-resetting circuit breaker can enter a half-open state after an interval and make a trial call to determine whether the underlying service has recovered. Circuit breakers can also support monitoring, asynchronous communications, thread pools, queues, and different failure thresholds.

Extraction note: the summary and evidence below were extracted from the retrieved page text on 2026-10-01 by an AI assistant. They state what the page states, they have not been independently verified, and they need a second-pass review before any claim beyond the evidence block is labelled FACT.

## Parsed evidence

- Remote calls can fail or hang until a timeout, and many callers waiting on an unresponsive supplier can cause cascading failures. ^ev-1
- The example circuit breaker uses a failure threshold of 5, an invocation timeout of 0.01, and a reset timeout of 0.1 for the self-resetting version. ^ev-2
- The circuit has closed, open, and, in the self-resetting version, half-open states. ^ev-3
- Successful calls reset the failure counter, while timeout failures increment it. ^ev-4
- Circuit breakers may trip based on error frequency, such as a 50% failure rate, or use different thresholds for different errors. ^ev-5
- Circuit breakers are useful for monitoring, and operations staff should be able to trip or reset them. ^ev-6

## Evidence locations

- Page: <https://martinfowler.com/bliki/CircuitBreaker.html>. Section-level locators are pending a full parse.

## Limitations

The page states that its example is a simple explanatory example and that practical circuit breakers provide more features and parameterization. It does not establish that all errors should trip the circuit; some errors should be handled as normal application logic.

- Parse status is summary-extracted. The full text has not been parsed into this record.

## Conflicts

None recorded. No cross-source comparison has been performed yet.

## Rights and access

Rights status: unverified. No full text is reproduced here. See [[ARC-fowler-circuit-breaker]] for capture status.

## Relationships

- Archive manifest: [[ARC-fowler-circuit-breaker]]
- Registry: [[Source-Registry]]
- Cited by vault notes: [[Cost-Governance]], [[Emergency-Authority]], [[Emergency-Materiality]], [[Execution-and-Replacement]], [[Glossary]], [[WS10-Workflow-Orchestration-and-Replaceable-Execution]], [[WS17-Cost-Governance-and-Resource-Arbitrage]]

## Workstream usage

- [[WS10-Workflow-Orchestration-and-Replaceable-Execution]]
- [[WS17-Cost-Governance-and-Resource-Arbitrage]]

## Verification log

| Date | Action | Result |
|---|---|---|
| 2026-10-01 | Page text retrieved and key statements extracted | summary-extracted |
