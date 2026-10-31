# 04 — Repeated Games, the Shadow of the Future, and How Forgiving Should You Be

## Why "play it once" logic breaks down when you repeat

If you know in advance you're playing Prisoner's Dilemma **exactly N times**
with the same person, logic says: still defect every time, even round 1.

Why: think about the very last round. There's no future round left to
protect, so it's just a one-shot game — defect wins. Now think about the
second-to-last round: both of you already know the last round will be
mutual defection no matter what, so there's no cooperation left to protect
by being nice now either. This logic "unravels" backward to round 1.
**Knowing exactly when a relationship ends kills cooperation.** (Backward
induction.)

## The shadow of the future (with real numbers)

Two business partners deal every week. Payoffs per round:

|                  | Cooperate     | Defect     |
|------------------|---------------|------------|
| **Cooperate**    | 3, 3          | 0, 5       |
| **Defect**       | 5, 0          | 1, 1       |

If the relationship is expected to continue indefinitely (no known end
date), compare two plans:

- **Keep cooperating:** 3 every round, forever.
- **Cheat once, relationship collapses to mutual defection after:** +2
  one-time bonus (5 instead of 3), but -2 every single round after that,
  forever.

One-time gain: **+2**. Ongoing loss: **-2 per round, every future round.**
The moment there's more than one expected future round, cheating is a bad
trade. This weight of expected future consequences on today's decision is
"the shadow of the future" — it's literal arithmetic, not a vibe. It's why
one-off deals invite cheating and long-term relationships don't.

## The strategy spectrum — and why "always forgive" is wrong

Tit-for-Tat (mirror their last move, forgive instantly if they return to
cooperating) is the famous answer here, but **it's not the universal right
answer.** There's a real spectrum:

| Strategy             | Rule                                              |
|-----------------------|----------------------------------------------------|
| Always Cooperate      | Never retaliate — gets exploited                   |
| Always Defect         | Never trust — safe, but zero cooperation gains      |
| Tit-for-Tat           | Mirror last move; retaliate but forgive instantly   |
| Tit-for-Two-Tats      | Only retaliate after *two* defections in a row      |
| Grim Trigger          | Cooperate until the first defection, then defect **forever**, no matter what |

**Grim Trigger is not a worse idea than Tit-for-Tat** — in the formal
theory of sustaining cooperation in repeated games (the Folk Theorem),
Grim Trigger is actually the *strongest possible deterrent*, because the
threat (permanent cutoff) is maximally scary. "Cut them off forever the
moment they cheat" is a fully rational, legitimate strategy — not a
mistake.

### So which one should you actually use?

It comes down to one question: **how sure are you that what you saw was
real betrayal, versus a mistake or miscommunication?**

- **Clear, unambiguous betrayal** (partner provably stole funds, obvious
  intentional fraud) → use **Grim Trigger**. Cut it off permanently.
  Forgiving a proven cheater just invites a repeat.
- **Ambiguous or noisy signal** (a late shipment, a missed call, something
  that could plausibly be an honest mistake rather than intentional
  cheating) → full Grim Trigger is dangerous, because one honest mistake
  (by either side) permanently destroys an otherwise fine relationship.
  This is where **Tit-for-Tat** (or Tit-for-Two-Tats, which tolerates one
  slip-up) earns its keep — punish immediately so cheating isn't free, but
  don't hold a permanent grudge over something that might not have even
  been real betrayal.

**The actual takeaway:** the right amount of forgiveness is a dial, not a
fixed rule — set it based on (1) how reliable your evidence of cheating is,
and (2) how costly a false accusation would be to a relationship that was
actually worth keeping.

## Where this shows up in real life

- Business partnerships: hard evidence of fraud → cut ties for good; a
  missed deadline with a reasonable excuse → don't torch the relationship
- Reputation/review systems (eBay, Uber, credit scores) — mechanisms that
  make the "shadow of the future" visible and real, so cheating has lasting
  consequences
- International trade/diplomacy — why clear treaty violations get harsh,
  lasting sanctions, but ambiguous incidents get smaller, reversible
  responses
- Personal relationships — why a single clear betrayal (e.g. proven
  infidelity) often ends things for good, while an honest misunderstanding
  usually doesn't
