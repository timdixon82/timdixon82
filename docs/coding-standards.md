# Project Coding Standards: timdixon82

This project follows the team's stack-independent standards in the global wiki's `coding-standards.md`.

## Stack

This is a Markdown-only repository. It contains no JavaScript, CSS, PHP, or WordPress code. The only runtime artefact is README.md, which GitHub renders as the visitor-facing profile page.

## Project-specific notes

### Markdown style

- Every Markdown file has exactly one H1, then H2 and H3 in order, with no skipped levels.
- Plain language at roughly Flesch-Kincaid grade 9 or below.
- Descriptive link text on every link. Never "click here" and never a bare URL.
- No inline HTML unless strictly necessary (and documented here if added).
- Lines are not hard-wrapped at 80 characters; the markdownlint MD013 rule is disabled in `.markdownlint.json`.

### Commit conventions

Commits follow Conventional Commits style so release-please can manage VERSION automatically. Common types for this repository: `docs` for README or wiki changes, `chore` for config and workflow updates.

### No pa11y.json

Pa11y is not used in this repository. No `pa11y.json` file is present or needed. See `accessibility.md` for the reasoning.
