# HTML Editing Mode

[![中文](https://img.shields.io/badge/语言-中文-1f6feb?style=flat-square)](README.md)

Add a lightweight, polished visual editing mode to an existing HTML page while preserving its design, responsive layout, animations, and interactions.

## Features

- Edit headings, body copy, labels, and card text directly
- Change the selected text's size and color
- Replace image URLs and update global color variables
- Drag independent text blocks or components to refine placement
- Export an HTML file containing the current edits
- Use a subtle icon-based editor menu that does not cover the page

## Use

Copy the `html-editing-mode` folder to the skills or instructions directory used by your AI coding agent.

Agents that support the `SKILL.md` convention can read the workflow directly; follow your agent platform's documentation for the exact installation path. For Codex, use:

```text
~/.codex/skills/html-editing-mode/
```

Then ask:

```text
Use $html-editing-mode to add a lightweight editing mode to this HTML page.
```

## Structure

```text
html-editing-mode/
├── SKILL.md
└── agents/openai.yaml
```

`SKILL.md` contains the core workflow. `agents/openai.yaml` is optional OpenAI / Codex UI metadata and can be safely ignored by other agents.
