---
name: daily-journal
description: End-of-day capture of what you learned, built, and discovered
---

# Daily Journal

Capture your daily learnings into your lived knowledge base.

## When to Use

Run `/daily-journal` at the end of each day to:
- Document what you worked on
- Capture key learnings before you forget them
- Build your lived knowledge base over time

## Process

### Step 1: Ask What Happened

Ask the user:
> "What happened today worth remembering? This could be:
> - A problem you solved
> - Something you learned
> - A decision you made
> - A conversation that changed your thinking"

### Step 2: Extract the Key Elements

From their response, identify:
1. **The Story** — What actually happened? (Be specific)
2. **The Learning** — What's the transferable insight?
3. **The Quotable** — How would they naturally say this?
4. **Tags** — What topics does this cover?

### Step 3: Create the Entry

Generate a markdown file with this structure:

```markdown
# [DATE] - [Brief Descriptive Title]

## Metadata
- **Date:** [TODAY]
- **Tags:** [extracted tags]
- **Project/Context:** [what they were working on]

## What Happened

[The story, written in first person]

## Key Learning

[The transferable insight]

## Quotable

> "[Natural language quote]"
```

### Step 4: Save the Entry

Save to: `context/lived-experiences/[DATE]-[slug].md`

Confirm: "Logged to lived experiences: `[filename]`"

### Step 5: Optional - Connect to Current Work

Ask:
> "Is there anything you're working on where this learning might apply? I can flag it for future reference."

## Inputs Needed

- User's description of what happened (voice memo transcript or typed)

## Output

- Markdown file in `context/lived-experiences/`
- Confirmation message

## Example

```
User: /daily-journal

Claude: What happened today worth remembering?

User: Spent way too long debugging an API issue. Turns out the auth
tokens were expiring and the error messages weren't clear. Should
have checked that first.

Claude: Got it. Here's what I captured:

**What Happened:** Debugged an API integration issue for several hours.
Root cause was expired auth tokens, but error messages didn't make
this clear.

**Key Learning:** When API calls fail silently, check auth token
expiration first—before diving into the code.

**Quotable:** "The bug that takes 3 hours is usually the thing you
assumed was working."

Logged to lived experiences: `2026-03-13-api-auth-debugging.md`

Is there anything you're working on where this learning might apply?
```

## Learnings

[Add learnings here after each use]

- Keep entries specific—"had a good day" is useless
- Voice memo transcripts work great as input
- The quotable should sound natural, not polished
