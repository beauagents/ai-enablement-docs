---
source_id: SRC-finops-anomaly-management
title: "Anomaly Management FinOps Framework Capability"
creators: []
url: https://www.finops.org/framework/capabilities/anomaly-management/
date_or_version: "not stated on page"
kind: guidance
quality_class: Q2
retrieved: 2026-10-01
parse_status: summary-extracted
capture_status: not-captured
rights_status: unverified
archive_manifest: "[[ARC-finops-anomaly-management]]"
supersedes:
superseded_by:
used_by_workstreams:
  - WS17
---

# Source record: Anomaly Management FinOps Framework Capability

## Metadata

| Field | Value |
|---|---|
| Source ID | SRC-finops-anomaly-management |
| Title | Anomaly Management FinOps Framework Capability |
| Creators or publisher | not stated on page |
| URL | <https://www.finops.org/framework/capabilities/anomaly-management/> |
| Date or version | not stated on page |
| Kind | guidance |
| Quality class | Q2. Framework capability page. Publisher is not stated on the page. The host is finops.org. See [[Source-Quality-Classes]]. |
| Retrieved | 2026-10-01 |

## Summary

Anomaly Management enables FinOps teams to detect, identify, clarify, alert on, and manage unexpected cost events in a timely manner to minimize business impact. It involves tools or reports to identify unexpected spending, distribute anomaly alerts, and investigate and resolve anomalous usage or cost. Effective anomaly detection examines aggregate usage and usage within subcategories, supported by cost allocation metadata and appropriate granularity. Managing and resolving anomalies typically involves investigation, environmental changes, adjusted cost expectations, or documenting the reasons for acknowledging an anomaly.

Extraction note: the summary and evidence below were extracted from the retrieved page text on 2026-10-01 by an AI assistant. They state what the page states, they have not been independently verified, and they need a second-pass review before any claim beyond the evidence block is labelled FACT.

## Parsed evidence

- Anomaly Management includes detecting anomalies, enabling anomaly detection, and managing anomalies. ^ev-1
- Crawl maturity includes manually checking for anomalous spending, reacting more than a week after anomalies occur, and using budget alerts instead of an anomaly detection service. ^ev-2
- Walk maturity includes automated detection or reporting, context-relevant thresholds, cost allocation metadata for segmentation, automatic routing to responsible teams, and documenting anomaly outcomes. ^ev-3
- Run maturity includes mature anomaly detection tooling, automated detection or resolution suggestions, integration with event management or ticketing systems, iterative threshold updates, and captured results and resolutions. ^ev-4
- Measures of success include anomaly counts, false-positive and missed-anomaly identification, anomaly-associated cost, mean time to detect, mean time to notify, duration of unresolved anomalies, and time to investigate and address anomalies. ^ev-5
- The Anomaly Detection Rate formula is Total Cost of Anomaly Spikes divided by Total AI Spend, with green defined as less than 2%, yellow as 2–7%, and red as greater than 7%. ^ev-6

## Evidence locations

- Page: <https://www.finops.org/framework/capabilities/anomaly-management/>. Section-level locators are pending a full parse.

## Limitations

The page does not state a publisher or author, date, or version. It does not establish a single required anomaly detection tool, universal threshold, or mandatory resolution process.

- Parse status is summary-extracted. The full text has not been parsed into this record.

## Conflicts

None recorded. No cross-source comparison has been performed yet.

## Rights and access

Rights status: unverified. No full text is reproduced here. See [[ARC-finops-anomaly-management]] for capture status.

## Relationships

- Archive manifest: [[ARC-finops-anomaly-management]]
- Registry: [[Source-Registry]]
- Cited by vault notes: [[Cost-Governance]], [[Emergency-Materiality]], [[WS17-Cost-Governance-and-Resource-Arbitrage]]

## Workstream usage

- [[WS17-Cost-Governance-and-Resource-Arbitrage]]

## Verification log

| Date | Action | Result |
|---|---|---|
| 2026-10-01 | Page text retrieved and key statements extracted | summary-extracted |
