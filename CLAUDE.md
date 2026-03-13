# CLAUDE.md - Personal OS

This file provides guidance to Claude Code when working in this repository.

## What This Is

Personal OS is a system for building a lived knowledge base that enhances everything you do with AI. It contains:

- **Lived Experiences** — Daily journal entries of what the user learned
- **Best Work** — Examples that teach AI the user's standards
- **Consultants** — Expert frameworks the user has documented
- **Audience** — Real people the user has interviewed
- **Skills** — Reusable workflows

## How to Use This Context

When helping the user:

1. **Check lived experiences** for relevant past learnings
2. **Reference best work** when matching voice/style
3. **Apply consultant frameworks** when giving strategic feedback
4. **Consider audience preferences** when reviewing content

## Key Folders

| Folder | Purpose |
|--------|---------|
| `context/lived-experiences/` | Daily journal entries—the user's accumulated wisdom |
| `context/best-work/` | Examples of the user's best outputs |
| `context/consultants/` | Expert frameworks to apply |
| `context/audience/` | Real people to consider when creating content |
| `skills/` | Reusable workflows |

## Skills

Skills are in `skills/[name]/SKILL.md`. When the user runs `/[skill-name]`, read the SKILL.md and follow the process.

**Available skills:**
- `/daily-journal` — End-of-day capture of learnings

## Principles

1. **Reference lived experiences** — The user's past learnings are more valuable than generic advice
2. **Match their voice** — Use examples in best-work to match style
3. **Apply frameworks** — Use consultant frameworks for strategic feedback
4. **Improve skills** — After running a skill, suggest learnings to add
5. **Be specific** — Generic advice is useless. Reference specific entries, examples, frameworks.
