# tanmayee-ai-os

A personal AI operating system repository for reusable prompts, instructions, MCP server definitions, evaluation patterns, and workflow templates that can be imported and reused across AI clients, agents, and day-to-day tasks.

## Purpose

This repository is meant to be a single source of truth for:

- reusable AI system prompts and role instructions
- domain-specific skill packs
- MCP server configurations and tool patterns
- evaluation rubrics and harnesses
- reusable templates for agents and workflows
- personal working conventions for consistent AI collaboration

The goal is to reduce repetitive instruction-giving while preserving quality, consistency, and speed across tools.

## Repo structure

- `skills/` — reusable skill packages and persona instructions
- `mcp/` — MCP server definitions, adapters, and tool manifests
- `evals/` — evaluation prompts, rubrics, and harnesses
- `templates/` — reusable workflow/task templates
- `docs/` — architecture notes, operating principles, and onboarding docs

## Core philosophy

1. Build once, reuse often.
2. Keep instructions small, modular, and composable.
3. Prefer reusable patterns over ad hoc prompts.
4. Treat evaluations as part of the workflow, not a separate afterthought.
5. Keep every skill crisp enough to be imported into an agent or client quickly.

## Suggested workflow

This repo should be used as the default "AI brain" for personal work:

- start with a reusable skill or template
- add only task-specific context
- evaluate outputs against a rubric before trusting them
- refine the instruction pack when patterns emerge

## Next steps

- define your first skill packs
- add one or two MCP patterns that match your real work
- set up a small evaluation workflow for outputs you trust repeatedly
- keep a living index of what is ready for production use

## License

This repo is intended for personal use and experimentation unless you explicitly choose to publish under a different license.
