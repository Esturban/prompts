# Prompt Draft Engine

A lightweight system for drafting high-quality prompts with consistent structure.

## Quickstart

1. Start from the template:
   - `prompts/templates/first-draft-template.md`
2. Follow the always-on rules in `.cursor/rules`:
   - Overview, Workflow, Template, Checklist, Formatting
3. Pick an archetype rule if relevant:
   - Software, Data, Creative
4. Replace ☐ placeholders and delete non-applicable lines
5. Validate with the checklist and include a concrete test example

## Folder Structure

- `.cursor/rules/` Cursor rules guiding drafting
- `prompts/templates/` base templates
- `prompts/archetypes/` optional archetype-specific templates (future)

## Tips

- Keep outputs testable and constrained
- Prefer explicit schemas and acceptance criteria
- Ask max 3 targeted questions if critical info is missing, then proceed with assumptions

