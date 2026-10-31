# 03 — Mixed Strategies & Matching Pennies

## The game

Two players, A and B, each secretly pick **Heads** or **Tails**, reveal at
the same time.

- Match (both H or both T) → A wins B's penny
- Mismatch → B wins A's penny

Payoffs (+1 = win a penny, -1 = lose one):

|                 | B: Heads     | B: Tails     |
|-----------------|--------------|--------------|
| **A: Heads**    | A: +1, B: -1 | A: -1, B: +1 |
| **A: Tails**    | A: -1, B: +1 | A: +1, B: -1 |

This is a **zero-sum game** — whatever one player wins, the other loses.
Pure conflict, zero room for cooperation (unlike the last two games).

## No stable pure outcome

Check every cell — someone always regrets their move:

- (H,H): B wishes they'd played Tails
- (H,T): A wishes they'd played Tails
- (T,H): A wishes they'd played Heads
- (T,T): B wishes they'd played Heads

It's musical chairs — whatever fixed move you commit to, the other player
has a counter to it, and you have a counter to that, forever. **No cell is
stable.** There is no pure-strategy Nash Equilibrium here.

## Mixed strategies

The fix: stop committing to one move. Instead, randomize between your
options on purpose, with specific probabilities. Here (by symmetry) the
equilibrium is: **both players play Heads/Tails 50/50.**

### The counterintuitive part

You don't choose your own probability split to directly maximize your own
payoff. You choose it so the **other player is indifferent** between their
own options — so there's no exploitable pattern in your behavior.

If you played Heads 60% of the time, the opponent could notice and lean
into whichever response punishes that bias. 50/50 is the one split where
you genuinely can't be exploited — and the same logic applies to them. In
asymmetric games the exact split won't be 50/50, but it's always picked by
this same "make the other player indifferent" logic.

## The real-life lesson

When a situation is pure conflict and there's no stable deterministic plan
— your opponent can always counter whatever you lock in — the right move is
to be **deliberately, precisely unpredictable**. Not "random" in a sloppy
sense — following exact probabilities calculated so you can't be exploited.

This is the real math behind:

- Penalty kicks in soccer — both keeper and kicker mix their choices in
  calculated ratios, not just gut feel
- Bluffing frequency in poker
- Rock-paper-scissors against a decent opponent
- Randomizing security patrol routes/timing so they can't be predicted
- Varying pricing/promotions against a competitor who's watching your
  patterns

**How to use this:** if you notice you keep "losing" in some repeated
back-and-forth with an opponent who adapts to you (a competitor, a
negotiation, a game), ask whether you've become predictable. If the
situation is truly adversarial with no stable fixed plan, the fix usually
isn't "pick a better fixed move" — it's to mix your moves in a calculated,
hard-to-read way.

## So far: three flavors of game

1. **Prisoner's Dilemma** — individual rational choices → bad group outcome
   (trust problem)
2. **Battle of the Sexes** — multiple stable outcomes, real issue is
   coordination, not logic
3. **Matching Pennies** — zero-sum conflict, no stable fixed plan exists,
   the fix is calculated unpredictability
