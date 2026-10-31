# 08 — Evolutionary Game Theory & Hawk-Dove

## No conscious reasoning required

Everything so far assumed rational players deliberately choosing a
strategy. Evolutionary game theory drops that assumption entirely:
whichever behavior earns a better average payoff simply spreads through a
population over time (survival, reproduction, or just copying/imitation),
while worse-performing behavior dies out. Same payoff logic, zero
conscious calculation needed.

## Hawk-Dove

Animals compete over a resource. Each individual is "wired" as one fixed
type:

- **Hawk** — always fights for the resource
- **Dove** — always backs down rather than fight

Payoffs, with resource value V = 6 and fight-injury cost C = 10:

|                  | Meets Hawk | Meets Dove |
|------------------|------------|------------|
| **Hawk**         | -2 (fight, 50/50 shot, injury cost) | +6 (Dove retreats) |
| **Dove**         | 0 (retreats, no cost) | +3 (share peacefully) |

### Why neither pure population is stable

**All-Dove population, one mutant Hawk invades:** every encounter the
Hawk has is against a Dove → Hawk earns 6 per encounter, versus 3 for the
resident Doves fighting... er, sharing with each other. Hawk does much
better → Hawk spreads. **All-Dove is not stable.**

**All-Hawk population, one mutant Dove invades:** every encounter the
Dove has is against a Hawk → Dove earns 0, versus -2 for resident Hawks
fighting each other. Dove does better → Dove spreads. **All-Hawk is not
stable either.**

### The stable outcome: a mixed population

Since both pure extremes get invaded, the population settles into a
**stable mix** of both types — some fixed percentage Hawk, the rest Dove.
The stable ratio is exactly the point where being Hawk and being Dove earn
the *same* average payoff:

- If Hawks become more common than that ratio, the average Hawk runs into
  other Hawks more often (more costly fights), dragging Hawk's payoff
  below Dove's → Dove relatively thrives → the ratio corrects back down.
- If Hawks become rarer, the reverse happens → Hawk's relative payoff
  rises → the ratio corrects back up.

This self-correcting stable point is called an **Evolutionarily Stable
Strategy (ESS)**.

## Connection to mixed strategies

This is the exact same mathematical shape as
[[03-mixed-strategies-matching-pennies]] — but reinterpreted. There, one
individual secretly randomizes between two moves. Here, a whole
*population* settles into a stable proportion of two fixed types. Same
underlying math, different mechanism: no one calculates anything
consciously, it emerges automatically from whichever type is currently
out-earning the other.

## Where this shows up in real life

- Aggressive and accommodating types persist side by side in markets,
  teams, and species — neither ever fully "wins," because overcrowding
  either type creates an opening for the other to profit
- A market of all cautious, non-confrontational businesses invites an
  aggressive new entrant to profit disproportionately by grabbing
  uncontested share
- A market of all cutthroat competitors makes room for a cooperative
  niche player to profit by avoiding the costly fights entirely
- Personality and negotiating-style mixes within social groups and teams

**How to use this:** the "right" amount of aggression, risk-taking, or
assertiveness in any group isn't a fixed universal number — it depends on
what everyone else around you is currently doing. If a group/market looks
heavily skewed toward one type (all-accommodating, all-aggressive), that's
often a signal there's unclaimed profit available to whoever leans the
other way, at least until the balance shifts back.
