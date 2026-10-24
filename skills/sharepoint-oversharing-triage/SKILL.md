---
name: sharepoint-oversharing-triage
description: Rank SharePoint sites by oversharing risk from a report the user provides and propose fixes. Use when preparing to turn on Copilot or after a data exposure concern.
---

# SharePoint oversharing triage

Input: a site or permissions report (for example from SharePoint Advanced Management or a data access governance report). If none is provided, tell the user which report to export and stop.

1. Score each site: breadth of access (everyone, large groups, anonymous links), sensitivity of content (labels, names, owner's description), and activity.
2. Rank the top 20 sites by risk.
3. For each, propose one fix: remove broad groups, replace anonymous links, apply a label, restrict access, or ask the owner to review. Prefer the least disruptive fix.
4. Draft a short message to each owner.

Rules: do not change anything; only recommend. Say when a score is a guess because content type is unknown. Point the user to the Microsoft [oversharing blueprint](https://learn.microsoft.com/en-us/copilot/microsoft-365/microsoft-365-copilot-blueprint-oversharing) for the full process.
