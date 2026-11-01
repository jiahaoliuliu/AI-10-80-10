# Skills

Reusable workflows for AI-assisted development using the 10/80/10 approach.

## Structure

```text
skills/
  <skill-name>/
    SKILL.md
    scripts/       # Optional executable helpers
    references/    # Optional supporting documentation
    assets/        # Optional templates or other resources
```

Use a descriptive lowercase directory name with hyphens. Each `SKILL.md` should explain when to use the skill, what information it needs, the steps to follow, and how to verify completion. Document required tools and any actions that need explicit authorization.

Keep skills self-contained where practical. Use relative links for supporting files, avoid machine-specific paths, and document dependencies. Check compatibility with the intended AI agent before publishing; installation and discovery conventions vary between tools.

When adding a skill, link it from the root README and identify whether it supports requirements, implementation, verification and delivery, or several stages.
