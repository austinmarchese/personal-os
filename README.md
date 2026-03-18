# Personal OS

A starter kit for building your own AI-powered operating system. Turn Claude Code into a team that knows how you think, what you've learned, and what good looks like.

**This isn't about vibe coding. It's about codifying the way you work.**

---

## What This Is

Personal OS is a folder structure that makes AI smarter about YOU over time:

- **Your profile** — Goals, voice, preferences
- **Lived experiences** — A journal of what you've learned and built
- **Experts** — Cloned advisors whose frameworks you can apply
- **Projects** — Active work that becomes training data when done
- **Skills** — Reusable workflows that improve themselves

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

### 4. Set up your profile

```
/interview-me
```

Claude will ask about your goals, background, and how you work. This becomes the foundation for everything else.

---

## The System

```
personal-os/
├── .claude/
│   ├── agents/              # AI personas (experts you clone)
│   └── skills/              # Reusable workflows
│
├── knowledge/               # What you KNOW
│   ├── me/                  # Who you are
│   │   ├── about.md         # Background, goals
│   │   ├── voice.md         # How you communicate
│   │   └── preferences.md   # Tools, workflows
│   ├── lived-experiences/   # Daily learnings
│   ├── best-work/           # Examples of your best outputs
│   └── experts/             # Cloned expert frameworks
│
├── projects/                # What you're MAKING
│   ├── [your projects]/     # Active work
│   └── done/                # Finished (becomes training data)
│
└── CLAUDE.md
```

---

## Key Commands

| Command | What it does |
|---------|--------------|
| `/interview-me` | Set up your profile (goals, voice, preferences) |
| `/define-audience` | Define who you're creating content for |
| `/daily-journal` | Capture today's learnings |
| `/weekly-review` | Weekly reflection and planning |
| `/brainstorm-project` | Turn an idea into a concrete project |
| `/create-skill` | Create a new reusable workflow |
| `/create-agent` | Clone an expert's frameworks |
| `/improve-skill` | Enhance a skill based on learnings |

---

## First Week Workflow

### Day 1: Set Up
```
/interview-me
```
Tell Claude about your goals, background, and how you work.

### Day 2-6: Capture Daily
```
/daily-journal
```
At the end of each day, spend 2 minutes capturing what you learned.

### Day 7: Review
```
/weekly-review
```
Reflect on the week, capture insights, plan ahead.

---

## Use Cases

Personal OS works for:

- **Content creators** — Social media, newsletters, YouTube
- **Knowledge workers** — Reports, emails, presentations
- **Side projects** — Apps, designs, experiments
- **Life admin** — Selling a house, planning events, organizing

### Example: Social Media Campaign

1. `/interview-me` → Define your goals
2. `/define-audience` → Who are you speaking to?
3. `/brainstorm-project` → Plan the campaign
4. Work on it in `projects/social-media-campaign/`
5. When done, move to `projects/done/` → becomes training data

### Example: Side Project

1. `/brainstorm-project` → "I want to build an app for X"
2. Claude creates `projects/my-app/` with phases and first step
3. Work on it, capturing learnings with `/daily-journal`
4. When shipped, move to `projects/done/`

---

## How It Gets Better Over Time

The magic is in the feedback loops:

1. **Your profile deepens** — Goals evolve, voice gets sharper
2. **Lived experiences compound** — Every entry makes AI smarter
3. **Skills improve themselves** — Add learnings after each use
4. **Projects become training data** — Done work teaches AI your standards

**After 30 days:** AI knows your voice, your experiences, and your goals.

**After 90 days:** It feels like a team, not a tool.

---

## Adding Experts

An "expert" is someone whose thinking you want to apply at scale.

1. Pick someone whose frameworks you admire
2. Consume their content (videos, podcasts, articles)
3. Run: `/create-agent`
4. Claude helps you extract their philosophy, frameworks, and questions

See `knowledge/experts/_example-consultant.md` for a complete example.

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
