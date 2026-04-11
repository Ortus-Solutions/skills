# Ortus Skills

> Production-ready Claude and agent skills from Ortus Solutions for frontend engineering, language expertise, BoxLang development, security analysis, code review, and technical documentation.

This repository follows a flat `skills/<slug>/SKILL.md` layout and is designed to work with Claude plugin installs as well as skills.sh-compatible tooling.

---

## Quick Install

```bash
# Claude plugin install from GitHub
claude plugin install https://github.com/Ortus-Solutions/skills
```

```bash
# Skills-only install
npx skills add Ortus-Solutions/skills
```

```bash
# Install a single skill
npx skills add Ortus-Solutions/skills/skills/vuejs-expert
```

---

## Included Skills

| Skill | What It Covers |
|---|---|
| [`vite-expert`](./skills/vite-expert/SKILL.md) | Vite configuration, HMR, bundling strategy, env handling, Vitest integration |
| [`alpinejs-expert`](./skills/alpinejs-expert/SKILL.md) | Alpine.js component state, directives, progressive enhancement, accessibility |
| [`vuejs-expert`](./skills/vuejs-expert/SKILL.md) | Vue 3 Composition API, component architecture, state ownership, rendering patterns |
| [`tailwind-expert`](./skills/tailwind-expert/SKILL.md) | Tailwind tokens, utility composition, responsive patterns, accessibility styling |
| [`bootstrap-expert`](./skills/bootstrap-expert/SKILL.md) | Bootstrap grid, components, upgrades, theming, JavaScript integration |
| [`javascript-expert`](./skills/javascript-expert/SKILL.md) | Modern JavaScript design, async flows, module boundaries, runtime safety |
| [`typescript-expert`](./skills/typescript-expert/SKILL.md) | Type modeling, strict mode adoption, generics, inference, runtime boundary safety |
| [`java-expert`](./skills/java-expert/SKILL.md) | Java service design, concurrency, profiling, testing, production hardening |
| [`boxlang-expert`](./skills/boxlang-expert/SKILL.md) | BoxLang idioms, modules, async flows, runtime integration, Ortus conventions |
| [`security-expert`](./skills/security-expert/SKILL.md) | Threat modeling, auth, validation, secrets, secure coding remediation |
| [`code-reviewer`](./skills/code-reviewer/SKILL.md) | Severity-ranked code review, regression risk, correctness, performance, test gaps |
| [`code-documenter`](./skills/code-documenter/SKILL.md) | API docs, docstrings, runbooks, onboarding docs, documentation consistency |

---

## Repository Layout

| Path | Purpose |
|---|---|
| [`skills/`](./skills/) | Canonical skill source folders |
| [`.claude-plugin/plugin.json`](./.claude-plugin/plugin.json) | Claude plugin manifest |
| [`.claude-plugin/marketplace.json`](./.claude-plugin/marketplace.json) | Marketplace metadata for plugin distribution |
| [`.claude/marketplace.json`](./.claude/marketplace.json) | Additional marketplace descriptor |
| [`.mcp.json`](./.mcp.json) | Ortus documentation MCP endpoints |

---

## Notes

- The source of truth is `skills/*/SKILL.md`.
- This repository does not keep duplicate mirrored skill files under `.claude/skills/`.
- The plugin manifest currently registers `./skills/`, which covers all 12 skills in this repo.

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

- [Ortus Solutions](https://www.ortussolutions.com/)
- [BoxLang Documentation](https://boxlang.ortusbooks.com/)
- [ColdBox Documentation](https://coldbox.ortusbooks.com/)
- [skills.sh](https://skills.sh)
