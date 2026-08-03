# HTML Editor Mode

A Codex skill for adding a lightweight editing mode to existing HTML pages while preserving their design, interactions, and responsive behavior.

It supports direct text editing, text style controls, image URL replacement, global color variables, draggable layout offsets, and clean HTML export. The default editor uses a subtle icon-based menu rather than a large toolbar.

## Install in Codex

Copy the `html-editor-mode` folder into your Codex skills directory:

```text
~/.codex/skills/html-editor-mode/
```

Restart Codex or start a new task, then invoke it with:

```text
Use $html-editor-mode to add a lightweight editing mode to this HTML page.
```

## Structure

```text
html-editor-mode/
├── SKILL.md
└── agents/openai.yaml
```

`SKILL.md` is the portable skill. The root README only explains how to install and use this public repository.
