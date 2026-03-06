# AY Skills — Open Source Claude Code Skills

A collection of Claude Code skills built and used by [AY Automate](https://ayautomate.com).

Each skill lives in `skills/<skill-name>/` and is plug-and-play with Claude Code.

## What is a Claude Code Skill?

A skill is a `SKILL.md` file (and optional supporting files) that you drop into `.claude/skills/` in your project. Claude Code reads it automatically and gains new capabilities — like generating Excalidraw diagrams, creating LinkedIn carousels, or building n8n workflows.

## Skills

| Skill | What it does |
|---|---|
| [excalidraw-diagram](./skills/excalidraw-diagram/) | Generate hand-drawn style Excalidraw diagrams (`.excalidraw` + PNG) from natural language descriptions. Includes a Python renderer using Playwright. |

More coming. Follow [@walid-boulanouar](https://linkedin.com/in/walid-boulanouar) for updates.

## How to Use

1. Copy the skill folder into your project's `.claude/skills/` directory
2. Start a Claude Code session — the skill is auto-loaded
3. Describe what you want. Claude Code will follow the skill's instructions.

## Contributing

Open an issue or PR. Skills should be self-contained, well-documented, and tested.

---

Built by [Walid Boulanouar](https://linkedin.com/in/walid-boulanouar) · AY Automate
