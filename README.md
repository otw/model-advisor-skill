# Model Advisor Skill

A reusable Codex skill for choosing an available model and thinking setting that can meet a task's quality bar at the lowest expected total cost. It reassesses at meaningful phase changes and checks current official provider guidance before recommending a switch.

The skill instructions are in [SKILL.md](SKILL.md). Install this repository as a personal skill folder named `model-advisor` under your Codex skills directory, then invoke `model-advisor` when model choice materially affects quality or cost. The skill does not change model settings on your behalf.

## Releases

Milestones use Git tags and GitHub Releases named `vMAJOR.MINOR.PATCH`. Release notes describe changes to recommendation behavior and source-check requirements. During the `0.x` series, minor releases may change guidance; patch releases clarify or correct it. See [CHANGELOG.md](CHANGELOG.md).
