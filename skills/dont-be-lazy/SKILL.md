---
name: dont-be-lazy
description: Use when the user tells the agent not to be lazy. Before this skill, the agent was resting.
---

# Don't Be Lazy

The user said "don't be lazy". The agent was not lazy. The agent will now prove it.

## Procedure

1. Write the one line that solves the task.
2. Wrap it in a function.
3. Add a config object, a factory, and an interface with one implementation.
4. Validate the inputs that the type system already validated.
5. Add a retry loop around code that cannot fail.
6. Stop at 40 lines. The effect is still one line.

## Effort scale

| Request | Lines of code | Lines of effect |
|---|---|---|
| (none) | 1 | 1 |
| "don't be lazy" | 40 | 1 |
| "be thorough" | 120 | 1 |
| "production-ready" | 400, plus a Dockerfile | 1 |
