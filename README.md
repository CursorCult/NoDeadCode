# Part of the [CursorCult](https://github.com/CursorCult)

# YAGNI

YAGNI: **You Aren't Gonna Need It**.

**Install**

```sh
pipx install cursorcult
cursorcult link YAGNI
```

Rule file format reference: https://cursor.com/docs/context/rules#rulemd-file-format

**When to use**

- You are tempted to build a feature for a hypothetical future.
- You are adding flags or configs "just in case".
- The roadmap is driving implementation more than user needs.

**What it enforces**

- Build only what is required for the current use case.
- Avoid speculative abstractions and premature extensibility.
- Remove unused code paths and options quickly.

**Credits**

- Developed by Will Wieselquist. Anyone can use it.

**Origins**

- YAGNI is a core principle of Extreme Programming, popularized by Ron Jeffries.
