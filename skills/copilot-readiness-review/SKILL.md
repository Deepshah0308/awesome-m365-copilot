---
name: copilot-readiness-review
description: Guide a Microsoft 365 Copilot readiness review before rollout and produce a prioritised gap list. Use when someone asks if their tenant is ready for Copilot.
---

# Copilot readiness review

Ask for what the user can share (admin centre screenshots, exports, notes). Never ask for passwords or tokens.

1. **Licensing and scope.** Which users and groups are in the pilot? Are licences assigned to them only?
2. **Data access.** Are there sites, teams or mailboxes with broad access (everyone, large groups, anonymous links)? Note the evidence and who owns each.
3. **Labels and protection.** Are sensitivity labels published and used on high-value content? Is DLP covering Copilot interactions?
4. **Identity.** Are Conditional Access and MFA applied to Copilot users? Are guest accounts reviewed?
5. **Devices.** Are pilot devices compliant and managed? Are app protection policies applied on mobile?
6. **Agents.** Who can create and share agents? Is there an inventory and owner for each?
7. **Monitoring.** Are audit logs on and is someone responsible for reviewing them?
8. **People.** Is there training, a champion network and a way to collect feedback?

Output: a table with Area, Finding, Risk (High/Medium/Low), Fix, Owner. Mark anything you could not check as "Not checked", never as passed. Finish with the top three actions before go-live.
