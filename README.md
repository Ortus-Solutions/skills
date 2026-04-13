# Ortus Skills

> Production-ready Claude Code skills from Ortus Solutions for frontend engineering, language expertise, BoxLang development, security analysis, code review, and technical documentation.

This repository follows a flat `skills/<slug>/SKILL.md` layout and works as a Claude Code plugin marketplace as well as skills.sh-compatible tooling.

---

## Quick Install

### Claude Code Plugin (recommended)

```bash
# Add the marketplace and install the plugin
/plugin marketplace add Ortus-Solutions/skills
/plugin install ortus-agent-skills@ortus-agent-skills
```

### npx skills CLI

```bash
# Install all Ortus skills
npx skills add Ortus-Solutions/skills

# Install a single skill
npx skills add Ortus-Solutions/skills/skills/vuejs-expert
npx skills add Ortus-Solutions/skills/skills/boxlang-expert
npx skills add Ortus-Solutions/skills/skills/security-expert
```

---

## Included Skills

| Skill | What It Covers |
|-------|----------------|
| [`alpinejs-expert`](./skills/alpinejs-expert/SKILL.md) | Alpine.js component state, directives, progressive enhancement, accessibility |
| [`bootstrap-expert`](./skills/bootstrap-expert/SKILL.md) | Bootstrap grid, components, upgrades, theming, JavaScript integration |
| [`boxlang-expert`](./skills/boxlang-expert/SKILL.md) | BoxLang idioms, modules, async flows, runtime integration, Ortus conventions |
| [`code-documenter`](./skills/code-documenter/SKILL.md) | API docs, docstrings, runbooks, onboarding docs, documentation consistency |
| [`code-reviewer`](./skills/code-reviewer/SKILL.md) | Severity-ranked code review, regression risk, correctness, performance, test gaps |
| [`java-expert`](./skills/java-expert/SKILL.md) | Java service design, concurrency, profiling, testing, production hardening |
| [`javascript-expert`](./skills/javascript-expert/SKILL.md) | Modern JavaScript design, async flows, module boundaries, runtime safety |
| [`security-expert`](./skills/security-expert/SKILL.md) | Threat modeling, auth, validation, secrets, secure coding remediation |
| [`tailwind-expert`](./skills/tailwind-expert/SKILL.md) | Tailwind tokens, utility composition, responsive patterns, accessibility styling |
| [`typescript-expert`](./skills/typescript-expert/SKILL.md) | Type modeling, strict mode adoption, generics, inference, runtime boundary safety |
| [`vite-expert`](./skills/vite-expert/SKILL.md) | Vite configuration, HMR, bundling strategy, env handling, Vitest integration |
| [`vuejs-expert`](./skills/vuejs-expert/SKILL.md) | Vue 3 Composition API, component architecture, state ownership, rendering patterns |

---

## Repository Layout

| Path | Purpose |
|------|---------|
| [`skills/`](./skills/) | Canonical skill source folders |
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
| Ortus Solutions | https://www.ortussolutions.com/ |
| BoxLang Documentation | https://boxlang.ortusbooks.com/ |
| ColdBox Documentation | https://coldbox.ortusbooks.com/ |
| Claude Code Plugin Docs | https://code.claude.com/docs/en/plugins |
| skills.sh | https://skills.sh |
