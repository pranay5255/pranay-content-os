# Content Operating System

> Based on Dan Koe's content system: **Twitter-first, AI-augmented, daily output.**

## The Core Principle

All content starts from a single source: **one tweet** (280 chars). That tweet becomes everything else.

```
Newsletter (1x/week)
        ↓
Tweet (2-3x/day) ← YOU WRITE THIS FIRST
        ↓
┌───────────────────────────────────────┐
│  Threads → Instagram → LinkedIn      │
│  Reels/TikToks (script from tweet)   │
└───────────────────────────────────────┘
```

## Daily Workflow

1. **Morning**: Open `DAILY/YYYY-MM-DD.md` — fill in 3 tweet ideas
2. **Use prompts**: Generate drafts in `CONTENT/drafts/`
3. **Edit & post**: Pick the best, polish, publish
4. **End of day**: Move drafts to `CONTENT/published/`
5. **Weekly**: Write newsletter from week's best tweets

## Directory Structure

```
pranay-content-os/
├── README.md              ← you are here
├── PROMPTS/               ← all AI prompts
│   ├── idea-generator.md
│   ├── tweet-writer.md
│   ├── thread-expander.md
│   ├── linkedin-transformer.md
│   ├── reel-script-writer.md
│   └── newsletter-writer.md
├── CONTENT/
│   ├── ideas/             ← raw ideas, sparks, screenshots
│   ├── drafts/            ← AI-generated, needs editing
│   └── published/         ← final polished posts
├── STYLE/
│   └── guide.md           ← your voice, themes, do's/don'ts
├── SYSTEM/
│   ├── daily-template.md  ← paste into new daily file
│   ├── weekly-template.md
│   └── reminders.md
└── DAILY/
    └── YYYY-MM-DD.md      ← one file per day, 3 slots
```

## The Repurposing Chain

| Platform | Input | Format |
|----------|-------|--------|
| Tweet | Your brain | 280 chars, punchy |
| Threads | Tweet | 5-10 slide thread |
| LinkedIn | Tweet | Image + caption |
| Instagram | Tweet | Image post or reel script |
| Reels/TikToks | Tweet | 60s script (read tweet + add 20%) |

## Key Rules from Dan Koe

- Write Twitter **first** — it's the limiting factor that sharpens everything
- 2-3 posts/day minimum
- 1 newsletter/week baseline
- Don't edit while generating — generate first, edit second
- Batch similar tasks
- Your voice > perfect voice — authenticity compounds

## Tools

Just Claude and ChatGPT. No fancy stack. The system is the advantage.
