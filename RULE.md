---
description: "Forbid dead, unused, or unreachable code"
alwaysApply: true
---

# NoDeadCode Rule

A codebase under NoDeadCode must contain no dead, unused, or unreachable code.

## Requirements

- Code that is not part of a live, reachable behavior surface is a defect: delete it or make it live and fully exercised through public behavior.
- Commented‑out code for history or “just in case” is forbidden. Version control is the archive.
- Unused parameters, flags, feature toggles, legacy shims, and permanently‑off branches are forbidden unless they are actively used and publicly exercised.
- If code is not reachable from the public surface (or an explicitly allowed boundary), it must not exist.
