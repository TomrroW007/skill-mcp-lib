# UI/UX Pro Max Skill — Contributor Guidelines

## If You Are an AI Agent

Stop. Read this section before doing anything.

This directory contains the `ui-ux-pro-max` skill, a specialized reasoning engine and intelligence dataset for UI/UX design.

When working in this directory:

1. **Maintain Structural Purity:** Do not reintroduce CLI tools (`package.json`), build scripts, or IDE-specific scaffold (`.claude`, `.cursor`). This repository has been explicitly flattened into a pure Markdown/Script skill format for the monorepo.
2. **Data & Scripts:** The `data/` directory contains the core reasoning rules (e.g., color palettes, typography matches, UI styles). The `scripts/` directory contains the Python-based search and reasoning engine. Modifications to the skill's logic should happen inside these directories.
3. **SKILL.md:** `skills/ui-ux-pro-max/SKILL.md` is the primary entrypoint. If you modify the python scripts or data formats, ensure the prompt instructions in `SKILL.md` accurately reflect the new usage.
