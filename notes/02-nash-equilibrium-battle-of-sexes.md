# 02 — Nash Equilibrium & the Battle of the Sexes

## Nash Equilibrium (formal idea)

A combination of strategies (one per player) such that **no player can
improve their own payoff by unilaterally switching strategy**, given
everyone else's strategy stays fixed. It's a state of mutual best response —
not necessarily a "good" outcome, just a *stable* one.

Contrast with the Prisoner's Dilemma: there, one player's dominant strategy
didn't depend on the other's move at all. Nash Equilibrium is the more
general tool — useful even when no dominant strategy exists.

## Battle of the Sexes

A couple wants to be together; they disagree on activity. One prefers
**Opera**, the other prefers the **Game**. Payoffs:

|                   | B: Opera     | B: Game      |
|-------------------|--------------|--------------|
| **A: Opera**      | A: 2, B: 1   | A: 0, B: 0   |
| **A: Game**       | A: 0, B: 0   | A: 1, B: 2   |

### No dominant strategy

Unlike the Prisoner's Dilemma, A's best move **depends on what B does**:
- If B picks Opera → A's best response is Opera (2 > 0)
- If B picks Game → A's best response is Game (1 > 0)

A's best response *flips* depending on B's choice — so there's no dominant
strategy. Same for B by symmetry. This is where Nash Equilibrium (checking
mutual best responses for a specific combination) becomes the useful tool,
rather than dominance (checking if one choice always wins).

### Two Nash Equilibria

Checking **(Opera, Opera)**: given A picks Opera, Opera is A's best response
(2 vs 0 for switching to Game). Given B picks Opera, Opera is B's best
response (1 vs 0 for switching). Neither wants to unilaterally switch →
**Nash Equilibrium**.

Checking **(Game, Game)**: same logic holds in reverse → also a **Nash
Equilibrium**.

### Key insight: multiple equilibria

Nash Equilibrium does not guarantee a *unique* predicted outcome — only that
an outcome is self-consistent/stable once reached. Here there are two
equally "stable" outcomes, and the real-world problem becomes **coordination**:
which stable outcome do the players actually land on, especially without
communication? (Real-world tie-breakers: conventions, communication, or
"focal points" — salient/obvious choices both players gravitate to.)

### Next

Battle of the Sexes still has *some* pure-strategy Nash Equilibria (two, in
fact). The next example (Matching Pennies) has **none** — which is what
motivates **mixed strategies**.
