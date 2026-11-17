# Contributing to Skript.sk

Thanks for helping improve Skript.sk!

Please keep contributions practical, readable, and testable.

## Before Contributing

- Search existing scripts and issues to avoid duplicates.
- Explain the problem your script solves.
- Avoid unnecessary addons.
- Never claim compatibility with versions you have not tested.

## Script Requirements

Every submitted script should include or document:

- Purpose and feature overview
- Minecraft version(s) tested
- Server software and version tested
- Skript version tested
- Required addons/plugins and their versions
- Installation and configuration instructions
- Commands and permissions
- Known limitations or incompatibilities

## GUI Standard

All inventory GUIs must be double-chested:

**6 rows / 54 slots.**

Keep slot layouts consistent and prevent players from accidentally moving or losing GUI items.

## Code Quality

- Use clear variable names and consistent formatting.
- Avoid unnecessary dependencies.
- Validate user input.
- Check permissions for privileged actions.
- Handle offline players, empty inventories, and invalid arguments.
- Avoid overwriting unrelated files or server data.
- Keep messages understandable and configurable where practical.

## Testing

Test on a real server before marking a script as complete.

Include the exact environment used in the documentation.

If you cannot test a particular version, label it untested rather than supported.

## Pull Requests

1. Describe the feature or fix.
2. List changed files.
3. State the exact test environment and test results.
4. Mention remaining limitations.

Small, focused pull requests are easier to review.
