---
name: onboard
description: Day one setup. Interviews the owner about her sourdough channel and fills in CLAUDE.md placeholders plus brand/brand.md, brand/voice.md and brand/pillars.md. Trigger on "/onboard", "set me up", "let's get started", or whenever CLAUDE.md still contains [YOUR NAME]. Safe to re-run any time to update the brand files.
---

## What this does

Runs a short interview, one question at a time, and writes the answers into the brand files so every other skill knows who she is and how she sounds.

## Rules

- One question per message. Always attach a best guess she can accept with "yes".
- Save each answer to `brainstorms/onboard-<YYYY-MM-DD>.md` the moment she gives it, before asking the next one.
- Keep it friendly and quick. About 10 questions. Skip any she already answered.

## Questions (adapt the wording, keep the order)

1. What's your first name, and your handle on TikTok and Instagram (or the one you want)?
2. Where are you with the channel today? (Brand new, posting a bit, already growing. Follower counts if you have them.)
3. Why sourdough, and why you? What's your story with it in two sentences?
4. Who do you picture watching? (Total beginners, home bakers leveling up, moms baking for family, people who just love watching bread.)
5. What's your angle, the thing that makes your channel yours? Offer 3 guesses based on answers so far.
6. Which 3 to 5 kinds of videos do you want to make over and over? Offer a starter list: bake with me, beginner mistakes, scoring and ASMR, recipes with discard, day in the life, Q&A from comments.
7. How do you talk on camera? Paste a caption or text you wrote, or describe it (bubbly, calm, funny, teachy). Any words you love or hate?
8. How often can you realistically film and post per week?
9. Goals for the next 90 days? (Followers, consistency, first brand deal, selling a starter or a course.)
10. Anything off limits? (Showing your face, your kids, your home, certain topics.)

## Writing the files

When done, write or update:

- `CLAUDE.md`: replace `[YOUR NAME]`, `[@YOUR_HANDLE]`, and the angle placeholder.
- `brand/brand.md`: story, audience, angle, where the channel is today, 90 day goals, posting capacity, off limits list.
- `brand/voice.md`: how she talks, words she uses, words she never uses, 2 or 3 real samples of her writing if she gave any.
- `brand/pillars.md`: each pillar with one line on what it is and two example video ideas.
- `content/ideas/ideas.md`: seed it with 10 ideas spread across the pillars.

Then show her a five line summary and suggest the next step: `/trend-scout`, then `/content-plan`.
