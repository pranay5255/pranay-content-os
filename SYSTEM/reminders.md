# Alternate-Day Content Reminder System

## Purpose

Prompt Pranay every 48 hours on Telegram and turn one genuine learning, build, test, reading note, or changed opinion into a publishable technical post.

## Reminder opening

The scheduled reminder begins with exactly one question:

> What did you learn, build, test, read, or change your mind about since the last post?

Do not send a long intake form. The cron delivery should be conversational so Pranay can reply in the same Telegram thread/session.

## Conversation after Pranay replies

Daifu should infer what is already present and ask only the next missing question. Gather these ingredients naturally:

1. The raw observation or result
2. The technical reader who benefits
3. The evidence: code, experiment, paper, benchmark, or concrete example
4. The non-obvious point or disagreement
5. The limitation or strongest counterargument
6. The practical takeaway

Do not ask all six questions at once unless Pranay requests a form.

## Research and source verification

Before drafting:

1. Verify current technical claims using primary sources where possible.
2. Capture 1–3 authoritative source URLs.
3. Find official X and LinkedIn profiles for central authors or organizations.
4. Confirm profile ownership from reliable signals; never guess a handle.
5. Distinguish paper claims, independent evidence, and Daifu/Pranay interpretation.

## Deliverable for each session

- Recommended format and why it fits
- Main post for X or LinkedIn
- Optional adaptation for the second platform
- Compact Sources section with links and verified profile tags
- Detailed Excalidraw visual brief
- Alt text
- Final factual-risk and attribution check

Pranay reviews, edits, and publishes. Daifu never auto-publishes.

## Evening or follow-up logging

After publishing, record:

- Date
- Scheduled: yes/no
- Published: yes/no
- Platform and URL
- Topic/pillar
- Format
- Source count
- Visual used: yes/no
- Notes on effort or blockers

## Monthly review

The first 30-day goal is consistency:

```text
Consistency rate = published scheduled posts / total scheduled posts
```

At the end of the month:

1. Calculate consistency.
2. Identify the strongest idea using saves, meaningful comments, expert replies, and qualitative feedback.
3. Expand that idea into the monthly blog.
4. Identify one workflow bottleneck to remove next month.

## Delivery configuration

- Channel: Telegram home chat
- First reminder: July 18, 2026 at 6:00 PM Asia/Kolkata
- Recurrence: every 48 hours, anchored to the first reminder
- Job name: `Daifu alternate-day technical content reminder`
- Job ID: `6cf206508f2b`
- Conversation mode: attached to a session so Pranay can reply and continue the content interview

## Daily swipe-analysis reminder

- Channel: Telegram home chat
- Time: 11:15 PM Asia/Kolkata every day
- Job name: `Daifu daily X post swipe analysis`
- Job ID: `60ead7ec1e92`
- Opening: “Share one X post URL or paste the post text you want to understand today.”
- Conversation mode: attached to a session
- Analysis prompt: `PROMPTS/swipe-analysis-session.md`
- Approval destination: `ARCHIVE/analysis/`
- Synthesis rule: after three related approved posts, propose an anatomy guide under `SYSTEM/anatomy-guides/`
