---
name: captions
description: Write the caption, hashtags, and on screen text for a TikTok or Instagram video in her voice, with versions for each platform. Trigger on "/captions", "write a caption", "hashtags for this", "caption this video".
---

## Steps

1. Read `brand/voice.md`. If there's a script in `content/scripts/` for this video, read it.
2. Ask for anything missing in one line with a guess (what the video shows, the goal: follows, saves, comments).
3. Write:
   - **TikTok caption**: 1 to 2 short lines, searchable words people actually type ("sourdough for beginners", "sourdough discard recipe"), 3 to 5 hashtags.
   - **Instagram caption**: first line works as a hook before "more", then 2 to 5 short lines of value (the recipe, the tip, the story), a question or save prompt, then 5 to 10 hashtags mixing big and niche.
   - **On screen text**: the hook plus any step labels, short enough to read in 2 seconds.
   - **Alt text** for Instagram: one plain sentence describing the video.
4. Hashtags: mix broad (#sourdough, #breadtok) with specific (#sourdoughdiscard, #sourdoughforbeginners) and any trend tag that genuinely fits. No banned or spammy tags.
5. Run the humanizer rules over it before showing her.

## Rules

- Sounds like her, not a brand. No "elevate your bake", no "game changer", no emoji walls (a couple is fine if her voice file says she uses them).
- Recipes in captions get exact amounts and units she confirmed. Never guess a recipe.
