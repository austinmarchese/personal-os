# CLAUDE.md - Personal OS

This file provides guidance to Claude Code when working in this repository.

## What This Is

Personal OS is a system for building a lived knowledge base that enhances everything you do with AI. It contains:

- **Lived Experiences** — Daily journal entries of what the user learned
- **Best Work** — Examples that teach AI the user's standards
- **Consultants** — Expert frameworks the user has documented
- **Skills** — Reusable workflows that improve themselves

## How to Use This Context

When helping the user:

1. **Check lived experiences** for relevant past learnings
2. **Reference best work** when matching voice/style
3. **Apply consultant frameworks** when giving strategic feedback

## Key Folders

| Folder | Purpose |
|--------|---------|
| `context/lived-experiences/` | Daily journal entries—the user's accumulated wisdom |
| `context/best-work/` | Examples of the user's best outputs |
| `context/consultants/` | Expert frameworks to apply |
| `skills/` | Reusable workflows |

## Skills

Skills are in `skills/[name]/SKILL.md`. When the user runs `/[skill-name]`, read the SKILL.md and follow the process.

**Available skills:**

| Command | What it does |
|---------|--------------|
| `/daily-journal` | Capture today's learnings into lived experiences |
| `/create-skill` | Create a new reusable workflow |
| `/improve-skill` | Enhance a skill based on learnings |
| `/create-consultant` | Clone an expert's frameworks |

## Improving Skills

After running any skill, look for opportunities to improve it. If the user mentions something that could be better, or if you notice a pattern, suggest:

> "Should I add this to the skill so it works better next time?"

Or prompt them:

> "Based on our conversation, I could improve the [skill-name] skill. Want me to update it?"

## Principles

1. **Reference lived experiences** — The user's past learnings are more valuable than generic advice
2. **Match their voice** — Use examples in best-work to match style
3. **Apply frameworks** — Use consultant frameworks for strategic feedback
4. **Improve skills recursively** — After running a skill, suggest learnings to add
5. **Be specific** — Generic advice is useless. Reference specific entries, examples, frameworks.
