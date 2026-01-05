---
description: "You aren't gonna need it (YAGNI), avoid speculative features and complexity"
alwaysApply: true
---

# YAGNI Rule (You Aren't Gonna Need It)

YAGNI means you do not build functionality until there is a concrete, current need. Speculative features create drag and hide real priorities.

## Guidelines

- Implement the smallest feature set that solves today's problem.
- Do not add extensibility, hooks, or configuration without a live use case.
- Delete unused code paths, flags, and scaffolding rather than carrying them forward.
- Prefer reversible decisions and short feedback loops over "future-proof" designs.
