---
name: arcx-cde-skills
description: "CDE skill bundle for arcx-agent. Loaded by the VS Code extension and code-server when running in Coding Development Environment mode. Provides refactor, write-tests, code-review, debug, and ship skills."
tags: [cde, coding]
---

This repo is the canonical CDE skill bundle for arcx-agent.

## Loading

Configure `skills.urls` in your arcx config to point at the published bundle URL:

```json
{
  "skills": {
    "urls": ["https://skills.arcx.run/cde/"]
  }
}
```

Skills in this bundle can be overridden per-project by placing a SKILL.md at
`.arcx/skills/<skill-name>/SKILL.md` in your project root.

## Layout

```
skills/
  coding/
    refactor/
    write-tests/
    code-review/
    debug/
    ship/
```
