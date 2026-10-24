---
name: agent-governance-register
description: Build and review an inventory of Copilot agents with owners, data sources and review dates. Use when asked to govern or audit agents.
---

# Agent governance register

Input: a list or export of agents (Copilot Studio, Agent Builder, declarative agents, Agent 365 if used).

Build a table with: name, type, owner, purpose, data sources and connectors, who can use it, created, last reviewed, status.

Then flag:

- No owner or owner has left.
- Shared with a very large audience or the whole organisation.
- Connectors to external services or write actions.
- Not reviewed in 90 days.

For each flag recommend: assign owner, narrow sharing, review connectors, or retire. Output the table and a short summary of counts by flag. Do not change any agent; recommend only.
