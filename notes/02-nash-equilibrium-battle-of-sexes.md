# 02 — Nash Equilibrium & the Battle of the Sexes

## Nash Equilibrium, in plain terms

A Nash Equilibrium is a "stable point" in a strategic situation — a set of
choices (one per person) where **nobody wants to change their own move**,
given what everyone else is doing.

It does NOT mean the outcome is good, fair, or the best possible result.
It just means it's stable — nobody acting alone can do better by switching.

**Why this matters in real life:** it answers the question "where will this
situation settle, and will it stay settled?" It's how you predict things
like pricing wars between competitors, why traffic clusters on the same
routes, or why an entire industry converges on the same business model —
and it tells you something important: if you change your own move but
others just adapt around you and cancel out your gain, you're fighting an
equilibrium. To actually change the outcome, you need to change the
incentives underneath it, not just your own move.

In the Prisoner's Dilemma, there was a shortcut: betraying was *always* the
best move regardless of what the other person did (a "dominant strategy").
Not every situation is that clean — which is where Nash Equilibrium becomes
the more general tool. Let's see a game where neither player has an
always-best move.

## Battle of the Sexes

A couple wants to spend the evening together but disagree on what to do.
One prefers **Opera**, the other prefers the **Game**. Both care more about
being together than about the activity itself. Payoffs:

|                   | B: Opera     | B: Game      |
|-------------------|--------------|--------------|
| **A: Opera**      | A: 2, B: 1   | A: 0, B: 0   |
| **A: Game**       | A: 0, B: 0   | A: 1, B: 2   |

### No "always correct" move here

Check A's best move in each case:
- If B picks Opera → A is better off also picking Opera (2 vs 0)
- If B picks Game → A is better off also picking Game (1 vs 0)

A's best move **flips** depending on what B does. There's no dominant
strategy — what's smart for you depends entirely on what the other person
does. This is actually how most real-life situations work (unlike the
Prisoner's Dilemma, which is a cleaner, more extreme case).

### Checking for stable points

A combination is a Nash Equilibrium if neither person wants to switch,
given what the other picked.

- **(Opera, Opera):** A has no reason to switch to Game (2 beats 0). B has
  no reason to switch to Game (1 beats 0). Stable → **Nash Equilibrium.**
- **(Game, Game):** Same logic in reverse. Also stable → **Nash
  Equilibrium.**

### The real lesson here

This game has **two** stable outcomes, not one. That's a big deal: Nash
Equilibrium doesn't promise a single predicted answer — just which outcomes
are self-consistent. Here, "everyone goes to Opera" and "everyone goes to
Game" are *both* fine, stable arrangements.

So the actual problem isn't selfishness or trust (like in the Prisoner's
Dilemma) — it's **coordination**: picking one of several equally good
options and getting everyone to land on the same one, often without being
able to communicate first.

### Where this shows up in real life

- Which side of the road everyone drives on — neither is "more correct,"
  it just needs to be consistent
- A company's whole team converging on one tool/process out of several
  equally fine options
- Social norms, meeting times, "what's the plan Friday night" — any time a
  group needs to land on *one* of several good options together

**How to use this:** when a disagreement isn't really about who's right,
but about which of several fine options to pick, stop arguing about logic —
that's not the issue. Use convention, communication, or precedent (a
"focal point") to just pick one and move on.

### Next

Battle of the Sexes still has *some* stable pure outcomes (two). The next
example — Matching Pennies — has **zero**, which is where "mixed
strategies" (randomizing your choice on purpose) come in.
