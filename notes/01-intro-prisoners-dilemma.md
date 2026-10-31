# 01 — Intro to Game Theory & the Prisoner's Dilemma

## What is game theory?

The study of strategic decision-making: situations where the best choice for a
player depends on what *other* players choose, not just on their own
preferences in isolation. This is what separates it from ordinary
optimization/decision theory.

Every game has three ingredients:

1. **Players** — the decision-makers
2. **Strategies** — the set of choices available to each player
3. **Payoffs** — the outcome each player receives for every combination of
   choices made by all players

## The Prisoner's Dilemma

Two suspects, A and B, are interrogated separately (no communication). Each
chooses to **stay silent** or **betray** the other. Payoffs are years in
prison (lower is better):

|                     | B stays silent | B betrays   |
|---------------------|-----------------|-------------|
| **A stays silent**  | A: 1, B: 1      | A: 3, B: 0  |
| **A betrays**       | A: 0, B: 3      | A: 2, B: 2  |

### Reasoning through it

Check A's best move in each possible case for B:

- If B stays silent → A betraying (0) beats A staying silent (1)
- If B betrays → A betraying (2) beats A staying silent (3)

Betray is better for A **regardless of what B does**. This is a **dominant
strategy**: a choice that is at least as good as the alternative no matter
what the other player does — no need to predict or guess the opponent's move.

By symmetry, B reasons the same way. Both players rationally betray, landing
on **(betray, betray) → 2 years each**.

### The dilemma

If both had stayed silent, each would only get **1 year** — strictly better
for both than the (betray, betray) outcome. But neither can risk unilaterally
staying silent, since that risks the worst individual outcome (3 years) if
the other betrays.

**Key insight:** individually rational choices can lead to a collectively
worse outcome. Self-interest doesn't guarantee group-optimal results.

### Preview: Nash Equilibrium

(betray, betray) is also a **Nash Equilibrium** — a state where no player can
improve their own payoff by unilaterally switching strategy, given what the
other player is doing. We'll formalize this next.
