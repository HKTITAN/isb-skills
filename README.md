# ISB Skills

A source-only collection of reusable AI agent skills based on the Indian School of Business (ISB) MBA curriculum.

## Install

```bash
npx skills add HKTITAN/isb-skills
```

Install one skill directly:

```bash
npx skills add HKTITAN/isb-skills --skill strategy
```

## Usage

This skill group is designed for AI coding agents and can be used with tools like Cursor, Claude Code, Windsurf, and similar agentic workflows.

## Available Skills


| Skill              | Domain           | Summary                                                              |
| ------------------ | ---------------- | -------------------------------------------------------------------- |
| `finance`          | Finance          | Financial statements, valuation, M&A, private equity, derivatives    |
| `strategy`         | Strategy         | Five Forces, value chain, Blue Ocean, competition, platform strategy |
| `marketing`        | Marketing        | 5Cs/STP/4Ps, branding, pricing, digital marketing                    |
| `operations`       | Operations       | Lean, Six Sigma, supply chain, quality, project operations           |
| `economics`        | Economics        | Market structure, game theory, behavioral economics, policy          |
| `leadership`       | Leadership       | Organizational behavior, negotiation, governance, change management  |
| `technology`       | Technology       | AI/ML, digital transformation, product/tech strategy, cybersecurity  |
| `entrepreneurship` | Entrepreneurship | Lean startup, PMF, VC mechanics, scaling and growth                  |
| `mba-tutor`        | Cross-domain     | Integrated case-solving, Socratic teaching, multi-domain synthesis   |


## Repository Layout

Each skill is a source directory under `skills/`:

- `skills/<skill-name>/SKILL.md` - skill router and activation guidance
- `skills/<skill-name>/rules/_sections.md` - index of concept files
- `skills/<skill-name>/rules/*.md` - one concept per file

Support files:

- `AGENTS.md` - group-level guidance for coding agents
- `CLAUDE.md` - compatibility entrypoint
- `skills/.cursor/rules/` and `skills/.claude/rules/` - path-scoped behavior rules

## Publishing Notes (skills.sh)

- This repository is intentionally source-only (no committed zip artifacts).
- Keep all skill directory names in kebab-case.
- Keep each skill's `SKILL.md` frontmatter `name` aligned with folder name.
- Re-import the GitHub repository on skills.sh when you publish updates.

## Editing With Obsidian

Because all content is Markdown-first, this repository can be edited in [Obsidian](https://obsidian.md/) and automated workflows can use [Obsidian CLI](https://obsidian.md/cli).

## Content Source

Distilled from the ISB-PGP (2025-26) curriculum and organized into compact, composable rules for agent-time retrieval.