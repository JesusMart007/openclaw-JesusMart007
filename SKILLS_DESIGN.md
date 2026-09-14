# Skills Design

## Purpose

Define how skills are designed, documented and maintained for the OpenClaw workspace.

## Skill Structure

Each skill should include:

- A clear name and focused responsibility.
- A concise description of when it should be used.
- Required inputs and expected outputs.
- The tools, files or external services it depends on.
- Safety boundaries and approval requirements.
- Examples for common workflows.
- A validation method or checklist.

## Design Principles

- Keep each skill focused on one meaningful capability.
- Prefer existing tools and integrations before creating custom logic.
- Make instructions explicit, actionable and easy to scan.
- Preserve user privacy and avoid exposing credentials or personal data.
- Ask for confirmation before external or irreversible actions.
- Document assumptions, limitations and failure modes.
- Keep skills maintainable as the workspace evolves.

## Recommended Workflow

1. Define the user problem and the skill's scope.
2. Identify available tools, files and integrations.
3. Specify inputs, outputs and safety constraints.
4. Write the smallest useful implementation.
5. Test the skill with representative cases.
6. Record known limitations and maintenance notes.

## Review Checklist

- [ ] The skill has a focused purpose.
- [ ] Activation conditions are clear.
- [ ] Inputs and outputs are defined.
- [ ] External actions require appropriate confirmation.
- [ ] Sensitive data is handled safely.
- [ ] Examples and validation steps are included.
- [ ] The documentation matches the current implementation.
