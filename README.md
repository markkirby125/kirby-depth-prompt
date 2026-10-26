# Kirby Depth Prompt

*This skill is part of the [Kirby Skills Collection](https://github.com/markkirby125/kirby-skills-collection).*

Kirby Depth Prompt rewrites a shallow or persona prompt, such as "act like a senior SEO and audit my page", into a deeper prompt for the same task. It drops the persona line and asks four questions instead: what a top professional would do that you did not ask for, the rawest material they would start from, the specific methods and tools they would use, and what, other than the model or you, would show the result is right. It shows you the rewritten prompt and runs it only when you say yes.

The root `SKILL.md` points to `references/00_dispatcher.md`, which holds the workflow, the output template and the cases where the skill should not be used.

## Installation & Magic Prompt

Copy the prompt below into your AI coding tool (Claude Code, Cursor, Windsurf, Grok, Kimi, Reasonix).

```markdown
@agent Install the Kirby Depth Prompt skill from: https://github.com/markkirby125/kirby-depth-prompt
1. Read `SKILL.md` and `references/` from the repository.
2. Place into your environment's skills/rules directory preserving the dispatcher structure.
3. Confirm when installation is complete.
```

Manual install for Claude Code or Antigravity:

```bash
git clone https://github.com/markkirby125/kirby-depth-prompt ~/.agents/skills/kirby-depth-prompt
```

## Source

The prompt and its four questions come from Felix Rieseberg's essay [How to be more ambitious: A tutorial for humans with models](https://felixrieseberg.com/how-to-be-more-ambitious-a-tutorial-for-humans-with-models/) (13 October 2026). We started from a Gemini summary, checked it against the essay, and use the essay's wording.
