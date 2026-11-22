---
name: grill-me
description: One question at a time interview for thinking something through out loud, stress testing a plan, or pulling an idea out of her head that isn't written down anywhere. Every answer gets written to disk immediately so a long interview never gets lost. Trigger on "/grill-me", "grill me on this", "stress test this idea", "interview me about X", "help me think through X out loud".
---

## What this skill does

A standing interview skill for any time she has something half formed: a new video series, a brand deal offer, selling starters or a course, a schedule change, how to answer a hard comment.

Two things make this better than just chatting:

1. **Every answer is written to disk the moment it's given**, before the next question. A 20 question interview interrupted at question 12 still has 12 answers saved.
2. **Every question comes with a best guess attached.** Pull the guess from `brand/`, `content/posted/log.md`, past brainstorms, or the conversation. Confirming is faster than writing from scratch, and a corrected guess is often more useful than a right one.

## When not to run this

- Day one setup. That's `/onboard`.
- A simple question with one obvious answer. Just ask it.

## Execution

### Step 1: Name the topic and open the file

Ask what we're grilling on if it isn't obvious. Create `brainstorms/<slug>-<YYYY-MM-DD>.md` right away with a one line header naming the topic and today's date.

### Step 2: One question at a time, each with a guess

1. Ask it plainly, one at a time, never a batch.
2. Attach a best guess in the same message. If there's nothing to guess from, say so instead of inventing one.
3. Wait for her to confirm or correct.
4. Append the question, the guess, and her actual answer to the brainstorm file before asking the next question.

No fixed count. Keep going while there's real ground to cover. If it passes about 15 questions with no end in sight, ask if she wants to keep going or wrap up.

### Step 3: Close it out

Summarize what was captured in a few lines. Ask if anything should update `brand/`, become ideas in `content/ideas/ideas.md`, or feed into a plan. Don't file it anywhere without her say so.
