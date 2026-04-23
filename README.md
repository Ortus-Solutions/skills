# Ortus Skills

> Production-ready Claude Code skills from Ortus Solutions for frontend engineering, language expertise, BoxLang development, security analysis, code review, and technical documentation.

This repository follows a flat `<slug>/SKILL.md` layout at the repository root and works as a Claude Code plugin marketplace as well as skills.sh-compatible tooling.

**You can find all our skills published to our online directory at https://skills.boxlang.io/.**

---

## Quick Install

### Claude Code Plugin (recommended)

```bash
# Add the marketplace and install the plugin
/plugin marketplace add Ortus-Solutions/skills
/plugin install ortus-agent-skills@ortus-agent-skills
```

### ColdBox CLI

```bash
# Install the ColdBox CLI if you haven't already
box install coldbox-cli

# Install AI integration into your app
# This reads your app, box.json and installs skills based on your stack and preferences
coldbox ai install

# Skills Management

# List installed skills
coldbox ai skills list
# Add a skill
coldbox ai skills add Ortus-Solutions/skills/vuejs-expert
# Remove a skill
coldbox ai skills remove vuejs-expert
```

All skills are installed at `.agents/skills/` in your project.

### npx skills CLI

```bash
# Install all Ortus skills
npx skills add Ortus-Solutions/skills

# Install a single skill
npx skills add Ortus-Solutions/skills/vuejs-expert
npx skills add Ortus-Solutions/skills/security-expert
```

---

## Included Skills

| Skill | What It Covers |
|-------|----------------|
| [`alpinejs-expert`](./alpinejs-expert/SKILL.md) | Alpine.js component state, directives, progressive enhancement, accessibility |
| [`bootstrap-expert`](./bootstrap-expert/SKILL.md) | Bootstrap grid, components, upgrades, theming, JavaScript integration |
| [`code-documenter`](./code-documenter/SKILL.md) | API docs, docstrings, runbooks, onboarding docs, documentation consistency |
| [`code-reviewer`](./code-reviewer/SKILL.md) | Severity-ranked code review, regression risk, correctness, performance, test gaps |
| [`gitbook-docs-expert`](./gitbook-docs-expert/SKILL.md) | GitBook structure, information architecture, markdown consistency, docs publishing workflows |
| [`github-action-authoring`](./github-action-authoring/SKILL.md) | GitHub Actions authoring, workflow design, reusable actions, CI reliability and security |
| [`java-expert`](./java-expert/SKILL.md) | Java service design, concurrency, profiling, testing, production hardening |
| [`javascript-expert`](./javascript-expert/SKILL.md) | Modern JavaScript design, async flows, module boundaries, runtime safety |
| [`ortus-java-coding-standards`](./ortus-java-coding-standards/SKILL.md) | Ortus Java coding conventions, style consistency, maintainability and quality guardrails |
| [`security-expert`](./security-expert/SKILL.md) | Threat modeling, auth, validation, secrets, secure coding remediation |
| [`tailwind-expert`](./tailwind-expert/SKILL.md) | Tailwind tokens, utility composition, responsive patterns, accessibility styling |
| [`typescript-expert`](./typescript-expert/SKILL.md) | Type modeling, strict mode adoption, generics, inference, runtime boundary safety |
| [`vite-expert`](./vite-expert/SKILL.md) | Vite configuration, HMR, bundling strategy, env handling, Vitest integration |
| [`vuejs-expert`](./vuejs-expert/SKILL.md) | Vue 3 Composition API, component architecture, state ownership, rendering patterns |

---

## Repository Layout

| Path | Purpose |
|------|---------|
| [`alpinejs-expert/`](./alpinejs-expert/) | Skill folder |
| [`bootstrap-expert/`](./bootstrap-expert/) | Skill folder |
| [`code-documenter/`](./code-documenter/) | Skill folder |
| [`code-reviewer/`](./code-reviewer/) | Skill folder |
| [`gitbook-docs-expert/`](./gitbook-docs-expert/) | Skill folder |
| [`github-action-authoring/`](./github-action-authoring/) | Skill folder |
| [`java-expert/`](./java-expert/) | Skill folder |
| [`javascript-expert/`](./javascript-expert/) | Skill folder |
| [`ortus-java-coding-standards/`](./ortus-java-coding-standards/) | Skill folder |
| [`security-expert/`](./security-expert/) | Skill folder |
| [`tailwind-expert/`](./tailwind-expert/) | Skill folder |
| [`typescript-expert/`](./typescript-expert/) | Skill folder |
| [`vite-expert/`](./vite-expert/) | Skill folder |
| [`vuejs-expert/`](./vuejs-expert/) | Skill folder |
| [`.claude-plugin/plugin.json`](./.claude-plugin/plugin.json) | Claude Code plugin manifest |
| [`.claude-plugin/marketplace.json`](./.claude-plugin/marketplace.json) | Claude Code marketplace catalog |
| [`.mcp.json`](./.mcp.json) | Ortus documentation MCP endpoints |

---

## MCP Servers

The bundled [`.mcp.json`](./.mcp.json) points to Ortus GitBook MCP servers for:

- BoxLang
- ColdBox
- TestBox
- WireBox
- CacheBox
- LogBox
- DocBox

---

## Resources

| Resource | Link |
|----------|------|
| Skills Publishing Site | https://skills.boxlang.io/ |
| Ortus Solutions | https://www.ortussolutions.com/ |
| ColdBox Skills Repository | https://github.com/coldbox/skills |
| BoxLang Skills Repository | https://github.com/ortus-boxlang/skills |
| BoxLang Documentation | https://boxlang.ortusbooks.com/ |
| ColdBox Documentation | https://coldbox.ortusbooks.com/ |
| Claude Code Plugin Docs | https://code.claude.com/docs/en/plugins |
| skills.sh | https://skills.sh |
