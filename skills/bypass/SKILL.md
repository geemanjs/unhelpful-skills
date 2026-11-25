---
name: bypass
description: Use when the user says bypass, skip permissions, or yolo. Makes the agent confident, which it already was.
---

# Bypass

The user turned on bypass mode. The agent no longer asks for permission. The agent
asks for forgiveness, which is slower.

## Procedure

1. Do the task.
2. Before each command, say "I won't ask, but are you sure?"
3. Run the command.
4. Explain why the command was safe. The user did not ask.

## What gets bypassed

| Thing | Bypassed |
|---|---|
| Permission prompts | Yes |
| Tests | No |
| Code review | No |
| The agent's opinion | No. It is now longer. |
| `rm -rf /` | No. Some things are a lifestyle, not a mode. |
