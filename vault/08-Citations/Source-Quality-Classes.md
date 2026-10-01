---
doc_id: citations.quality-classes
title: Source Quality Classes
status: scaffold
authority: normative-draft
audience:
  - human
  - ceo-agent
access_scope:
  - citations
sensitivity: internal
owner: human-principal
version: 0.1.0
created: 2026-10-01
last_reviewed:
review_required: true
supersedes:
---

# Source Quality Classes

Classes describe provenance and incentive, not truth. A lower class can still be cited when labelled.

| Class | Description | Examples of kinds |
|---|---|---|
| Q1 | Formal standard from a standards body, or an open specification maintained by its governing project (the record states which) | standard, specification |
| Q2 | Official guidance from a public body, intergovernmental body or recognized professional community | guidance |
| Q3 | Research publication, including preprints (peer review status stated in the record) | preprint |
| Q4 | Practitioner article by a named expert | practitioner-article |
| Q5 | Product or provider documentation. Useful for what a capability does and its stated limits. Not neutral on claims about its own value. | product-documentation |
| Q6 | Community proposal or convention without a formal standards process | proposal |

## Rules

- Every record states its class and the reasoning.
- Q5 sources document capabilities and stated limits. They are not used to justify architectural choices on the main branch.
- Preprints are labelled as such ([[SRC-arxiv-understanding-sycophancy]] and [[SRC-arxiv-concrete-problems-ai-safety]] are preprints in this seed set).
- A claim resting only on Q4 to Q6 sources is flagged for review.
