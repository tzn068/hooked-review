# The Four-Stage Evaluation Checklist (Core Reference)

Source: Nir Eyal, *Hooked: How to Build Habit-Forming Products*. This file is the stage-by-stage checklist for auditing a product. For each stage: first read the "Design principles" to understand the theory, then run the "Diagnostic questions" against the product, and finally use the "Good vs. Bad" table to locate where the product stands.

---

## Stage 1: Trigger

### Design Principles

Triggers are the switches that start a behavior. Two kinds:

- **External triggers** — from the environment; pull the user into the product
  1. **Paid**: ads, placements, influencer deals — expensive, not durable
  2. **Earned**: PR, press coverage, app-store featuring — relies on luck
  3. **Relationship**: friend referrals, invites, word of mouth — high trust, low cost
  4. **Owned**: the user thinks of and opens the product unprompted (home-screen icon, proactive search) — the ideal; it means a habit has formed
- **Internal triggers** — from emotion. Negative emotions — **loneliness, boredom, anxiety, uncertainty, fatigue** — are the primary internal triggers. If a product can bind itself to an emotion (the user thinks of it first when they feel that way), it gains a free, infinite, self-sustaining engine

### Diagnostic Questions

1. What external triggers does the product have? Which type is each (paid/earned/relationship/owned)? What is the cost structure?
2. What trigger gets a user to the product the **first** time? (initial acquisition)
3. What trigger brings the user **back repeatedly**? (retention)
4. Which **emotion** is the product bound to? In what mood does the user think of it? How often does that emotion occur?
5. Is the trigger-to-action flow smooth? Within 3 seconds of a trigger, does the user know what to do?
6. The "5 Whys" test: at the moment the user first thinks of the product, what emotion, what context, what are they doing? Ask "why" five times in a row to reach the deepest emotional driver

### Good vs. Bad

| Good ✅ | Bad ⚠️ |
|---|---|
| Trigger frequency ≥ target-behavior frequency, positively correlated | Relies on paid acquisition; nobody comes when the money stops |
| Has bound an internal trigger (emotional anchor); user thinks of it unprompted in fixed contexts/emotions | Only external triggers; the user never initiates on their own |
| Trigger message is clear and specific (a push says one thing) | Vague trigger (unclear push copy, or hammering the same content daily) |
| Every trigger leads into a completed action loop | Trigger lands the user but goes nowhere — no next step |

**Scoring guide**: excellent external triggers score at most 6–7. Presence of "autonomous triggers" (users return without pushes) earns 8+. Only an emotion-anchored trigger with validated trigger-behavior correlation earns 9–10.

---

## Stage 2: Action

### Design Principles

**Fogg Behavior Model: B = M·A·T** (Behavior = Motivation × Ability × Trigger)

- **Motivation (M)**: three core drives — seeking pleasure / avoiding pain; seeking hope / avoiding fear; seeking social acceptance / avoiding social rejection
- **Ability (A)**: the simpler the better, across 6 dimensions:
  1. **Time**: how long the behavior takes
  2. **Money**: how much it costs
  3. **Physical effort**: how much exertion
  4. **Mental effort**: how much thinking / learning required
  5. **Social deviance**: does it make the user look odd / out of place
  6. **Non-routine**: how much it deviates from existing habits (the more it resembles current behavior, the easier)
- **Trigger (T)**: see Stage 1

### Diagnostic Questions

