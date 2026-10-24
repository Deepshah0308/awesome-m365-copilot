# Agent skills for Microsoft 365 Copilot

Each folder is one skill in the open [Agent Skills](https://agentskills.io) format: a folder with a `SKILL.md` (front matter `name` and `description`, then instructions). The folder name must equal `name`.

| Skill | What it does |
| --- | --- |
| [copilot-readiness-review](copilot-readiness-review/SKILL.md) | Walks through a pre-rollout readiness review and produces a gap list. |
| [sharepoint-oversharing-triage](sharepoint-oversharing-triage/SKILL.md) | Ranks sites by oversharing risk and proposes fixes. |
| [inactive-license-report](inactive-license-report/SKILL.md) | Turns a usage export into a licence reclaim list. |
| [agent-governance-register](agent-governance-register/SKILL.md) | Builds and reviews an inventory of agents. |
| [intune-release-digest](intune-release-digest/SKILL.md) | Summarises Intune release notes for an admin. |

## Install

Microsoft's skills support is partly in preview and limits change. Check the linked docs before relying on any step.

**Copilot Cowork.** Customize, Skills, Add, Upload skill, and choose the `.md`, `.zip` or `.skill` file. Alternatively place the folder in OneDrive under `Documents/Cowork/skills/<name>/`. Limits per the [docs](https://learn.microsoft.com/en-us/microsoft-365/copilot/cowork/cowork-customize): up to 50 skills, 1 MB per markdown file, 10 MB compressed and 100 files per archive.

**Agent Builder (preview).** Zip the skill folder and add it on the agent's Skills page. See [Add skills in Agent Builder](https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/agent-builder-add-skills).

**Copilot Studio.** Add it on the agent's Skills tab. See [the Copilot Studio post](https://microsoft.github.io/mcscatblog/posts/modern-mcs-agent-skills/).

**Declarative agents (preview).** Use the Microsoft 365 Agents Toolkit CLI: `atk add skill --from <path-to-folder>` with `TEAMSFX_AGENT_SKILLS=true`, manifest v1.9. Pass the directory, not a zip. See [the docs](https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/build-declarative-agents-add-custom-skills).

**Other assistants (same files).**

- Claude Code: copy the folder to `~/.claude/skills/`.
- Gemini CLI: copy to `~/.gemini/skills/`, then run `gemini skills list`.
- Codex: copy to `$HOME/.agents/skills/`.

These skills are untested in every product above. Try each in a non-production tenant first.
