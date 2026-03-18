# Consultants

Experts you've "cloned" by extracting their frameworks.

## Why This Matters

You can't hire every expert. But you can document how they think.

A consultant file captures:
- Their core philosophy
- Their frameworks and mental models
- Questions they'd ask
- How they give feedback

When you need feedback, AI applies their thinking to your specific situation.

## How to Clone an Expert

### Step 1: Pick someone whose thinking you admire

Good candidates:
- Authors whose books changed how you think
- YouTubers/podcasters with clear frameworks
- Industry experts with documented methodologies
- Mentors you've learned from

### Step 2: Consume their content

- Watch their videos, listen to their podcasts
- Read their books or articles
- Note the patterns in how they think

### Step 3: Extract their frameworks

Create a folder for them:
```bash
mkdir [name]
cp _template.md [name]/frameworks.md
```

Fill in:
- **Core Philosophy** — What do they fundamentally believe?
- **Frameworks** — What mental models do they use?
- **Questions They'd Ask** — What would they push back on?
- **How They Give Feedback** — What's their communication style?

### Step 4: Use them

When you need feedback in their domain, tell Claude to reference their file.

Example: "Review this thumbnail using the frameworks in `knowledge/experts/paddy-galloway/`"

## Example

See `_example-consultant.md` for a complete example.

## Tips

- **Be specific about frameworks.** "They're good at marketing" is useless. "They use a 3-step hook formula: problem → agitation → solution" is useful.
- **Include direct quotes.** Their exact language helps AI match their voice.
- **Update over time.** Add new frameworks as you discover them.
