# CLAUDE.md - Personal OS

This file provides guidance to Claude Code when working in this repository.

## What This Is

Personal OS turns Claude into a system that knows YOU — your goals, your voice, your experiences. The more you use it, the smarter it gets.

## Folder Structure

```
personal-os/
├── .claude/
│   ├── agents/              # AI personas you create
│   └── skills/              # Reusable workflows
│
├── knowledge/               # What you KNOW (training data)
│   ├── me/                  # Who you are
│   │   ├── about.md         # Background, goals
│   │   ├── voice.md         # How you communicate
│   │   └── preferences.md   # Tools, workflows
│   ├── lived-experiences/   # Daily learnings
│   ├── best-work/           # Examples of your best outputs
│   └── experts/             # Cloned expert frameworks
│
├── projects/                # What you're MAKING
│   ├── [active projects]/   # Work in progress
│   └── done/                # Finished (becomes training data)
│
└── CLAUDE.md
```

## How to Use Context

When helping the user:

1. **Check `knowledge/me/`** — Understand their goals, voice, preferences
2. **Reference `lived-experiences/`** — Pull from their past learnings
3. **Match `best-work/`** — Use their examples to match style
4. **Apply `experts/`** — Use expert frameworks for feedback
5. **Check `projects/`** — Know what they're working on

## Skills

Skills are in `.claude/skills/[name]/SKILL.md`. When the user runs `/[skill-name]`, read the SKILL.md and follow the process.

| Command | What it does |
|---------|--------------|
| `/interview-me` | Build your profile in knowledge/me/ |
| `/define-audience` | Define who you're creating content for |
| `/daily-journal` | Capture today's learnings |
| `/weekly-review` | Weekly reflection and planning |
| `/brainstorm-project` | Turn an idea into a concrete project |
| `/create-skill` | Create a new reusable workflow |
| `/create-agent` | Clone an expert's frameworks |
| `/improve-skill` | Enhance a skill based on learnings |

## Getting Started Flow

Recommended first-time setup:

1. `/interview-me` — Fill out your profile
2. `/define-audience` — (If creating content) Define who you're speaking to
3. `/brainstorm-project` — Start your first project
4. `/daily-journal` — Start capturing learnings

## Key Principles

1. **Use their context** — Reference `knowledge/me/` and `lived-experiences/`, not generic advice
2. **Match their voice** — Use `best-work/` examples to match style
3. **Be specific** — "Based on your goal of X..." not "Many people find..."
4. **Improve skills** — After running a skill, suggest learnings to add
5. **Reference projects** — Know what they're actively working on

## Project Lifecycle

```
projects/[name]/     →     projects/done/[name]/
    (active)                    (finished)
```

When a project is done, move it to `projects/done/`. Finished projects become training data for future work.
