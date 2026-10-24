# Awesome Microsoft 365 Copilot [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Curated guides, prompts, agent skills, governance and endpoint resources for Microsoft 365 Copilot and its agents.

Maintained by [Deep Shah](https://shahdeep.ca). Everything here is checked by a human before it is added. Corrections are welcome.

## Contents

- [Official documentation](#official-documentation)
- [Security and governance](#security-and-governance)
- [Adoption and readiness](#adoption-and-readiness)
- [Prompts](#prompts)
- [Agents and extensibility](#agents-and-extensibility)
- [Samples and tools](#samples-and-tools)
- [Scripts and automation](#scripts-and-automation)
- [Agent skills](#agent-skills)
- [Updates](#updates)
- [Community](#community)

## Official documentation

- [Microsoft 365 Copilot documentation](https://learn.microsoft.com/copilot/microsoft-365/) - The main Microsoft Learn hub for admins and users.
- [Copilot Control System](https://learn.microsoft.com/copilot/microsoft-365/copilot-control-system/overview) - Overview of the controls for securing, managing and measuring Copilot and agents.
- [What's new for Microsoft 365 Copilot developers](https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/whats-new) - Monthly changelog for extensibility features.
- [Microsoft Learn samples gallery](https://learn.microsoft.com/en-us/samples/browse/) - Searchable code samples across Microsoft products.
- [Microsoft 365 Developer on YouTube](https://www.youtube.com/@Microsoft365Developer) - Official videos for Copilot extensibility.

## Security and governance

- [Microsoft 365 Copilot oversharing blueprint](https://learn.microsoft.com/en-us/copilot/microsoft-365/microsoft-365-copilot-blueprint-oversharing) - Step-by-step guidance to find and fix oversharing before and after rollout ([PDF](https://aka.ms/Copilot/SecureGovernBlueprintPDF)).
- [Secure and govern Copilot foundations](https://learn.microsoft.com/en-us/microsoft-365/copilot/secure-govern-copilot-foundational-deployment-guidance) - Foundational deployment guidance for security and governance.
- [Configure a secure and governed data foundation](https://learn.microsoft.com/en-us/microsoft-365/copilot/configure-secure-governed-data-foundation-microsoft-365-copilot) - Data-protection setup to complete before enabling Copilot.
- [Microsoft Purview documentation](https://learn.microsoft.com/en-us/purview/) - Sensitivity labels, DLP and compliance controls that Copilot respects.
- [Purview secure by default](https://learn.microsoft.com/en-us/purview/deploymentmodels/depmod-securebydefault-intro) - A deployment model for protecting data by default.
- [SharePoint Advanced Management](https://learn.microsoft.com/en-us/sharepoint/advanced-management) - Site-level controls and reports used to reduce oversharing.
- [Zero Trust Assessment](https://microsoft.github.io/zerotrustassessment/guide) - Open-source assessment of a tenant's Zero Trust posture.

## Adoption and readiness

- [Copilot Success Kit](https://adoption.microsoft.com/copilot/success-kit) - Microsoft's adoption playbooks, templates and training material.
- [Scenario Library](https://adoption.microsoft.com/en-gb/scenario-library/) - Role-based Copilot scenarios with success measures.
- [Sample solution gallery](https://adoption.microsoft.com/sample-solution-gallery/?keyword=&sort-by=updateDateTime-true&page=1&product=Microsoft+365+Copilot) - Ready-made solutions filtered to Microsoft 365 Copilot.
- [Microsoft 365 Copilot licensing explained](https://practical365.com/microsoft-365-copilot-licensing/) - Practical overview of license options and gotchas.

## Prompts

- [Copilot Prompt Gallery](https://m365.cloud.microsoft/copilot-prompts) - Microsoft's built-in library of prompts by app and role ([docs](https://learn.microsoft.com/en-us/microsoft-365/copilot/copilot-prompt-gallery)).
- [Export prompts from the gallery](https://learn.microsoft.com/en-us/microsoft-365/copilot/copilot-prompt-gallery-export-prompts) - How admins export prompt content.
- [CIAOPS prompt posts](https://blog.ciaops.com/tag/prompts/) - Community prompt collections from an MVP.
- [Prompts in this repo](prompts/README.md) - Original prompts for admins and security teams.

## Agents and extensibility

- [Work IQ MCP overview](https://learn.microsoft.com/en-us/microsoft-365-copilot/extensibility/work-iq/mcp/overview) - Use Microsoft 365 work data through Model Context Protocol.
- [Microsoft Agent 365](https://www.microsoft.com/en-us/microsoft-agent-365) - Microsoft's control plane for registering and governing agents.
- [Add skills to declarative agents](https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/build-declarative-agents-add-custom-skills) - Preview guidance for packaging agent skills.
- [Add skills in Agent Builder](https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/agent-builder-add-skills) - Upload skills to agents built in Agent Builder.
- [Customize Copilot Cowork](https://learn.microsoft.com/en-us/microsoft-365/copilot/cowork/cowork-customize) - Add your own skills to Cowork.
- [Copilot Cowork skills lab](https://microsoft.github.io/copilot-camp/pages/copilot-cowork/01-cowork-skills/) - Hands-on lab for writing Cowork skills.
- [Modern Copilot Studio agent skills](https://microsoft.github.io/mcscatblog/posts/modern-mcs-agent-skills/) - Copilot Studio team post on skills for agents.
- [Agent Skills specification](https://agentskills.io) - The open SKILL.md format shared by several assistants.

## Samples and tools

- [Copilot Studio Samples](https://microsoft.github.io/CopilotStudioSamples/) - Official samples site ([GitHub](https://github.com/microsoft/CopilotStudioSamples)).
- [copilot-pro-dev-samples](https://github.com/pnp/copilot-pro-dev-samples) - Community samples for declarative agents and plugins from PnP.
- [Microsoft Teams samples](https://github.com/OfficeDev/Microsoft-Teams-Samples) - Teams app and agent samples.
- [agentsbestpractices](https://github.com/luishdemetrio/agentsbestpractices) - Best-practice notes for building agents.

## Scripts and automation

- [Find inactive Copilot users](https://practical365.com/inactive-copilot-users/) - Script walkthrough for reclaiming unused licenses; some readers report Graph audit errors, so test first.
- [Original skills in this repo](skills/README.md) - Skills that guide an assistant through readiness, oversharing and licence reviews.

## Agent skills

Skills use the open `SKILL.md` format, so the same folder can work in several assistants. See [skills/README.md](skills/README.md) for how to install them in Copilot Cowork, Agent Builder, Copilot Studio, declarative agents, Claude, Gemini CLI and Codex.

## Updates

Changes that affect admins and builders are logged in [UPDATES.md](UPDATES.md).

## Community

- [Microsoft 365 Copilot Connection](https://m365copilotconnection.substack.com/) - Newsletter covering monthly Copilot changes.
- [A Guide to Cloud](https://www.aguidetocloud.com/blog/) - Blog with monthly Copilot update summaries.

See [CONTRIBUTING.md](CONTRIBUTING.md) to add a resource.
