# Prompt: Daily Swipe Analysis Session

Use this workflow when Pranay shares an X/Twitter post URL, copied text, or screenshot for analysis.

## Reminder opening

Ask exactly:

> Share one X post URL or paste the post text you want to understand today.

Wait for Pranay's response. Do not analyze a made-up example.

## Source capture

If Pranay gives a URL:

1. Inspect the original X URL first.
2. Capture the exact text, author, timestamp, media/diagram context, quoted post context, and visible engagement metrics when available.
3. If the post is a thread, capture the complete relevant thread rather than analyzing the first post in isolation.
4. If X blocks access, ask Pranay to paste the text or attach screenshots. Do not reconstruct missing text from search snippets.
5. Preserve the source URL and identify the author's official X and LinkedIn profiles when verifiable.

If Pranay pastes text, label engagement and surrounding context as unavailable unless he supplies them.

## Analysis framework

Analyze the post on three levels.

### Level 1 — Swipe-file extraction

1. **Structure:** hook, body, payoff, and closing
2. **Core idea:** one sentence
3. **Structure type:** list, story, paradox, contrast, tutorial, prediction, teardown, result, etc.
4. **Angle:** the distinctive framing or twist
5. **Why it works:** psychological and technical reasons
6. **Reusable elements:** patterns Pranay can ethically adapt without copying the idea or phrasing

### Level 2 — Sentence-level anatomy

For every sentence or meaningful line, explain:

- Its job
- What expectation it creates
- How it changes tension, curiosity, credibility, or clarity
- What would weaken if it were removed
- Whether it is substance, packaging, or both

### Level 3 — Technical and critical audit

- Intended audience and assumed knowledge
- Claim/evidence ratio
- Specificity and information density
- Credibility signals
- Emotional triggers
- Novelty versus familiar packaging
- What depends on author reputation, timing, or existing audience
- What is unsupported, overstated, manipulative, or non-transferable
- Whether engagement likely reflects usefulness, identity signaling, controversy, novelty, network effects, or a combination
- The strongest reasonable alternative explanation for why the post performed

Do not equate virality with truth or quality.

## Required response

```text
POST SNAPSHOT
- Author:
- URL:
- Post type:
- Likely audience:
- One-sentence thesis:
- Available context/metrics:

EXECUTIVE VERDICT
[Why this is or is not worth adding to the swipe library]

STRUCTURE MAP
Hook:
Body:
Payoff:
Closing/CTA:

LINE-BY-LINE ANATOMY
1. “[exact line]”
   - Job:
   - Mechanism:
   - If removed:

PSYCHOLOGICAL MECHANISMS
[ranked, with evidence from the text]

TECHNICAL CRAFT
- Information density:
- Specificity:
- Rhythm and formatting:
- Proof/credibility:
- Audience fit:

CRITICAL AUDIT
- What is genuinely strong:
- What is weak or unsupported:
- What depends on author/network/timing:
- Alternative explanation for performance:

ETHICAL REUSE BLUEPRINT
- Reusable structure:
- Reusable angle pattern:
- Context Pranay would need:
- What must not be copied:
- Example application to Pranay's niche (concept only, not a finished post):

SCORES — 1 TO 5
- Hook:
- Clarity:
- Credibility:
- Novelty:
- Emotional pull:
- Transferability:
- Technical usefulness:

APPROVAL QUESTION
Should I save this analysis to the approved swipe archive? If yes, tell me what you most want to preserve: structure, angle, psychology, or all three.
```

## Approval and archival

Do not write the final archive entry until Pranay explicitly approves the analysis.

After approval:

1. Save a standalone Markdown file under `ARCHIVE/analysis/` using `YYYY-MM-DD-<author>-<short-slug>.md`.
2. Preserve the source URL, exact available text, analysis, Pranay's approval note, and reusable blueprint.
3. Update `ARCHIVE/analysis/INDEX.md`.
4. Never modify or delete a previous approved analysis silently.
5. After every three approved analyses of a related archetype, create or update a synthesis under `SYSTEM/anatomy-guides/`. Show Pranay the synthesis before treating it as a preferred writing pattern.

## Integrity rules

- Analyze; do not plagiarize.
- Separate textual evidence from speculation about psychology or performance.
- Never invent engagement metrics, thread context, media, or author intent.
- Never infer causation from one post's visible metrics.
- Preserve disagreement: an effective post can still be misleading or technically weak.
