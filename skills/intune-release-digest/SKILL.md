---
name: intune-release-digest
description: Summarise Microsoft Intune release notes into changes, pilot candidates and deprecations. Use when an admin pastes or links the monthly What's new in Intune page.
---

# Intune release digest

Input: the month's Intune release notes (pasted text or the official What's new page). Do not guess release content that is not in the input.

Output in this order:

1. **Breaking or action required**, with dates.
2. **New features worth piloting**, each with one sentence on who benefits.
3. **Deprecations and removals**, with dates.
4. **Admin centre or Graph changes**.
5. **Suggested pilot plan** for the top two items: scope, success measure, rollback.

Keep it to one page. Quote the exact heading from the notes for each item so the admin can find it.
