# Personal OS

A starter kit for building your own AI-powered operating system. Turn Claude Code into a team of specialists that know how you think, what you've learned, and what good looks like.

**This isn't about vibe coding. It's about codifying the way you work.**

---

## What This Is

Personal OS is a folder structure that makes AI smarter about YOU over time:

- **Lived Experiences** — A journal of what you've learned, built, and discovered
- **Consultants** — Cloned experts whose frameworks you can apply at scale
- **Audience** — Real people you've interviewed, documented as permanent advisors
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

### 3. Create your first journal entry

```bash
cp context/lived-experiences/_template.md context/lived-experiences/$(date +%Y-%m-%d)-first-entry.md
```

Open that file and fill it in with something real from today.

### 4. Start Claude Code in this directory

```bash
cd ~/personal-os
claude
```

Now Claude has access to everything in your Personal OS.

---

## The System

```
personal-os/
├── context/
│   ├── lived-experiences/    # Your daily journal → lived knowledge base
│   ├── best-work/            # Examples of YOUR best outputs
│   ├── consultants/          # Cloned experts (frameworks you've extracted)
│   └── audience/             # Real people you've interviewed
├── skills/
│   └── daily-journal/        # Your first skill (included)
└── .claude/
    └── settings.json         # Claude Code project settings
```

---

## Step-by-Step Setup

### Step 1: Build Your Lived Knowledge Base (Day 1)

This is the most important part. Every day, you learn things. You solve problems. You have insights. Then you forget them.

Your **Lived Knowledge Base** captures everything so AI can reference it later.

**End of each day:**

1. Open a new entry:
   ```bash
   cp context/lived-experiences/_template.md context/lived-experiences/$(date +%Y-%m-%d)-slug.md
   ```

2. Fill in what happened:
   - What did you work on?
   - What did you learn?
   - What would you tell yourself next time?

3. The entry gets saved. AI can now reference it forever.

**Why this matters:** Generic AI gives generic advice. AI with YOUR lived experiences gives advice grounded in what you've actually done.

---

### Step 2: Clone Your First Consultant (Day 2-3)

A "consultant" is someone whose thinking you want to apply at scale.

**How to clone an expert:**

1. Pick someone whose frameworks you admire
2. Consume their content (videos, podcasts, articles)
3. Extract their frameworks into a markdown file

```bash
mkdir context/consultants/[name]
cp context/consultants/_template.md context/consultants/[name]/frameworks.md
```

4. Fill in:
   - Their core philosophy (what do they believe?)
   - Their frameworks (how do they think?)
   - Questions they'd ask (what would they push back on?)

**Example:** See `context/consultants/_example-consultant.md`

Now when you need feedback, AI can think like them.

---

### Step 3: Document Your Audience (Week 1-2)

This is the part nobody talks about.

**Interview real people** in your target audience. Not surveys—actual conversations.

Ask them:
- What do you click on? What makes you bounce?
- What's the difference between content you'd watch vs. ask ChatGPT?
- What titles/topics turn you off?

Then document everything:

```bash
cp context/audience/_template.md context/audience/[name].md
```

**Why this matters:** Most people guess what their audience wants. You'll have documented preferences from real humans, applied to every decision.

---

### Step 4: Add Your Best Work (Ongoing)

AI learns your standards from examples, not rules.

Add files to `context/best-work/`:
- Your best emails
- Reports that landed well
- Proposals that closed
- Writing you're proud of

Organize by type:
```
context/best-work/
├── emails/
├── reports/
├── proposals/
└── writing/
```

When you ask AI to write something, it matches YOUR voice, not generic AI voice.

---

### Step 5: Create Your First Skill (Week 2)

A skill is a reusable workflow. Instead of explaining the same process every time, you write it once and run it as a command.

This repo includes one skill: `/daily-journal`

To create your own:

```bash
mkdir skills/[skill-name]
cp skills/_template/SKILL.md skills/[skill-name]/SKILL.md
```

**Good first skills:**
- Weekly review
- Meeting notes processor
- Email drafting workflow
- Content outline generator

---

## How It Gets Better Over Time

The magic is in the feedback loops:

1. **Lived experiences compound** — Every entry makes AI smarter about you
2. **Skills improve themselves** — Add learnings after each use
3. **Consultants get sharper** — Add new frameworks as you discover them
4. **Audience docs get refined** — Update with new interview insights

**After 30 days:** AI knows your voice, your experiences, your audience, and your standards.

**After 90 days:** It feels like a team, not a tool.

---

## Folder Reference

| Folder | Purpose | Update Frequency |
|--------|---------|------------------|
| `context/lived-experiences/` | Daily journal entries | Daily |
| `context/best-work/` | Examples of your best outputs | As you create good work |
| `context/consultants/` | Expert frameworks you've extracted | When you find new experts |
| `context/audience/` | Real people you've interviewed | After interviews |
| `skills/` | Reusable workflows | When you notice repeated processes |

---

## Tips

**Start small.** Don't try to build everything at once. Begin with daily journaling. Add consultants and audience docs over time.

**Be specific.** "Had a good meeting" is useless. "Learned that finance wants weekly reports because monthly is too slow for their planning cycle" is gold.

**Use voice memos.** Easiest way to capture lived experiences. Transcribe at end of day, then process into an entry.

**Update your skills.** After running a skill, ask: "What would make this better next time?" Add it to the skill file.

---

## The Shift

The opportunity isn't "AI writes my emails faster."

The opportunity is: **AI runs your playbooks, applies your frameworks, references your experiences—and improves every time.**

One person. A small company's worth of output.

---

## License

MIT — use this however you want.

## Author

Built by [Austin Marchese](https://youtube.com/@austin.marchese)

Part of [The AI Playbook](https://the-ai-playbook.com/) newsletter.
