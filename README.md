# Tableau Embedded Catalyst

A [Claude Code](https://claude.com/claude-code) skill that helps Tableau sellers build executive-ready embedded-analytics Points of View (POVs) using the Challenger Sale framework.

Use it when building prospect pitches, POV decks, email hooks, talk tracks, one-pager PDFs, or branded portal mockups for embedding Tableau into a customer's product.

## What it does

- Runs a structured discovery intake (customer, industry, buyer, use case, licensing)
- Proactively researches prospect leadership, news, and tech stack via web search
- Frames every output through the Challenger Sale sequence (Teach, Tailor, Take Control)
- Generates polished one-pager PDFs (reportlab) and fully brand-immersive HTML portal mockups with real SVG charts, interactive Tableau Pulse cards, and a Tableau MCP chat widget
- Grounds claims in bundled reference material (competitive intel, GTM/deal structure, HLS & FINS use cases)

## Install

Claude Code loads a skill from a **directory** containing a `SKILL.md` file — the directory name is the skill name. Clone this repo directly into your skills folder:

```bash
mkdir -p ~/.claude/skills && \
git clone https://github.com/allisonbierschenk/tableau-embedded-catalyst.git \
  ~/.claude/skills/tableau-embedded-catalyst
```

No restart needed — the skill appears as `/tableau-embedded-catalyst` immediately.

> **Note:** A common install mistake is dropping the file in as a flat `tableau-embedded-catalyst.md`. Claude Code only registers skills that live in their own directory as `SKILL.md`, so the flat-file version never shows up in the menu.

## Updating

This command works whether you originally installed via `git clone` or any other method:

```bash
rm -rf ~/.claude/skills/tableau-embedded-catalyst && \
git clone https://github.com/allisonbierschenk/tableau-embedded-catalyst.git \
  ~/.claude/skills/tableau-embedded-catalyst
```

No restart needed after updating.

## Usage

In Claude Code:

```
/tableau-embedded-catalyst
```

The skill will ask for any discovery documents you have (or you can type `skip`), then walk you through building the POV.
