# Hooked Review — Product Addiction Audit Skill

A WorkBuddy/Claude-style agent skill that audits any product's "addictiveness" using the **Hook Model** from Nir Eyal's *Hooked: How to Build Habit-Forming Products*.

Built from the book itself: the four-stage Hook Model (Trigger → Action → Variable Reward → Investment), the Fogg Behavior Model (B = M·A·T), the three variable-reward types, the five stored-value types, and the morality-of-manipulation 2×2.

## What It Does

Given a product (name, PRD, or competitive material), the skill produces a **structured habit-formation review report**:

1. **Product & target behavior** — who the user is, what action to drive, in what context
2. **Four-stage score overview** — Trigger / Action / Variable Reward / Investment, each scored 1–10
3. **Stage-by-stage diagnosis** — evidence, problems, and concrete recommendations per stage
4. **Ethics positioning** — Facilitator / Peddler / Entertainer / Dealer + the book's self-test + red-line warnings
5. **Overall rating** — habit strength verdict in one line
6. **Prioritized action list** — P0 / P1 / P2 improvements

## Structure

```
hooked-review/
├── SKILL.md                    # 6-step review process + fixed report template
└── references/
    ├── hook-model.md           # Stage-by-stage checklist: diagnostic questions + good-vs-bad tables + scoring guides
    └── ethics.md               # Morality-of-manipulation 2×2 + self-test + red-line warnings + AI-companion notes
```

## Installation

### WorkBuddy (recommended)

The skill is distributed as `hooked-review-en.zip`. Install it to your user skills directory:

```bash
# macOS / Linux
unzip hooked-review-en.zip -d ~/.workbuddy/skills/
```

Then in any conversation just ask:

- "Run a Hooked review on <product>"
- "Is <product> addictive? Audit its habit loop"
- "Analyze <competitor>'s hooks"
- "Self-audit my product with the Hook Model"

### Claude Code / other Claude-based agents

Copy the `hooked-review-en/` folder into your agent's skills directory (e.g. `~/.claude/skills/`), keeping `SKILL.md` at the top level.

## Requirements

- Any agent that supports the Anthropic Skills format (SKILL.md + references/)
- No external APIs, no network calls — the audit runs entirely on the model's reasoning + the checklists in `references/`

## Credits

Framework and concepts from *Hooked: How to Build Habit-Forming Products* by Nir Eyal with Ryan Hoover (2014). This skill is an independent evaluation tool built from the book's public concepts.

## License

MIT — see [LICENSE](LICENSE).
