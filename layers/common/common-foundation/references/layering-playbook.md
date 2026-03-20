# Layering Playbook

Use this reference when you are deciding where a rule or workflow belongs.

## Put It In Common When

- The rule applies across multiple domains.
- The wording should stay stable even if the project changes.
- The goal is to improve task framing, validation, or communication quality.

## Put It In A Specialist Skill When

- The work needs domain-specific heuristics.
- The evaluation criteria are specific to a craft such as software, music, design, or research.
- Good output depends on specialist vocabulary, common failure modes, or domain workflows.

## Put It In A Project Skill When

- The rule depends on a repository, product, client, team, or environment.
- The task needs exact file paths, commands, conventions, release rules, or business constraints.
- The instruction would become stale if copied to another project.

## Promotion And Demotion

- Promote a project rule upward only after it repeats across projects.
- Demote a common rule downward if it starts carrying too much specialist detail.
- Keep each layer readable on its own. If a skill cannot explain its purpose in a few paragraphs, split it.
