---
name: hooked-review-en
description: Evaluate a product's "addictiveness", retention mechanics, habit-formation design, and behavior design using the Hook Model from Nir Eyal's book "Hooked". Use when the user asks to review/judge/diagnose whether a product is addictive or habit-forming, analyze retention mechanisms, analyze a competitor's hooks, audit their own product's habit loop, or review a product document/PRD against behavior-design standards. Input can be a product description, PRD, competitive analysis material, or any product/App/feature. Output is a structured habit-formation review report (four-stage scores + diagnosis + ethics positioning + prioritized improvement list).
agent_created: true
---

# Hooked Review — Product Addiction Audit

A systematic "addictiveness" audit of any product using the **Hook Model** from Nir Eyal's *Hooked: How to Build Habit-Forming Products*. Applicable to: apps, websites, hardware interactions, AI products, games, content products — anything whose goal is to build user habits.

## When to Use

- The user asks to evaluate/diagnose whether a product is "addictive" or whether its retention mechanics work
- The user asks to analyze a product through the Hook Model / behavior-design frameworks
- The user wants a competitor hook analysis (deconstruct a rival's triggers, rewards, and investment design)
- The user is designing their own product and wants to self-audit the habit loop before launch
- The user provides a product document/PRD and wants it reviewed against behavior-design standards

## Review Process

### Step 1: Gather Product Information

Build a product profile before judging. If information is insufficient, ask only the minimum follow-ups needed (at most 3 questions per round):

1. **Target users** — who are they?
2. **Core behavior** — the one action the user should repeat. What is the target frequency?
3. **Usage context** — when/where/in what emotional state does the user use it?
4. **Existing data** (if any): DAU, retention, time per session, revisit interval

If the user only names a product with no details, start with a preliminary review based on public knowledge, and explicitly mark which judgments are assumptions.

### Step 2: Define the "Target Behavior"

Lock in the core behavior the Hook Model must drive before judging. Write it in one sentence: **A user (who) performs (what action) under (what trigger)**. All later stages revolve around this target behavior.

### Step 3: Evaluate Stage by Stage (Core)

Load `references/hook-model.md` and check each of the four stages — **Trigger → Action → Variable Reward → Investment**. For every stage you must output:

- **Score**: 1–10 (10 = textbook design, 1 = completely absent)
- **Evidence**: concrete design elements in the product for this stage (state what exists; note what is missing)
- **Problems**: weaknesses / risks in this stage
- **Recommendations**: concrete, actionable improvements (not vague advice)

Core principles from the book to apply while judging:

- **Trigger**: Check whether the product stays at "external triggers" or has evolved an "internal trigger" (emotional anchoring). Autonomous triggers (the user thinks of the product unprompted) are where habit begins; internal triggers cannot be designed directly — they are cultivated indirectly by binding the product to an emotion
- **Action**: B = M·A·T — the three factors multiply; if any is zero, the behavior doesn't happen. Rather than working hard to raise motivation, first lower the ability barrier (time / money / physical effort / mental effort / social deviance / non-routine — 6 dimensions)
- **Reward**: Distinguish "craving" from "liking" — dopamine peaks during anticipation, so rewards must be **variable** to be sticky. Check whether all three reward types (social / prey / self) are present, whether they vary, and whether the user keeps autonomy
- **Investment**: The value users are led to store (content / data / followers / reputation / skills) is their switching cost — and the source of the next trigger. Check whether small investments accumulate progressively

### Step 4: Ethics Assessment

Load `references/ethics.md`, place the product in the morality-of-manipulation 2×2 (Facilitator / Peddler / Entertainer / Dealer), and run the book's "self-test". **Red lines** (infinite variability, manipulative design, engineered dependence) — if touched, must trigger a prominent warning in the report and the overall rating is downgraded.

### Step 5: Output the Review Report

Use the fixed template below so every review has the same shape and is comparable across products:

```
# Hooked Review: <Product Name>

## 1. Product & Target Behavior
Target users / core behavior / usage context / current data (if any)

## 2. Four-Stage Score Overview
| Stage | Score | One-line verdict |

## 3. Stage-by-Stage Diagnosis
### Trigger — x/10
✅ Strengths / ⚠️ Issues / 💡 Recommendations
### Action — x/10
(same)
### Variable Reward — x/10
(same)
### Investment — x/10
(same)

## 4. Ethics Positioning
Quadrant + self-test results + red-line warnings (if any)

## 5. Overall Rating
Habit strength rating: within habit zone / forming / not forming + one-line verdict

## 6. Prioritized Action List
P0 (do now, make-or-break) / P1 (soon, meaningful lift) / P2 (later, if opportunity arises)
```

### Step 6: Give the Verdict

Close the report with 2–3 sentences: Is the product's "habit loop" closed? What is the single most critical gap? What is the single highest-leverage improvement?

## Quick Reference for Judging

- **Loop completeness**: if one of the four stages is missing, the habit breaks. Finding the "broken link" matters more than scoring every stage
- **Strength**: trigger frequency × behavior simplicity × reward variability determines habit-formation speed; habitual users' lifetime value (LTV) far exceeds new users'
- **Ethics first**: even with all four stages intact, if the product sits in the "Dealer" quadrant (engineers dependence, user unaware and harmed), the verdict must be negative
- **Cite sources**: all judgments rest on concepts from *Hooked* (Hook Model, Fogg Behavior Model, three variable-reward types, five stored-value types, the morality-of-manipulation quadrants). Use these terms in the report so the user knows where the basis comes from
