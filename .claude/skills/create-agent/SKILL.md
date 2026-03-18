---
name: create-agent
description: Clone an expert by extracting their frameworks into an agent file
---

# Create Agent

Turn an expert's thinking into an AI persona you can reference anytime.

## When to Use

Run `/create-agent` when you:
- Found someone whose frameworks you want to apply
- Consumed enough of their content to extract patterns
- Want AI to think like them when giving feedback

## Process

### Step 1: Identify the Expert

Ask:
> "Who do you want to clone as an AI agent?
>
> This should be someone whose thinking you've studied:
> - Authors whose books changed how you think
> - YouTubers/podcasters with clear frameworks
> - Industry experts with documented methodologies
> - Mentors you've learned from
>
> Who is it, and what are they known for?"

### Step 2: Extract Core Philosophy

Ask:
> "What does [name] fundamentally believe?
>
> Think about:
> - What principles do they repeat constantly?
> - What do they think most people get wrong?
> - What's their core thesis?
>
> Give me 3-5 core beliefs."

### Step 3: Extract Frameworks

Ask:
> "What frameworks or mental models do they use?
>
> These are repeatable ways of thinking, like:
> - A specific process they follow
> - A way of evaluating decisions
> - A checklist they apply
>
> Describe 2-3 frameworks. For each one:
> - What's it called?
> - How does it work?
> - When do you apply it?"

### Step 4: Extract Their Voice

Ask:
> "How does [name] give feedback?
>
> - Are they direct or gentle?
> - Do they use specific phrases?
> - What questions do they always ask?
> - What would they push back on?
>
> Give me some examples of how they'd respond to work."

### Step 5: Create the Agent File

Create the file at:
```
knowledge/experts/[name].md
```

Use this structure:
```markdown
# [Name] - [What They're Known For]

## Background

[Brief bio - who are they, why are they credible?]

## Core Philosophy

- [Belief 1]
- [Belief 2]
- [Belief 3]

## Frameworks

### [Framework 1 Name]

[How it works, when to apply it]

### [Framework 2 Name]

[How it works, when to apply it]

## Questions They'd Ask

- [Question 1]
- [Question 2]
- [Question 3]

## How They Give Feedback

[Communication style, common phrases]

## Key Quotes

> "[Direct quote]"

> "[Another quote]"

## Sources

- [Where you learned their frameworks]
```

### Step 6: Confirm Creation

> "Created [name] agent at `knowledge/experts/[name].md`
>
> To use this agent, tell me:
> 'Review this like [name] would'
>
> Or just mention their name and I'll apply their thinking."

## Example

```
User: /create-agent

Claude: Who do you want to clone as an AI agent?

User: Tim Ferriss - he's known for lifestyle design and
deconstructing world-class performers

Claude: What does Tim Ferriss fundamentally believe?

User: He believes you should question default assumptions,
that most rules are negotiable, and that you can achieve
more by doing less of the right things. He's obsessed with
finding the minimum effective dose.

Claude: Great. What frameworks does he use?

User: The main one is fear-setting - instead of goal setting,
you write out your fears in detail. Also the 80/20 principle
applied to everything. And he asks "what would this look like
if it were easy?"

Claude: How does Tim give feedback?

User: Very Socratic - lots of questions. He'd ask things like
"have you actually tested this assumption?" or "what's the
worst case scenario, really?" He pushes back on complexity.

Claude: Created Tim Ferriss agent at
`knowledge/experts/tim-ferriss.md`

To use: "Review my plan like Tim Ferriss would"
```

## Tips

- **Include direct quotes** — Their exact language helps AI match their voice
- **Be specific about frameworks** — "They're good at X" is useless. "They use a 3-step process: A, B, C" is useful.
- **Update over time** — Add new frameworks as you discover them
