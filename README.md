# AI 10/80/10

A practical approach to AI-assisted software development, with reusable skills to support each stage.

Inspired by the delegation principle in Dan Martell’s [Buy Back Your Time](https://www.goodreads.com/en/book/show/60880804-buy-back-your-time), this repository adapts the idea to working with AI on software.

## The rule

| Stage | Focus | Developer’s responsibility |
| --- | --- | --- |
| First 10% | Define the requirements with AI | Explain the problem, explore the codebase, clarify constraints, and agree on acceptance criteria and a plan. |
| Middle 80% | Let AI implement | Give AI the context and tools to write code, run checks, and resolve routine issues. Stay available for decisions that change scope or behavior. |
| Final 10% | Verify and deliver | Review the diff, validate the user flow and test evidence, and prepare the change for delivery. |

The percentages are a guideline, not a fixed time budget. Discovery and verification should take as long as the task requires. The developer remains responsible for the outcome.

**Define together. Let AI execute. Verify and deliver.**

## AI skills

The [`skills/`](skills/) directory will contain reusable instructions for AI coding agents. Each skill lives in its own directory with a `SKILL.md` entry point and any supporting resources it needs.

See the [skills guide](skills/README.md) for the expected structure. No skills have been published here yet.

## Contributing

Add focused skills that help define, implement, or verify a concrete task. State prerequisites, expected inputs, workflow, and completion criteria. Keep credentials, private company instructions, and personal data out of contributions, and ensure you have permission to share any material you include.

## License

[Apache License 2.0](LICENSE).
