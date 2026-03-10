# AY Skills — Open Source Claude Code Skills

A collection of Claude Code skills built and used by [AY Automate](https://ayautomate.com).

Each skill lives in `skills/<skill-name>/` and is plug-and-play with Claude Code.

## What is a Claude Code Skill?

A skill is a `SKILL.md` file (and optional supporting files) that you drop into `.claude/skills/` in your project. Claude Code reads it automatically and gains new capabilities — like generating Excalidraw diagrams, creating LinkedIn carousels, or building n8n workflows.

## Skills

| Skill | What it does |
|---|---|
| [artifacts-builder](./skills/artifacts-builder/) | Build complex claude.ai HTML artifacts using React, Tailwind, and shadcn/ui; bundle to a single HTML for sharing. |
| [mcp-client](./skills/mcp-client/) | Universal MCP client to connect to any MCP server with progressive disclosure; includes Python runner and example configs. |
| [remotion](./skills/remotion/) | Best-practice rules and patterns for creating Remotion video compositions and animations in React. |
| [skill-creator](./skills/skill-creator/) | Author effective Claude Code skills with clear triggers, references, scripts, and packaging tools. |
| [notebooklm](./skills/notebooklm/) | Query Google NotebookLM notebooks for source-grounded, citation-backed answers via controlled browser sessions. |
| [ui-ux-pro-max](./skills/ui-ux-pro-max/) | AI-powered design system with rules, styles, and palettes; CLI to initialize premium UI foundations. |
| [agent-browser](./skills/agent-browser/) | Headless browser automation CLI for agents; ref-based element control, parallel sessions, persistent auth. |
| [claude-seo](./skills/claude-seo/) | Full-stack SEO audits inside Claude Code; technical SEO, AI search, and DataForSEO MCP integration. |
| [superpowers](./skills/superpowers/) | End-to-end agentic dev workflow (brainstorm → plan → subagents → review) with TDD enforcement. |
| [excalidraw-diagram](./skills/excalidraw-diagram/) | Generate Excalidraw diagrams (.excalidraw + PNG) with brand-styled visuals and evidence artifacts. |

## How to Use

1. Copy the skill folder into your project's `.claude/skills/` directory
2. Start a Claude Code session — the skill is auto-loaded
3. Describe what you want. Claude Code will follow the skill's instructions.

## Contributing

Open an issue or PR. Skills should be self-contained, well-documented, and tested.

More skills dropping soon.

---

Built by [Walid Boulanouar](https://linkedin.com/in/walid-boulanouar) · AY Automate
