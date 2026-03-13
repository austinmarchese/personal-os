# Personal OS

A starter kit for building your own AI-powered operating system. Turn Claude Code into a team of specialists that know how you think, what you've learned, and what good looks like.

**This isn't about vibe coding. It's about codifying the way you work.**

---

## What This Is

Personal OS is a folder structure that makes AI smarter about YOU over time:

- **Lived Experiences** — A journal of what you've learned, built, and discovered
- **Consultants** — Cloned experts whose frameworks you can apply at scale
- **Skills** — Reusable workflows that improve themselves
- **Best Work** — Examples that teach AI your standards

The more you use it, the smarter it gets.

---

## Quick Start (5 minutes)

### 1. Clone this repo

```bash
git clone https://github.com/austinmarchese/personal-os.git ~/personal-os
cd ~/personal-os
```

### 2. Install Claude Code (if you haven't)

```bash
npm install -g @anthropic-ai/claude-code
```

### 3. Start Claude Code

```bash
claude
```

### 4. Create your first journal entry

```
/daily-journal
```

That's it. You just started building your lived knowledge base.

---

## The System

```
personal-os/
├── context/
│   ├── lived-experiences/    # Your daily journal → lived knowledge base
│   ├── best-work/            # Examples of YOUR best outputs
│   └── consultants/          # Cloned experts (frameworks you've extracted)
├── skills/
│   └── daily-journal/        # Your first skill (included)
└── CLAUDE.md                 # Instructions for Claude
```

---

## Daily Practice: Journal Your Learnings

At the end of each day, run:

```
/daily-journal
```

Claude will ask what happened, extract the key learning, and save it to your lived knowledge base.

**Why this matters:** Generic AI gives generic advice. AI with YOUR lived experiences gives advice grounded in what you've actually done.

---

## Create Your First Skill

A skill is a reusable workflow. Instead of explaining the same process every time, you write it once and run it as a command.

**To create a skill, run:**

```
/create-skill
```

Claude will ask:
1. What workflow do you want to codify?
2. What are the steps?
3. What inputs does it need?

Then it creates the skill file for you.

**Good first skills:**
- Weekly review
- Meeting notes processor
- Email drafting workflow
- Research synthesis

---

## Improve Your Skills

Skills should get better over time. After running a skill, if you notice something that could be improved, run:

```
/improve-skill
```

Or just tell Claude:

> "Based on our conversation, can you update the [skill-name] skill with what we learned? Add it to the learnings section and update the process if needed."

**Example improvements:**
- "Add a step to check for X before Y"
- "The output format should include Z"
- "Ask about A upfront to avoid backtracking"

The skill gets smarter with every use.

---

## Clone Your First Consultant

A "consultant" is someone whose thinking you want to apply at scale.

**How to clone an expert:**

1. Pick someone whose frameworks you admire
2. Consume their content (videos, podcasts, articles)
3. Run: `/create-consultant`

Claude will help you extract:
- Their core philosophy
- Their frameworks
- Questions they'd ask

**Example included:** See `context/consultants/_example-consultant.md` for a complete example.

---

## Add Your Best Work

AI learns your standards from examples, not rules.

Add files to `context/best-work/`:
- Your best emails
- Reports that landed well
- Writing you're proud of

When you ask AI to write something, it matches YOUR voice.

---

## Key Commands

| Command | What it does |
|---------|--------------|
| `/daily-journal` | Capture today's learnings |
| `/create-skill` | Create a new reusable workflow |
| `/improve-skill` | Enhance a skill based on learnings |
| `/create-consultant` | Clone an expert's frameworks |

---

## How It Gets Better Over Time

The magic is in the feedback loops:

1. **Lived experiences compound** — Every entry makes AI smarter about you
2. **Skills improve themselves** — Add learnings after each use
3. **Consultants get sharper** — Add new frameworks as you discover them

**After 30 days:** AI knows your voice, your experiences, and your standards.

**After 90 days:** It feels like a team, not a tool.

---

## The Shift

The opportunity isn't "AI writes my emails faster."

The opportunity is: **AI runs your playbooks, your frameworks, your accumulated wisdom—and improves them every time.**

One person. A small company's worth of output.

---

## License

MIT — use this however you want.

## Author

Built by [Austin Marchese](https://youtube.com/@austin.marchese)

Part of [The AI Playbook](https://the-ai-playbook.com/) newsletter.
