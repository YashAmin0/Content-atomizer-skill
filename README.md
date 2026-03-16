# Content Atomizer Skill

A Claude Code skill that takes one piece of long-form content and rewrites it into 6 platform-native formats — built for creators and marketers who want maximum distribution from a single piece of content.

---

## What It Does

Give it a blog post, article, transcript, or podcast. It outputs 6 ready-to-post formats, each rewritten to match how that platform's audience reads, scrolls, and engages.

| Format | Goal | Length |
|---|---|---|
| LinkedIn Post | Comments, saves, shares | 150–300 words |
| Twitter/X Thread | Reach + follows | 8–12 tweets |
| Instagram Caption | Saves + shares | 100–150 words + hashtags |
| Email Newsletter Section | Clicks + replies | 200–350 words |
| YouTube Description | SEO discovery | 250–400 words |
| Short-Form Video Script | Views + follows | ~150 words (60 sec) |

Not copy-paste. Each format is rewritten with platform-specific structure, voice, and hooks.

---

## Installation

**Step 1 — Find your Claude skills directory:**

```
~/.claude/skills/
```

Create the folder if it doesn't exist.

**Step 2 — Copy the skill file:**

```bash
cp content-atomizer/SKILL.md ~/.claude/skills/content-atomizer.md
```

**Step 3 — Use it in Claude Code:**

```
/content-atomizer
```

---

## Usage

When you invoke the skill, Claude will ask for:

1. **The content** — paste your article, transcript, or outline
2. **Original goal** — what was this piece trying to communicate?
3. **Target audience** — who is it for?
4. **Platforms needed** — which of the 6 outputs do you want? (default: all)
5. **Brand voice** — tone guidelines, first-person vs third, formal vs casual
6. **One key insight** — the single most important takeaway

A rough outline is enough to start. Claude works with what's provided.

---

## Output Format

Each format is delivered as a labeled, ready-to-use block with:
- Format name and where to post it
- The full content
- A note on what makes this version work for that platform

---

## Core Principles

- **One insight, six angles** — find the sharpest insight and let each platform explore a different dimension of it
- **Platform-native means platform-specific** — a LinkedIn post that reads like a tweet will underperform
- **The hook changes, the truth doesn't** — core insight stays consistent; the angle shifts per platform
- **Hard editing** — every word earns its place
