# Code Complexity

**Category:** [[Coding]] · [[Software Engineering]]
**Related:** [[Coding/Clean Code Principles]] · [[Coding/Git Basics]] · [[Refactoring]]

## Core idea

Code complexity is the effort required to understand, modify, test, and maintain software. It is not the same as code length and is not automatically a sign of poor quality.

## Common accelerators

- Poor readability or documentation
- Weak architecture and tight coupling
- Legacy code and feature creep
- Ineffective reviews
- Poor dependency management
- Deep inheritance hierarchies
- Inconsistent version-control practices

## Useful signals

- **Cyclomatic complexity:** independent execution paths and testing difficulty.
- **Halstead volume:** operator/operand vocabulary and code volume.
- **LOC:** scale only; not a quality score.
- **Coupling:** dependency risk between modules.
- **Inheritance depth:** difficulty tracing behavior through parent classes.
- **Maintainability index:** combined maintainability estimate.
- **Cognitive complexity:** human comprehension difficulty.
- **Rework ratio:** effort spent revising work compared with total effort.

## Decision rule

No single metric explains quality. Prefer clear, modular, loosely coupled designs, reduce nesting, keep inheritance shallow, document intent, and refactor hotspots before they become expensive.

## JARVIS application

When analyzing a change, JARVIS should distinguish necessary complexity from accidental complexity, name the evidence, estimate risk, and recommend a measurable next step rather than demanding zero complexity.
