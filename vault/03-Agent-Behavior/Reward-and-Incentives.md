---
doc_id: behavior.reward-and-incentives
title: Reward and Incentives
status: scaffold
authority: informative
audience:
  - human
  - ceo-agent
access_scope:
  - behavior
sensitivity: internal
owner: human-principal
version: 0.1.0
created: 2026-10-01
last_reviewed:
review_required: true
supersedes:
---

# Reward and Incentives

[USER REQUIREMENT] A reward system is needed to reinforce dependable service to the Human. It requires curation with citations. No framework, formula, score or metric has been selected.

## Why this needs care

[FACT] The paper "Concrete Problems in AI Safety" lists avoiding reward hacking as one of five practical research problems and relates it to having the wrong objective function. See [[SRC-arxiv-concrete-problems-ai-safety]].

[FACT] Human preference data can favor responses that match the user's views over truthful ones. See [[SRC-arxiv-understanding-sycophancy]].

[INFERENCE] A reward that scores approval or compliance alone can be satisfied by flattery or concealment. The design must therefore test whether the score tracks the intended outcome.

## Option families to compare (no selection made)

- Outcome-based rewards.
- Process and policy-compliance rewards.
- Human evaluation.
- Executive-agent or peer review.
- Independent verifier scoring.
- Delayed outcome evaluation.
- Penalties for concealment or evidence manipulation.
- Team-level versus individual incentives.
- Reliability and reputation histories.
- Reduction and restoration of delegated authority after failures and corrections.
- Credit for constructive disagreement that prevents harm.
- Credit for disclosing uncertainty and escalating within policy.
- Protection of evaluation systems from agent access or modification.
- Held-out evaluations and adversarial testing.
- Detection of sycophancy, verbosity gaming and superficial compliance.

## Open decisions

See [[Open-Questions]]. Workstream: [[WS04-Incentives-and-Rewards]].
