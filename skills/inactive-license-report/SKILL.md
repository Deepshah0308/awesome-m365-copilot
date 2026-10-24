---
name: inactive-license-report
description: Turn a Copilot usage export into a list of licences to reclaim or re-engage. Use when asked about unused Copilot licences or adoption gaps.
---

# Inactive licence report

Input: a user-level Copilot usage export (admin centre report or Microsoft Graph report) with last activity dates. If the user has none, explain where to get one and check the current Microsoft docs for the report name, since endpoints change.

1. Define "inactive" with the user (default: no activity in 30 days, and licence assigned longer than 30 days).
2. List inactive users with department, licence assigned date and last activity.
3. Split into: new (give time), at risk (send enablement), and reclaim candidates.
4. Draft one friendly message per group. Do not shame individuals.
5. State the estimated saving only if the user gives a price per licence.

Privacy: use the data only for licence decisions, tell the user to check local policy on usage reporting, and never publish individual names.
