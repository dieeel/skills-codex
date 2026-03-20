---
name: project-context-template
description: Use this skill as a template for project-specific skills that capture repository, product, client, or team constraints. Trigger it when common and specialist layers are not enough because exact paths, commands, conventions, or business rules matter.
---

# Project Context Template

## Overview

This skill is the project layer starter. Use it to encode the facts that should never be guessed inside a specific repository or engagement, while keeping reusable logic in the common or specialist layers.

## Workflow

1. Duplicate this skill into a project-specific directory with the real project name.
2. Replace placeholders with actual repository facts and team rules.
3. Add only project-bound knowledge that would be unsafe or noisy elsewhere.
4. Keep volatile detail in `references/` so the main `SKILL.md` stays short.
5. Update the skill when commands, ownership, release rules, or architecture change.

## What To Capture

- repository layout
- build, test, lint, and deploy commands
- coding and review conventions
- sensitive areas and high-risk flows
- domain language and business invariants

## Template Reference

Start from [references/project-profile-template.md](references/project-profile-template.md) and prune sections that the project does not need.
