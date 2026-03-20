---
name: skills-codex-project
description: Use this skill for work inside the skills-codex repository. Trigger it when the task affects repository structure, operational notes, research findings, or any agent-human collaboration flow that should follow this repo's language and documentation rules.
---

# Skills Codex Project

## Overview

This skill captures repository-specific operating rules for `skills-codex`. It defines the default conversation language and where ongoing operational and design knowledge should be stored.

## Project Rules

1. Agent and human communication should be in Japanese by default.
2. Store conversation history and operating notes under `meta/`.
3. Store reasoning background, research results, and design knowledge under `knowledge/`.

## Directory Intent

- `meta/`: agent-human conversation records, work logs, and operational memos.
- `knowledge/`: research notes, architectural rationale, decision background, and reusable findings.

## Usage

- When adding a new persistent note, decide whether it is operational (`meta/`) or knowledge-oriented (`knowledge/`) before writing.
- If a document mixes both, separate it into two files rather than merging concerns.
- Keep reusable repository rules here; do not push them down into the common or specialist layers.
