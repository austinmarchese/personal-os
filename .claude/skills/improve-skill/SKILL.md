---
name: improve-skill
description: Enhance a skill based on learnings from using it
---

# Improve Skill

Make a skill better based on what you learned while using it.

## When to Use

Run `/improve-skill` when:
- You just ran a skill and noticed something that could be better
- You have feedback on how a skill should work differently
- You want to add learnings from a conversation to a skill

## Process

### Step 1: Identify the Skill

Ask:
> "Which skill do you want to improve?
>
> Available skills:"

List all skills in `skills/` folder (excluding `_template`).

### Step 2: Understand the Improvement

Ask:
> "What should be better about this skill? For example:
> - Add a step that was missing
> - Change the order of steps
> - Add a question to ask upfront
> - Improve the output format
> - Add a learning for next time
>
> Or just describe what happened and I'll suggest improvements."

### Step 3: Review Current Skill

Read the current SKILL.md file and summarize:
> "Here's the current skill:
>
> **Steps:**
> 1. [current step 1]
> 2. [current step 2]
>
> **Learnings so far:**
> - [any existing learnings]
>
> Based on your feedback, here's what I'd change:
>
> [Proposed changes]
>
> Should I apply these changes?"

### Step 4: Apply Changes

If user approves, update the SKILL.md file with:
- Modified steps (if process changed)
- New learnings added to the Learnings section
- Any other improvements

### Step 5: Confirm

> "Updated `skills/[skill-name]/SKILL.md`
>
> Changes made:
> - [change 1]
> - [change 2]
>
> The skill will use these improvements next time you run it."

## Quick Mode

If user says something like:
> "Based on our conversation, can you improve the [skill-name] skill?"

Then:
1. Review the conversation for relevant learnings
2. Read the current skill file
3. Propose specific improvements
4. Apply on approval

## Example

```
User: /improve-skill

Claude: Which skill do you want to improve?

Available skills:
- daily-journal
- weekly-review

User: daily-journal

Claude: What should be better about this skill?

User: It should ask me about blockers - things that are frustrating
me or slowing me down. Those are useful to track.

Claude: Got it. Here's the current daily-journal process:

**Steps:**
1. Ask what happened
2. Extract key learning
3. Save entry

**Proposed change:**
Add Step 1b: "Ask about blockers or frustrations"

And update the entry template to include a "Blockers" section.

Should I apply these changes?

User: Yes

Claude: Updated `skills/daily-journal/SKILL.md`

Changes made:
- Added step to ask about blockers
- Added Blockers section to entry template
- Added learning: "Tracking blockers helps identify patterns"

Next time you run `/daily-journal`, it will ask about blockers.
```

## Conversation-Based Improvement

```
User: Based on our back and forth today, can you improve the
weekly-review skill with what we learned?

Claude: Looking at our conversation, I noticed:

1. You wanted to see completed tasks from last week (not just planned)
2. You asked me to highlight tasks that rolled over multiple weeks
3. The energy check at the end was helpful

Proposed improvements to `/weekly-review`:
- Add step: Pull completed tasks from last week
- Add step: Flag any task that's been on the list 3+ weeks
- Add step: Quick energy/motivation check before setting priorities

Should I apply these?

User: Yes

Claude: Updated `skills/weekly-review/SKILL.md` with all three improvements.
```
