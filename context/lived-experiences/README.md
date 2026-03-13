# Lived Experiences

Your daily journal of what you've learned, built, and discovered.

## Why This Matters

Every day, you learn things. You solve problems. You have insights. Then you forget them.

This folder captures everything so AI can reference it in future work.

- Writing an email? AI knows what worked last time.
- Solving a bug? AI remembers how you fixed similar issues.
- Creating content? AI can pull from YOUR real experiences, not generic advice.

## How to Use

**Daily (2-5 minutes):**

1. At end of day, create a new entry:
   ```bash
   cp _template.md $(date +%Y-%m-%d)-brief-description.md
   ```

2. Fill in:
   - What happened (the story)
   - Key learning (transferable insight)
   - Quotable moment (how you'd actually say it)

3. Save. Done.

**Voice memo method:**

1. Record a voice memo on your phone at end of day
2. Transcribe it (use your phone's transcription or an app)
3. Paste into a new entry, then clean up into the template format

## Entry Format

See `_template.md` for the structure.

Key sections:
- **What Happened** — Specific situation, be detailed
- **Key Learning** — Transferable insight others could use
- **Quotable** — Natural language you'd actually say
- **Tags** — For searchability

## Tips

- **Be specific.** "Had a good meeting" = useless. "Learned finance wants weekly reports because monthly is too slow for planning" = gold.
- **Include failures.** What went wrong is often more valuable than what went right.
- **Capture the emotion.** How did it feel? That context helps AI understand nuance.
- **Don't overthink it.** A rough entry is better than no entry.