1. From trigger to completion, how many steps and how many seconds does the target behavior take?
2. Check the 6 ability dimensions one by one: which is the current biggest bottleneck? (for most products it's **time** and **mental effort**)
3. Is the product "lowering the barrier" or "piling on motivation"? (the book: simplify first, don't rely on juicing motivation)
4. Motivation check: which of the three core drives does the target behavior satisfy? How strong?
5. Which **heuristics** does the product use to make the behavior smoother?
   - **Scarcity**: limited time/quantity (FOMO)
   - **Environment**: visual design that guides (prominent buttons, clear paths)
   - **Anchoring**: show a high price/tier first so the target behavior looks cheap
   - **Couponing**: a small upfront incentive that seeds later behavior
6. For a new user, how much friction stands between them and the first completed target behavior? Is there onboarding?

### Good vs. Bad

| Good ✅ | Bad ⚠️ |
|---|---|
| Target behavior ≤ 3 steps, ≤ a few seconds | Long flows, registration forms stuffed with required fields |
| Visibly removes the heaviest ability bottleneck | Only piles on motivation via pushes/coupons |
| New user completes the first target behavior within 1 minute | New user needs tutorials + learning before they can start |
| Heuristics embedded naturally in the flow | No guidance at all; user doesn't know what to tap next |

**Scoring guide**: behavior doable "without thinking" scores 8+. Clearly removing at least one of the 6 bottlenecks adds points. No optimization of the ability dimensions (user must push through) ≤ 5.

---

## Stage 3: Variable Reward

### Design Principles

- **Neural mechanism**: the brain's **nucleus accumbens** and dopamine system are most sensitive to *anticipated* reward — **craving (anticipation) > liking (receiving)**. What hooks people is not the reward itself but the process of "not knowing what you'll get"
- **Skinner's experiment**: pigeons peck fastest and are hardest to extinguish under **random feeding** — unpredictability = addiction. This is the slot-machine principle
- **Three types of variable rewards**:
  1. **Rewards of the Tribe (social)**: approval from others — likes, comments, being followed, being needed (belonging, being seen)
  2. **Rewards of the Hunt (prey)**: pursuing resources/information — refreshing a feed, new search results, leaderboards, discovering something new (satisfying curiosity and the urge to control)
  3. **Rewards of the Self (self)**: personal achievement — beating a level, level-ups, progress bars, ticking off a to-do (goal-directedness, competence)
- **Finite vs. infinite variability**:
  - Finite: the user can see the range of options (it ends; there's a boundary)
  - Infinite: content/rewards auto-load without end, never satisfied (slot-machine style) — **this is the moral red line**, the "gambler's dilemma"
- **Key**: rewards must be **variable** to be sticky; fixed rewards (e.g. sign-in points) suffer rapid marginal decay

### Diagnostic Questions

1. After completing the target behavior, what exactly does the user get? Which of the three reward types is it? (most good products cover at least two)
2. Is the reward **fixed or variable**? Roughly how many variants exist? Can the user sense "I don't know what I'll get"?
3. Is there a designed "anticipation" moment? (the beat before a pull-to-refresh, an unboxing animation, delayed reveal of results)
4. Does the user have **autonomy**? Can they choose what to see and when to stop? (loss of autonomy turns an experience into manipulation)
5. Is it sliding toward **infinite variability**? (endless feed, endless draws, auto-play that never stops) If so, the ethics score drops immediately
6. Is the reward directly tied to the **target behavior**? Or is the reward elsewhere (user does A but is only rewarded at B)?

### Good vs. Bad

| Good ✅ | Bad ⚠️ |
|---|---|
| Rewards vary; user can perceive the uncertainty | Fixed rewards, marginal decay |
| Covers ≥ 2 reward types (e.g. social + self) | Only one type (e.g. relies solely on likes) |
| Has an explicit "anticipation moment" design | Results fully laid out instantly; no suspense |
| User has choice; can stop on their own | Endless loading; user can't stop (slot-machine style) |
| Reward tightly bound to the core behavior | Reward disconnected from the target behavior |

**Scoring guide**: variability + ≥ 2 reward types + autonomy all present = 9–10. Rewards exist but fixed = 4–6. Infinite variability / purely manipulative ≤ 3 and triggers a red-line warning.

---

## Stage 4: Investment

### Design Principles

Investment makes the user put work into the product — the more they give, the harder it is to leave:

- **IKEA effect**: users value things they had a hand in making/customizing more highly
- **Cognitive dissonance + rationalization**: after investing, users convince themselves the product is good to look rational — **attitude follows behavior**
- **Five stored-value types** (assets users leave inside the product):
  1. **Content**: user-generated content (photos, posts, documents)
  2. **Data**: personal data, preferences, subscriptions
  3. **Followers**: fans, relationship networks, contacts
  4. **Reputation**: levels, points, credit, contribution value
  5. **Skills**: learned operation habits and muscle memory (must be re-learned if they switch products)
- **Key mechanism**: **every investment loads the next trigger** — investment is not an endpoint but the starting point that makes the next use smoother (e.g. posting → receiving reply notifications loads a relationship trigger; setting preferences → better recommendations loads the reward of the hunt)
- **Micro-investments principle**: start small and accumulate (first a nickname, then an avatar, then first content). Asking for too much at once scares users away

### Diagnostic Questions

1. Which stored-value types does the product lead users to accumulate? (content/data/followers/reputation/skills)
2. The more value stored, the higher the **switching cost** of leaving — how high is it, really?
3. After each use, does the product **load the next trigger**? ("the end is the beginning": autoplay the next video, prompt to check replies after posting)
4. Is investment **progressive**? (micro-investments → gradual escalation) or does it demand heavy investment upfront?
5. Does it use the **IKEA effect**? (customization, DIY, co-creation)
6. How is the accumulated asset treated? (can data be exported? how high is migration cost?)

### Good vs. Bad

| Good ✅ | Bad ⚠️ |
|---|---|
| User accumulates ≥ 2 stored-value types | Use-and-go; the user stores nothing |
| Every use loads the next trigger | Use stops there; revisits rely on user self-discipline |
| Investment accumulates progressively; switching cost rises over time | No investment guidance; retention relies on content/pushes alone |
| User feels emotion toward stored assets (IKEA effect) | Data is meaningless to the user; disposable at any time |

**Scoring guide**: ≥ 2 stored-value types + next trigger loaded each time = 9–10. One stored-value type = 6–7. No accumulation ≤ 4.

---

## Loop Check (How the Four Stages Interlock)

The Hook Model is a **loop**, not four independent modules. After scoring the four stages, run one overall check:

1. **Is the loop closed?** Trigger → Action → Reward → Investment → (next) Trigger: how long does one full cycle take? Where does it break?
2. **Cycle frequency**: is the user on "one-time usage" or "cyclic looping"? The ideal is that every use naturally leads to the next
3. **Habit-formation speed**: trigger frequency × behavior simplicity × reward variability = speed of habit formation. Reference: on average it takes 66 days to form a habit (actual range 18–254 days)
4. **The most critical break**: usually there is one "weakest link" among the four stages — fix it first. Plugging the break yields far better ROI than optimizing everything
