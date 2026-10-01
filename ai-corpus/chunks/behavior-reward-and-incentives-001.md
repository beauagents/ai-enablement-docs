---
chunk_id: behavior-reward-and-incentives-001
parent_document: vault/03-Agent-Behavior/Reward-and-Incentives.md
heading_path: Reward and Incentives > Why this needs care
document_version: 0.1.0
status: scaffold
authority: informative
audience:
  - ceo-agent
access_scope:
  - behavior
sensitivity: internal
labels_status: provisional
source_ids:
  - SRC-arxiv-concrete-problems-ai-safety
  - SRC-arxiv-understanding-sycophancy
parent_section_hash: a0fc9541d3967e97
effective_date:
supersedes:
review_required: true
---

Parent: [[Reward-and-Incentives#Why this needs care]]

[FACT] The paper "Concrete Problems in AI Safety" lists avoiding reward hacking as one of five practical research problems and relates it to having the wrong objective function. See [[SRC-arxiv-concrete-problems-ai-safety]].

[FACT] Human preference data can favor responses that match the user's views over truthful ones. See [[SRC-arxiv-understanding-sycophancy]].

[INFERENCE] A reward that scores approval or compliance alone can be satisfied by flattery or concealment. The design must therefore test whether the score tracks the intended outcome.
