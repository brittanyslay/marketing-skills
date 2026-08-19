# AI Marketing Skills

Seven small, sharp AI skills for the jobs a B2B marketing leader actually hands to a model every week: sharpen positioning, define an ICP, tear down a competitor, plan demand, write outreach worth replying to, turn one idea into a week of content, and strip the robot out of your copy.

They are written as [Claude Code](https://claude.ai/code) skills, but each one is just plain instructions, so they work as a Custom GPT, a system prompt, or a prompt you paste into any model.

Built by [Brittany Slay](https://brittanyslay.com). Free to use, copy, and share (MIT).

## The skills

| Skill | What it does |
|---|---|
| `anti-robot-editor` | Strips AI tells out of copy so it sounds like a specific human. The most-used one. |
| `positioning-in-five-seconds` | A one-line positioning statement a busy buyer gets in five seconds, plus two angles and their trade-offs. |
| `icp-from-best-customers` | Turns your best accounts into a sharp ICP and a "not a fit" list, using only real patterns. |
| `competitive-teardown` | Reads a competitor's messaging and hands you three wedges they cannot easily copy. |
| `first-demand-plan` | A lean, opinionated first-90-days demand plan for a real budget and a small team. |
| `cold-outreach` | A cold email a busy buyer would actually reply to, in two versions. |
| `content-engine` | Stretches one real insight into a week of content without watering it down. |

## Use them in Claude Code

Clone the repo, then copy the skills you want into your skills directory:

```bash
git clone https://github.com/brittanyslay/marketing-skills.git
cd marketing-skills

# user-level (available in every project)
mkdir -p ~/.claude/skills
cp -r skills/* ~/.claude/skills/

# or project-level (just this project)
mkdir -p .claude/skills
cp -r skills/* .claude/skills/
```

Then invoke a skill by name, or just describe the task and let Claude pick it up. Each skill lives in `skills/<name>/SKILL.md` with YAML frontmatter, the standard Claude Code format.

## Use them anywhere else

Open any `SKILL.md`, copy the body, and paste it into ChatGPT, Claude, Gemini, or a Custom GPT's instructions. They are model-agnostic. Swap the `[BRACKETED]` parts for your own details.

## The one rule that runs through all of them

Do not fake specificity. If a claim needs a real number, these skills flag it in `[brackets]` for you to fill in rather than inventing one. And no em dashes, anywhere.

---

More free tools and the writing behind them: [brittanyslay.com](https://brittanyslay.com)
