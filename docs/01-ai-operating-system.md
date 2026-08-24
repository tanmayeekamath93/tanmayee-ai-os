# Personal AI Operating System

This document defines the working model for using this repository as a reusable personal "AI operating system."

## Operating principles

- Keep instructions modular and reusable.
- Store working patterns in version-controlled files rather than chat memory alone.
- Prefer structured prompt blocks over free-form text.
- Maintain a small library of proven skills and prompts.
- Evaluate outputs before adopting them as default behavior.

## Recommended layers

### 1. Core identity

A short personal operating model for how the AI behaves:

- communication style
- default assumptions
- priorities and guardrails
- strengths and limits

### 2. Skill packs

Task-specific instruction bundles for:

- product work
- project planning
- software engineering
- architecture reviews
- research synthesis
- writing and editing
- code generation and debugging

### 3. Tooling layer

MCP servers and tool definitions that the agent can call when appropriate.

### 4. Evaluation layer

Simple rubrics for checking:

- correctness
- completeness
- clarity
- relevance
- safety

### 5. Template layer

Reusable sequences for recurring tasks like:

- sprint planning
- PRD drafting
- code review
- issue triage
- research brief generation

## Working pattern

When a task starts:

1. choose the nearest reusable skill or template
2. add required project-specific context only
3. ask the agent to operate within the standard guardrails
4. review output with the rubric
5. store what worked for repeated reuse

## Goal

The repository should become a living toolkit that captures your real-world AI workflow and reduces repeated instruction overhead across clients and tools.
