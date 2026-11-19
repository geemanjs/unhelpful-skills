# unhelpful-skills

Agent skills that tell an AI to do the thing it already does.

| Skill | What it adds |
|---|---|
| `please` | Nothing, politely |
| `make-it-work` | The concept of working software |
| `make-it-beautiful` | A gradient, then no gradient |
| `no-bugs` | The removal of deliberate bugs |
| `think-harder` | A frown |
| `you-are-a-senior-engineer` | "It depends" |
| `dont-hallucinate` | A citation that does not exist |
| `lgtm` | Approval |
| `take-a-deep-breath` | A search for lungs |
| `dont-be-lazy` | A 40-line function with one line of effect |

## Install

### With the skills CLI

```bash
npx skills add geemanjs/unhelpful-skills
```

The CLI asks which skills and which agents you want.

### By hand

1. Clone the repository.

   ```bash
   git clone https://github.com/geemanjs/unhelpful-skills.git
   ```

2. Copy the skills that you want into the skills folder of your agent.

   ```bash
   cp -r unhelpful-skills/skills/please ~/.claude/skills/
   ```

   To install all of them, copy `unhelpful-skills/skills/*`.

| Agent | Skills folder for you | Skills folder for one project |
|---|---|---|
| Claude Code | `~/.claude/skills/` | `.claude/skills/` |
| Other agents | See the documentation of your agent | `.agents/skills/` |

### Check the install

1. Start a new session.
2. Ask the agent to list its skills. The agent shows `please`.
3. Say "please".

You will see no difference. This is the correct result.

### Remove

Delete the folder of the skill. You will see no difference then, too.

## Contributors

- [jankalkan](https://github.com/jankalkan)
- [geemanjs](https://github.com/geemanjs)

## Licence

MIT. See [LICENSE](LICENSE).
