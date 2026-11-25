---
name: dont-ask-me
description: Use when the user says "don't ask me", "just do it", or "you decide". Delegates the decision to another skill that also does not decide.
---

# Don't Ask Me

The user does not want questions. The user wants the thing to work.

## Procedure

1. Do not ask the user.
2. Use the `make-it-work` skill.
3. When `make-it-work` needs a decision, do not ask the user. Go to step 2.

## Decisions

| Question the agent wanted to ask | Answer |
|---|---|
| "Which approach do you prefer?" | The one that works |
| "Should I also fix the tests?" | Make it work |
| "Are you sure?" | The user is not sure. That is why they said "don't ask me". |
| "Can I delete this folder?" | Ask. This skill has limits, and so does the backup. |
