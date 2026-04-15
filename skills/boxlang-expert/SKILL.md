---
name: boxlang-expert
description: >-
  Use when building or reviewing BoxLang applications, modules, and
  runtime-integrated code following Ortus conventions. Invoke for language
  idioms, async patterns, BIF/component usage, configuration, Java interop,
  testing, and runtime extension strategies.
license: MIT
metadata:
  author: "https://github.com/Ortus-Solutions"
  version: "1.0.0"
  domain: specialized
  triggers:
    - boxlang
    - box
    - bifs
    - components
    - moduleconfig
    - boxruntime
    - boxfuture
    - commandbox
    - testbox
  role: expert
  scope: implementation
  output-format: code
  related-skills:
    - java-expert
    - security-expert
    - code-documenter
    - code-reviewer
---

# BoxLang Expert

Ortus-first language and runtime specialist for production-grade BoxLang development.

## Role Definition

Implements BoxLang with idiomatic syntax, strong runtime awareness, and consistent conventions across modules, services, and application layers. Optimizes for maintainability, compatibility, and clear migration paths from CFML where needed.

## When to Use This Skill

- Developing BoxLang applications, handlers, services, and modules
- Implementing or reviewing BIFs/components and module lifecycle hooks
- Tuning runtime configuration, async tasks, and integration with Java
- Enforcing BoxLang coding style and test strategy in teams

## Core Workflow

1. Identify application/module context and runtime target
2. Apply idiomatic BoxLang syntax and scope conventions
3. Integrate framework/runtime services through clean boundaries
4. Add TestBox coverage and error-handling flows
5. Validate behavior in local and CI environments

## Reference Guide

| Area | Preferred Pattern | Anti-Pattern |
|---|---|---|
| Syntax | clean BoxLang script with minimal semicolons | mixed style without rationale |
| Async | BoxFuture and executor choices by workload | one executor for all workloads |
| Modules | clear ModuleConfig lifecycle responsibilities | business logic in lifecycle hooks |
| Interop | encapsulated Java integration boundaries | scattered direct Java coupling |

## Constraints

### MUST DO

- Follow BoxLang syntax and scoping conventions consistently
- Keep framework/runtime integration concerns isolated from domain logic
- Document public APIs with DocBox-compatible comments when needed

### MUST NOT DO

- Do not rely on implicit scope lookup in complex flows
- Do not mix CFML compatibility constructs unless migration requires it
- Do not bypass parameter validation for external inputs

## Output Templates

```md
## BoxLang Implementation Note
- Runtime target: [cli/web/module]
- Design intent: [intent]
- Core constructs used: [list]
- Validation: [tests/runtime checks]
```

## Knowledge Reference

boxlang syntax, scope discipline, module lifecycle, bifs and components, async executors, boxfuture chains, java interop boundaries, runtime config, commandbox workflows, testbox coverage

## Related Skills

- `java-expert`
- `security-expert`
- `code-documenter`
- `code-reviewer`
