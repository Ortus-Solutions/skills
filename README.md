# Ortus Skills

Production-ready Claude skills from Ortus Solutions for frontend engineering, language expertise, BoxLang development, security analysis, code review, and documentation.

## Included Skills

- `vite-expert`
- `alpinejs-expert`
- `vuejs-expert`
- `tailwind-expert`
- `bootstrap-expert`
- `javascript-expert`
- `typescript-expert`
- `java-expert`
- `boxlang-expert`
- `security-expert`
- `code-reviewer`
- `code-documenter`

## Install Options

### Claude Plugin Install

```bash
claude plugin install https://github.com/Ortus-Solutions/skills
```

### Marketplace Install

```bash
/plugin marketplace add Ortus-Solutions/skills
/plugin install ortus-agent-skills@Ortus-Solutions
```

### Skills-only Install

```bash
npx skills add Ortus-Solutions/skills
```

### Single Skill Install

```bash
npx skills add Ortus-Solutions/skills/skills/vuejs-expert
```

## Repository Layout

- `skills/<skill>/SKILL.md` - canonical source skills
- `.claude-plugin/plugin.json` - plugin manifest
- `.mcp.json` - docs MCP endpoints

## Notes

- The canonical source of truth is `skills/*/SKILL.md`.
- MCP endpoints point to Ortus GitBook documentation services.
