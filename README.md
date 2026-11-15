# Shared Codex Skills

Project-level Agent Skills are stored in `.agents/skills/`.

## Included
- `agent-reach` — upstream from [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach); includes three referenced guidance files. The Agent Reach CLI and platform dependencies are **not** installed by storing these instructions.
- `brainstorming` — upstream from [obra/superpowers](https://github.com/obra/superpowers).
- `markdown` — locally authored portable Markdown authoring and review skill.
- `ppt-standard` — locally authored default PowerPoint workflow.
- `ppt-master` — locally authored advanced alternative; optional.
- `humanizer` — upstream from [blader/humanizer](https://github.com/blader/humanizer).
- `skill-creator` — upstream from [openai/skills](https://github.com/openai/skills).

## Use in Codex
Open this repository as the active Codex project. Codex can discover project-level skills under `.agents/skills/`. In another repository, these project-level skills are not automatically global; copy the needed skill folders into that project's `.agents/skills/` or install them in a supported user-level skills directory.

## ChatGPT Work
This repository is a shared source of truth. A GitHub connection alone does not prove ChatGPT Work has imported or activated these skills. Import or activate them in Work separately if its Skills interface offers that capability.

## Provenance and licensing
Upstream files retain their original notices and metadata where supplied. Check each upstream project's license before redistribution or modification. The Markdown and PPT workflows are locally authored.
