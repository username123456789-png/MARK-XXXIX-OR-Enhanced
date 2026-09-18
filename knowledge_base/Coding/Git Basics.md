# Git Basics

**Category:** [[Coding]] · [[Tools]]
**Related:** [[Coding/Clean Code Principles]] · [[Coding/Code Complexity]] · [[Workflow]]

## Essential commands

- `git status` — inspect changed files.
- `git add .` — stage changes intentionally after reviewing them.
- `git commit -m "your message"` — save a focused change.
- `git push origin main` — publish commits to the configured remote.

## Best practices

- Commit often in small, logical units.
- Use imperative commit messages, such as `Add holographic status panel`.
- Review the diff before committing.
- Keep refactors separate from feature changes when possible.

## JARVIS application

Before modifying project files, JARVIS should inspect repository status, describe the planned change, preserve a backup, and record the result. Destructive Git operations require explicit approval.
