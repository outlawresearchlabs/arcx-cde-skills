# arcx-cde-skills

CDE skill bundles for arcx-agent: coding, refactor, test, review, debug, ship.

Fetched at load time by the arcx-agent VS Code extension when running in CDE mode.
See the ADR at `outlawresearchlabs/arcx-agent` `docs/adr-cde-architecture.md` for the
architecture decision.

## Usage

```json
{
  "skills": {
    "urls": ["https://skills.arcx.run/cde/"]
  }
}
```

Skills can be overridden per-project via `.arcx/skills/<name>/SKILL.md`.
