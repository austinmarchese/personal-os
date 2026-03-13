# Audience

Real people you've interviewed, documented as permanent advisors.

## Why This Matters

Most people guess what their audience wants.

You'll have documented preferences from real humans—applied to every creative decision.

When you're creating content, titles, products—you can ask: "Would [person] click this? Would [person] buy this?"

AI checks their documented preferences and gives you an actual answer.

## How to Document Your Audience

### Step 1: Interview real people

Not surveys. Actual conversations.

Find 3-5 people who represent your target audience. Ask them:
- What do you click on? What makes you bounce?
- What titles/topics turn you off?
- What's the difference between content you'd watch vs. just ask ChatGPT?
- What would make you NOT click something?
- What phrases or framings feel "not for me"?

### Step 2: Document everything

Create a file for each person:
```bash
cp _template.md [name].md
```

Fill in:
- Their situation (job, goals, relationship to your topic)
- What they would/wouldn't click
- Direct quotes from the interview
- Patterns you noticed

### Step 3: Use them as advisors

When creating content, tell Claude to check against your audience files:

"Would the people in `context/audience/` click this title?"

## Tips

- **Use real names (or pseudonyms).** "Derryn from Capital One" is more useful than "Persona A."
- **Include direct quotes.** Their exact words reveal how they think.
- **Document what they DON'T like.** Often more valuable than what they do like.
- **Update after new conversations.** Your understanding sharpens over time.

## Example

See `_example-audience.md` for a complete example.
