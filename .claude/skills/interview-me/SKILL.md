---
name: interview-me
description: Get to know the user through conversation and capture their context for later reference
---

# Interview Me

A conversation to learn who you are. Not a form — a real conversation that helps AI understand your background, goals, and how you think.

## When to Use

- First time setting up Personal OS
- When you want AI to really understand you
- After a major life change
- When AI responses feel too generic

## The Goal

By the end, AI should know:
- Where you came from
- What you're working on now
- Where you're trying to go
- How you think and communicate

This context informs everything else.

## Process

### Step 1: Start the Conversation

> "I'd love to learn about you. Not a job interview — just a conversation so I can actually be helpful.
>
> Let's start simple: what's your story? How'd you get to where you are now?"

Let them talk. Ask follow-ups based on what they share:
- "What made you make that switch?"
- "What was that like?"
- "How did that change how you think about things?"

### Step 2: Understand Their Current World

> "So that's how you got here. What does your life look like now?
>
> What do you spend most of your time on?"

Dig into:
- What they do day-to-day
- What they're responsible for
- What's working well
- What's frustrating

### Step 3: Learn Their Goals

> "Where are you trying to go? What are you working toward?"

Get specific:
- "What does success look like in the next few months?"
- "What about longer term — where do you want to be in a few years?"
- "What would have to change for you to get there?"

### Step 4: Understand What's in the Way

> "What's making that hard? What gets in the way?"

This reveals:
- Constraints (time, money, skills)
- Blockers (specific obstacles)
- Patterns (things they keep running into)

### Step 5: Learn How They Work

> "How do you like to work? What's your style?"

Explore:
- "Are you more of a planner or do you figure it out as you go?"
- "How do you make decisions?"
- "What kind of help is actually helpful vs. annoying?"

### Step 6: Capture What Matters to Them

> "What do you care about? What's important to you beyond just work?"

This might include:
- Values
- Interests
- People in their life
- What they do for fun

### Step 7: Summarize and Save

Summarize everything in a conversational way:

> "Here's what I learned about you:
>
> **Your story:** [2-3 sentences on their background]
>
> **Where you are now:** [Current situation]
>
> **Where you're going:** [Goals]
>
> **What's in the way:** [Challenges]
>
> **How you work:** [Style, preferences]
>
> **What matters to you:** [Values, interests]
>
> Does this sound right? Anything I'm missing?"

### Step 8: Update Files

Save to `knowledge/me/about.md` in a natural format:

```markdown
# About Me

## My Story
[Their background in their own words]

## Where I Am Now
[Current situation, what they're working on]

## Where I'm Going
[Goals — short and long term]

## What Gets in the Way
[Challenges, constraints, patterns]

## How I Work
[Work style, decision-making, what kind of help they want]

## What Matters to Me
[Values, interests, people, non-work stuff]

---
*Last updated: [date]*
```

Confirm:
> "Saved your context to `knowledge/me/about.md`.
>
> From now on, I'll reference this when we work together. If anything changes, just tell me or run `/interview-me` again."

## Tips

- **Listen more than you ask.** Follow what they're interested in talking about.
- **Use their words.** Don't translate into formal language.
- **Go where the energy is.** If they light up about something, explore it.
- **It's okay to be incomplete.** You can always add more later.
- **This isn't a one-time thing.** People change. Update as needed.

## Example Flow

```
Claude: I'd love to learn about you. What's your story? How'd you get to where you are now?

User: I was in tech for 10 years, mostly product management. Got burned out, took a year off, now I'm trying to figure out what's next. Thinking about starting something of my own.

Claude: What made you burn out? Was it the work itself or something else?

User: Honestly, I was good at my job but I didn't care about what we were building. Enterprise software. I want to work on something that actually matters to me.

Claude: Makes sense. What does "matters to you" look like? What kind of problems do you actually care about?

User: Health stuff, probably. My mom got sick a few years ago and navigating the healthcare system was a nightmare. I keep thinking there has to be a better way.

Claude: That's a strong motivation. So where are you now with that? Just thinking about it, or actively exploring?

[...conversation continues...]
```

## What This Unlocks

Once AI knows your context:
- Advice is grounded in YOUR situation, not generic
- Goals inform project suggestions
- Challenges are accounted for
- Communication matches your style

**Generic AI:** "Here are 5 tips for productivity"
**AI that knows you:** "Given your energy issues in the afternoon, what if you blocked deep work for mornings only?"
