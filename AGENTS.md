# AGENTS.md

Guidance for AI coding agents working on this skill group.

## Repository Purpose

`skills/` contains source-only MBA domain skills intended for import and distribution through skills.sh.

## Skill Layout

Each skill follows this structure:

```text
skills/
  <skill-name>/
    SKILL.md
    rules/
      _sections.md
      *.md
```

Current skills:

- `finance`
- `strategy`
- `marketing`
- `operations`
- `economics`
- `leadership`
- `technology`
- `entrepreneurship`
- `mba-tutor`

## Editing Rules

- Keep skill folder names in kebab-case.
- Keep `SKILL.md` frontmatter `name` equal to the folder slug.
- Keep one concept per `rules/*.md` file.
- Keep `rules/_sections.md` in sync when adding or removing rules.
- Prefer concise `SKILL.md` routers that point to rule files instead of embedding all content.

## Agent Workflow

1. Identify relevant domain skill(s).
2. Read the skill router in `SKILL.md`.
3. Read `rules/_sections.md` for concept indexing.
4. Load specific rule files needed for the prompt.
5. For cross-domain problems, include `mba-tutor`.

