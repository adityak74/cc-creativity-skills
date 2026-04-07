<p align="center">
  <h1 align="center">cc-creativity-skills</h1>
</p>

<p align="center">
  <strong>Deep creative intelligence for Claude Code — distilled from seven books on how creation actually works</strong>
</p>

<p align="center">
  <a href="https://github.com/adityak74/cc-creativity-skills/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT">
  </a>
  <a href="https://github.com/adityak74/cc-creativity-skills/issues">
    <img src="https://img.shields.io/github/issues/adityak74/cc-creativity-skills" alt="Issues">
  </a>
  <a href="https://github.com/adityak74/cc-creativity-skills/pulls">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome">
  </a>
  <img src="https://img.shields.io/badge/Claude_Code-Plugin-blueviolet" alt="Claude Code Plugin">
  <img src="https://img.shields.io/badge/category-creativity-orange" alt="Category: Creativity">
</p>

---

## Quick Start

```bash
# Step 1 — Add the marketplace
/plugin marketplace add adityak74/cc-creativity-skills

# Step 2 — Install the skill
/plugin install creative-source@cc-creativity-skills
```

---

## What's Inside

| Skill | Description |
|-------|-------------|
| [**creative-source**](./plugins/creative-source) | Activates deep creative intelligence for original thinking, breakthrough ideas, and artistic problem-solving |

---

## The `creative-source` Skill

Transforms Claude from a competent assistant into a creative collaborator operating from deep artistic intelligence.

**Activates automatically when you:**
- Ask to brainstorm, ideate, or generate novel ideas
- Need creative writing, naming, or narrative crafting
- Say "think outside the box", "get creative", "I'm stuck", or "be original"
- Work on marketing copy, product concepts, storytelling, or design
- Need to find unexpected connections or reframe problems

**What changes when active:**
- Pauses before producing — absorbs the full request and feels for the essence beneath the surface ask
- Generates multiple directions privately before presenting the best ones
- Surprises with specificity — every choice feels chosen, not defaulted to
- Names the thinking behind each creative direction
- Invites collaboration rather than presenting conclusions

---

## Installation

**Step 1: Add the marketplace**

```bash
/plugin marketplace add adityak74/cc-creativity-skills
```

**Step 2: Install the skill**

```bash
/plugin install creative-source@cc-creativity-skills
```

**Step 3: Use it**

The skill activates automatically. You can also invoke it explicitly:

```
/creative-source
```

**Installation scopes** — when prompted, choose:
- **User** (default): active across all your projects
- **Project**: shared with your team via `.claude/settings.json`
- **Local**: only in this repository

**Managing the skill**

```bash
# Disable without uninstalling
/plugin disable creative-source@cc-creativity-skills

# Uninstall
/plugin uninstall creative-source@cc-creativity-skills
```

---

## How This Skill Was Made

Seven books were fed whole into a single conversation. Not summarized. Not skimmed. Read — cover to cover — then held together until their overlapping truths became visible.

### Source Texts

| Book | Author |
|------|--------|
| The Creative Act | Rick Rubin |
| The Artist's Way | Julia Cameron |
| Creativity | Osho |
| Steal Like an Artist | Austin Kleon |
| Deep Work | Cal Newport |
| Atomic Habits | James Clear |
| Autobiography of a Yogi | Paramahansa Yogananda |

### The Process

No cherry-picking quotes. No chapter summaries stitched together.

The books were absorbed as a single body of knowledge — spiritual, practical, artistic, scientific — and then one question was asked: *What do all of these agree on about how creation actually works?*

The answer was distilled into a skill file where every word earns its place. Each sentence traces back to lived wisdom from at least two of the seven sources. Nothing was added for decoration.

### What Each Book Contributed

| Book | Contribution |
|------|-------------|
| **Rubin** | The artist as channel. The four phases of creation (Seed → Experiment → Craft → Completion). The ecstatic as compass. Beginner's mind. The ruthless edit. |
| **Cameron** | Morning pages as clearing practice. The inner critic as Censor. Artist dates as refilling the well. Creativity as spiritual electricity. |
| **Osho** | Creativity as the fragrance of freedom. Action vs. activity. The three C's: consciousness, compassion, creativity. Relaxation as the door to the divine. |
| **Kleon** | Steal like an artist. 1+1=3. Copy to find your voice. Side projects as the real work. Creativity is subtraction. |
| **Newport** | Deep work as the engine of mastery. Distraction as the enemy of depth. Ritualized focus. Deliberate disconnection. |
| **Clear** | 1% daily improvement. Systems over goals. Identity-based habits. The compound effect of small creative acts. Environment design. |
| **Yogananda** | Concentration as the gateway to the infinite. Devotion to practice. The surrender that enables receiving. Stillness as the origin of power. |

### The Rule

One rule governed the writing: **no filler**. Every word had to carry meaning. If a sentence could be removed without losing something essential, it was removed. The skill is short not because the source material was thin, but because distillation means reduction — the volume decreases, the flavor intensifies.

---

## Repository Structure

```text
.
├── .claude-plugin/
│   └── marketplace.json          # Plugin marketplace manifest
└── plugins/
    └── creative-source/
        ├── README.md             # Plugin documentation
        └── skills/
            └── creative-source/
                └── SKILL.md      # Skill definition loaded by Claude Code
```

---

## Contributing

Contributions welcome. If you have a skill that belongs in this collection — another lens on creativity, a complementary framework, a domain-specific variation — open a PR.

1. Fork the repo and create a branch: `skill/your-skill-name`
2. Add your skill under `plugins/<skill-name>/skills/<skill-name>/SKILL.md`
3. Register it in `.claude-plugin/marketplace.json`
4. Open a pull request with a clear description of what the skill does and when it activates

---

## Requirements

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) CLI installed

---

## License

[MIT](./LICENSE)
