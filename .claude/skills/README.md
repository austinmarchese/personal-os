# Skills

Reusable workflows that you run as commands.

## Why This Matters

Instead of explaining the same process every time, you write it once and run it with a slash command.

Skills:
- Codify your repeatable workflows
- Improve themselves over time
- Turn complex processes into single commands

## How Skills Work

Each skill is a folder with a `SKILL.md` file that describes:
- When to use it
- The step-by-step process
- What inputs it needs
- What outputs it produces

When you run `/skill-name`, Claude reads the SKILL.md and follows the process.

## Creating a Skill

```bash
mkdir skills/[skill-name]
cp skills/_template/SKILL.md skills/[skill-name]/SKILL.md
```

Then customize the process for your workflow.

## Included Skills

- **daily-journal** — End-of-day capture of what you learned

## Skill Ideas

Good candidates for skills:
- Weekly review
- Meeting notes processor
- Email drafting workflow
- Content outline generator
- Research synthesis
- Proposal generator

## Recursive Improvement

After running a skill, ask: "What would make this better next time?"

Add learnings directly to the SKILL.md file. The skill gets smarter with every use.
