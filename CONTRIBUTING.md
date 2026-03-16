# Contributing to R Analytics Skill

Thank you for your interest in contributing! This guide will help you get started.

## How to Contribute

### Adding a New Package Skill

1. **Identify the domain** -- determine which `sub-skills/` directory your package belongs in (e.g., `r-data`, `r-viz`, `r-ml`).
2. **Create the skill file** -- add a `SKILL.md` in the appropriate sub-directory following the existing structure.
3. **Follow the template** -- each `SKILL.md` should include:
   - YAML frontmatter (`name`, `description`, `triggers`)
   - Quick reference with common usage patterns
   - Code examples that are copy-paste ready
   - Links to official documentation

### Improving Existing Skills

- Fix inaccuracies or outdated information
- Add missing function signatures or parameters
- Improve code examples
- Add cross-references to related packages

### Adding References

- Place new reference guides in the `references/` directory
- Use Markdown format
- Include practical, runnable examples

## Development Workflow

1. **Fork** the repository
2. **Create a branch** for your changes:
   ```bash
   git checkout -b add-package-xyz
   ```
3. **Make your changes** and test them locally
4. **Commit** with a clear message:
   ```bash
   git commit -m "Add xyz package skill to r-data"
   ```
5. **Push** and open a Pull Request

## Style Guidelines

- Keep skill files concise and practical
- Use fenced code blocks with language hints (`r`, `bash`)
- Prefer tidyverse-style R code where applicable
- Include both basic and advanced usage examples
- Use consistent YAML frontmatter format

## Reporting Issues

- Use the [Bug Report](.github/ISSUE_TEMPLATE/bug_report.yml) template for errors or inaccuracies
- Use the [Feature Request](.github/ISSUE_TEMPLATE/feature_request.yml) template for new package or domain requests

## Code of Conduct

Be respectful, constructive, and welcoming. We are building a community resource for R users.

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE).
