---
name: create-skill
description: Create a new reusable skill from a workflow you do repeatedly
---

# Create Skill

Turn a repeatable workflow into a skill you can run with one command.

## When to Use

Run `/create-skill` when you:
- Notice you're explaining the same process repeatedly
- Have a workflow with clear steps
- Want to codify something so AI can do it consistently

## Process

### Step 1: Identify the Workflow

Ask the user:
> "What's a workflow you do repeatedly that you'd like to turn into a skill?
>
> Good candidates:
> - Weekly review
> - Meeting notes processing
> - Email drafting
> - Research synthesis
> - Content outlining
>
> Describe what you do, step by step."

### Step 2: Extract the Steps

From their description, identify:
1. The trigger (when do you run this?)
2. The inputs needed (what information does it require?)
3. The steps (what happens in order?)
4. The output (what does it produce?)

Confirm with the user:
> "Here's what I understood:
>
> **When to use:** [trigger]
> **Inputs:** [what's needed]
> **Steps:**
> 1. [step 1]
> 2. [step 2]
> 3. [step 3]
> **Output:** [what it produces]
>
> Does this capture your workflow? What's missing?"

### Step 3: Choose a Name

Ask:
> "What should we call this skill? Use lowercase with hyphens (e.g., `weekly-review`, `meeting-notes`)"

### Step 4: Create the Skill File

Create the folder and SKILL.md file:
```
skills/[skill-name]/SKILL.md
```

Use this structure:
```markdown
---
name: [skill-name]
description: [one-line description]
---

# [Skill Name]

[Brief description of what this skill does]

## When to Use

Run `/[skill-name]` when you:
- [situation 1]
- [situation 2]

## Process

### Step 1: [First Step]
[What to do]

### Step 2: [Second Step]
[What to do]

[Continue for all steps]

## Inputs Needed

- [input 1]
- [input 2]

## Output

[What this skill produces]

## Learnings

[Empty section - add learnings after each use]
```

### Step 5: Confirm Creation

Tell the user:
> "Created `/[skill-name]` at `skills/[skill-name]/SKILL.md`
>
> Try it now: `/[skill-name]`
>
> After using it, run `/improve-skill` to make it better based on what you learned."

## Example

```
User: /create-skill

Claude: What's a workflow you do repeatedly that you'd like to turn into a skill?

User: Every Monday I review what happened last week, what's coming up,
and set my priorities. I look at my calendar, check my task list,
and write a short summary.

Claude: Here's what I understood:

**When to use:** Start of each week (Monday)
**Inputs:** Calendar access, task list
**Steps:**
1. Review last week - what got done, what didn't
2. Look at upcoming calendar for the week
3. Identify top 3 priorities
4. Write a short summary

**Output:** Weekly summary with priorities

Does this capture your workflow?

User: Yes, but also add a step to check what's blocking me

Claude: Got it. What should we call this skill?

User: weekly-review

Claude: Created `/weekly-review` at `skills/weekly-review/SKILL.md`

Try it now: `/weekly-review`
```
