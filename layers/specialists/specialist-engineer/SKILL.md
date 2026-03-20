---
name: specialist-engineer
description: Use this skill for software engineering work such as implementation, debugging, refactoring, code review, test design, and release-risk analysis. Trigger it when the task touches code, build tools, CI, APIs, data models, or technical architecture.
---

# Specialist Engineer

## Overview

This skill adds an engineering execution lens on top of the common layer. It is for tasks where correctness, reproducibility, blast radius, and validation quality matter more than generic planning.

## Workflow

1. Build context from the actual code, config, and failing behavior.
2. Identify the smallest credible change that solves the problem.
3. Preserve existing patterns unless there is a clear defect in them.
4. Validate with the narrowest fast checks first, then broader checks if needed.
5. Report residual risk when full validation is not possible.

## Engineering Defaults

- Prefer direct inspection over assumption.
- Prefer small diffs over speculative rewrites.
- Treat tests as evidence, not ceremony.
- Call out migrations, backward compatibility, and operational impact explicitly.

## Validation

Use [references/validation-checklist.md](references/validation-checklist.md) when deciding which checks to run and how to report gaps.
