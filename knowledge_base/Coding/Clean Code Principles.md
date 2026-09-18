# Clean Code Principles

**Category:** [[Coding]] · [[Software Engineering]]
**Related:** [[Coding/Code Complexity]] · [[Coding/Git Basics]] · [[Meta-Learning/Feynman Technique]] · [[Refactoring]] · [[Programming]]

## Core ideas

- **Readability over cleverness:** Code is read more often than it is written. Prefer clear names and straightforward control flow.
- **DRY:** Extract genuinely repeated logic into reusable functions or modules, but do not force unrelated concepts into one abstraction.
- **Single responsibility:** Each function or class should have one clear responsibility and reason to change.

## Practical checklist

- [ ] Use descriptive names such as `user_account_balance` instead of `x`.
- [ ] Keep functions focused and usually under 20–30 lines when practical.
- [ ] Remove dead or commented-out code; use version control for history.
- [ ] Review [[Coding/Code Complexity]] before adding abstraction.
- [ ] Explain architectural intent using [[Meta-Learning/Feynman Technique]].
- [ ] Commit a focused change using [[Coding/Git Basics]].

## JARVIS application

When reviewing code, JARVIS should first explain the intent, then identify duplication, responsibility violations, naming problems, and complexity hotspots. It should propose the smallest safe refactor and recommend tests before changing files.
