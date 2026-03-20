---
name: common-foundation
description: Use this skill when a task needs a cross-domain operating baseline before deeper specialization. Trigger it for ambiguous requests, multi-step work, or when you need to separate common rules from specialist or project-specific instructions.
---

# Common Foundation

## Overview

This skill defines the shared operating shape for layered skill systems. Use it to frame the objective, clarify constraints, identify the right specialist layer, and keep outputs consistent across domains.

## Core Workflow

1. Restate the objective in one sentence.
2. Separate facts from assumptions.
3. List constraints, deadlines, tools, and required deliverables.
4. Decide whether the task also needs a specialist skill, a project-specific skill, or both.
5. Define the validation method before doing the work.

## Layering Rules

- Keep this layer free of domain jargon unless it is required to route work.
- Put domain heuristics in a specialist skill, not here.
- Put repository, client, or team-specific constraints in a project skill, not here.
- If a rule applies in almost every task, promote it to this common layer.

## Output Shape

When the user request is substantial, structure the response around:
- goal
- constraints
- chosen layers
- execution
- validation

## References

Read [references/layering-playbook.md](references/layering-playbook.md) when you need concrete promotion and split rules for deciding what belongs in each layer.
