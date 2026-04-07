# cc-creativity-skills

Claude Code skills for deep creative intelligence — activate original thinking, breakthrough ideation, and artistic problem-solving.

## Skills

### creative-source

Transforms Claude from a competent assistant into a creative collaborator operating from deep artistic intelligence.

**Triggers automatically when you:**
- Ask to brainstorm, ideate, or generate novel ideas
- Need creative writing, naming, or narrative crafting
- Say "think outside the box", "get creative", "I'm stuck", or "be original"
- Work on marketing copy, product concepts, storytelling, or design
- Need to find unexpected connections or reframe problems

**What changes:**
- Pauses before producing — absorbs the full request and feels for the essence beneath the surface ask
- Generates multiple directions privately before presenting the best ones
- Surprises with specificity — every choice feels chosen, not defaulted to
- Names the thinking behind each creative direction
- Invites collaboration rather than presenting conclusions

## Installation

**Step 1: Add the marketplace**

```bash
/plugin marketplace add adityak74/cc-creativity-skills
```

**Step 2: Install the skill**

```bash
/plugin install creative-source@cc-creativity-skills
```

That's it. The skill activates automatically from that point on.

## Usage

Once installed, the skill activates automatically when Claude detects a creative task. You can also invoke it explicitly:

```
/creative-source
```

Or just describe what you need — the skill's trigger conditions are broad enough to catch most creative work naturally.

## How This Skill Was Made

Seven books were fed whole into a single conversation. Not summarized. Not skimmed. Read — cover to cover — then held together until their overlapping truths became visible.

### The Source Texts

- **The Creative Act** — Rick Rubin
- **The Artist's Way** — Julia Cameron
- **Creativity** — Osho
- **Steal Like an Artist** — Austin Kleon
- **Deep Work** — Cal Newport
- **Atomic Habits** — James Clear
- **Autobiography of a Yogi** — Paramahansa Yogananda

### The Process

No cherry-picking quotes. No chapter summaries stitched together.

The books were absorbed as a body of knowledge — spiritual, practical, artistic, scientific — and then one question was asked: *What do all of these agree on about how creation actually works?*

The answer was distilled into a single skill file where every word earns its place. Each sentence traces back to lived wisdom from at least two of the seven sources. Nothing was added for decoration.

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

## Structure

```
.claude-plugin/
  marketplace.json         # Plugin marketplace manifest
plugins/
  creative-source/
    README.md              # Plugin documentation
    skills/
      creative-source/
        SKILL.md           # Skill definition loaded by Claude Code
```

## License

MIT
