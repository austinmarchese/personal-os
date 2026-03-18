---
name: brainstorm-project
description: Turn a vague idea into a concrete project with clear next steps
---

# Brainstorm Project

Take a half-baked idea and turn it into a real project. Works for side projects, content ideas, business ideas, or life projects (selling an apartment, planning an event).

## When to Use

- You have an idea but don't know where to start
- You're stuck in "thinking about it" mode
- You want to quickly scope something out

## Process

### Step 1: Get the Idea Out

Ask:
> "What's the idea? Just dump it out — doesn't need to be organized."

Let them ramble. Then summarize:
> "So if I understand right, you want to [summary]. Is that the gist?"

### Step 2: Clarify the Goal

Ask:
> "What does 'done' look like? How will you know this project is successful?"

If they're vague:
> "Let's make it concrete. In 3 months, what would make you say 'that worked'?"

### Step 3: Identify Constraints

Ask:
> "What are you working with?
> - How much time can you spend on this?
> - Any budget constraints?
> - Any deadlines or dependencies?
> - What skills/resources do you already have?"

### Step 4: Break It Down

Ask:
> "What are the major chunks of work? Let's break this into phases."

Help them identify 3-5 phases or milestones:
> "Here's how I'd break this down:
>
> 1. **[Phase 1]** — [What happens]
> 2. **[Phase 2]** — [What happens]
> 3. **[Phase 3]** — [What happens]
>
> Does that feel right?"

### Step 5: Find the First Step

Ask:
> "What's the very first thing you'd need to do to start Phase 1?"

Then:
> "Can you do that this week? What day?"

Make it concrete and time-bound.

### Step 6: Identify Risks

Ask:
> "What might derail this? What's the most likely reason you'd give up or stall?"

Help them plan around it:
> "How could you prevent that, or catch it early?"

### Step 7: Create the Project

Create a project folder in `projects/`:

```
projects/
└── [project-name]/
    ├── README.md       # Overview, goals, phases
    └── notes.md        # Working notes
```

README.md format:
```markdown
# [Project Name]

## Goal
[What does done look like?]

## Timeline
[Any deadlines or target dates]

## Phases
1. **[Phase 1]** — [Description]
2. **[Phase 2]** — [Description]
3. **[Phase 3]** — [Description]

## First Step
- [ ] [Specific action] — by [date]

## Risks
- [Risk 1] → [Mitigation]

## Notes
- [Any other context]
```

### Step 8: Confirm

> "Created `projects/[name]/` with your project plan.
>
> **Your first step:** [Action] by [Date]
>
> When you're ready to work on this, just open Claude in that folder and we can pick up where we left off."

## Example Projects This Works For

- **Side project:** "I want to build an app for wound care tracking"
- **Content:** "I need to do a social media branding campaign"
- **Life admin:** "I need to sell my NYC apartment"
- **Design:** "I want to redesign my friend's backyard setup"
- **Learning:** "I want to get better at using AI tools"

## Tips

- Don't over-plan — just enough structure to start
- First step should be doable in < 30 minutes
- If the project is huge, help them pick a smaller starting scope
- Reference their goals from `knowledge/me/about.md` if relevant
