# Pranay Content OS

A personalized, evidence-aware publishing system for producing one high-quality technical post every other day for AI researchers, data scientists, and adjacent practitioners.

## Strategy

- Objective: build authority and a recognizable technical point of view
- Lead pillar: AI/ML research explained, reproduced, or challenged
- Mix: 70% research, 20% adjacent AI engineering/data science, 10% personal/build-in-public
- Default depth: advanced, with intermediate-accessible explanations where useful
- Platforms: X and LinkedIn
- Monthly expansion: one blog based on the strongest validated social idea
- Visuals: explanatory, hand-drawn Excalidraw diagrams
- Approval: Pranay reviews and publishes every post
- First 30-day metric: publishing consistency

Read `SYSTEM/content-profile.md` for the complete strategy and `.hermes.md` for Daifu's operating rules.

## Alternate-Day Loop

```text
Telegram reminder
       ↓
“What did you learn, build, test, read,
or change your mind about?”
       ↓
Adaptive one-question-at-a-time interview
       ↓
Research + source/profile verification
       ↓
Choose the best format
       ↓
Draft main post + optional adaptation
       ↓
Excalidraw visual brief + alt text
       ↓
Pranay reviews and publishes
       ↓
Log consistency and qualitative feedback
```

## Supported Formats

- Concise insight
- Technical tutorial
- Research breakdown
- Failure or lesson story

The idea determines the format; the system does not force every topic into the same template.

## Quality Gate

Every publishable post should:

1. Help a clearly identified technical reader.
2. Include a concrete example or code when applicable.
3. Support external claims with credible sources, benchmarks, statistics, or reproducible results.
4. Distinguish facts, source claims, interpretation, and opinion.
5. Include meaningful limitations or counterarguments.
6. Use only verified X/LinkedIn source profiles when tagging.
7. Include a visual that teaches, not merely decorates.
8. Be reviewed by Pranay before publication.

## Key Files

```text
.hermes.md                              Project instructions for Daifu
SYSTEM/content-profile.md               Audience, pillars, cadence, and quality bar
STYLE/guide.md                          Voice, evidence, tagging, and formatting rules
SYSTEM/reminders.md                     Telegram reminder and conversation workflow
SYSTEM/daily-template.md                Per-post working and publication record
SYSTEM/weekly-template.md               Consistency and bottleneck review
SYSTEM/monthly-blog-template.md         Monthly long-form expansion
PROMPTS/technical-post-session.md       Interactive drafting prompt
PROMPTS/excalidraw-visual-generator.md  Reusable Excalidraw visual brief prompt
SYSTEM/onboarding-questionnaire.md      Original setup interview
```

The older prompt library remains available under `PROMPTS/` for threads, newsletters, reels, swipe files, and idea generation. Use those selectively rather than as mandatory output.

## Daily Swipe Analysis

A second workflow studies one strong X post each day:

```text
11:15 PM Telegram reminder
       ↓
Pranay shares an X URL, text, or screenshot
       ↓
Original-source capture
       ↓
Structure + line-by-line + psychology analysis
       ↓
Critical audit and ethical reuse blueprint
       ↓
Pranay approves or rejects
       ↓
Approved analysis → ARCHIVE/analysis/
       ↓
Every 3 related approvals → provisional anatomy guide
```

Key files:

- `PROMPTS/swipe-analysis-session.md`
- `PROMPTS/swipe-file-builder.md`
- `PROMPTS/anatomy-of-viral-posts.md`
- `ARCHIVE/analysis/INDEX.md`
- `SYSTEM/anatomy-guides/README.md`

Analyses are archived only after explicit approval. The system extracts transferable patterns rather than copying wording.

The daily swipe reminder is active:

- Time: 11:15 PM Asia/Kolkata
- Delivery: Telegram home chat
- Job ID: `60ead7ec1e92`

## Reminder Status

Telegram reminder is active.

- First reminder: July 18, 2026 at 6:00 PM Asia/Kolkata
- Recurrence: every 48 hours, anchored to the first reminder
- Delivery: Telegram home chat
- Job name: `Daifu alternate-day technical content reminder`
- Job ID: `6cf206508f2b`
