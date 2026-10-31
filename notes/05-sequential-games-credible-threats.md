# 05 — Sequential Games & Credible Threats

## Sequential vs. simultaneous

So far, both players chose at the same time (Prisoner's Dilemma, Battle of
the Sexes, Matching Pennies). In a **sequential game**, one player moves
first, and the second player gets to see that move before responding.

## The Market Entry Game

A small company (**Entrant**) is deciding whether to enter a market owned
by a big company (**Incumbent**). Incumbent can only respond if Entrant
actually enters.

1. Entrant chooses: **Enter** or **Stay Out**
2. If Entrant enters, Incumbent chooses: **Fight** (price war) or
   **Accommodate** (share the market)

Payoffs:

|                                  | Entrant | Incumbent |
|----------------------------------|---------|-----------|
| Stay Out                        | 0       | 5         |
| Enter → Incumbent Fights         | -3      | -1        |
| Enter → Incumbent Accommodates   | 2       | 2         |

Before Entrant decides, Incumbent announces: **"If you enter, I will
fight."** — trying to scare Entrant off.

## Why the threat is empty

Reason it backward from the last decision point, not from what was said.
If Entrant actually enters, and it's genuinely time for Incumbent to pick
Fight or Accommodate, Incumbent looks only at -1 vs. 2 and obviously prefers
**Accommodate**. The threat to fight was never actually in Incumbent's own
interest to carry out — it's an **empty / non-credible threat**.

A rational Entrant sees through this and enters anyway, getting 2 instead
of 0.

**The core method:** don't evaluate a threat by what someone *says* they'll
do — evaluate it by what they'd *actually* prefer to do once they're really
standing at that decision point. (This "check every decision point, not
just the final outcome" version of backward induction is formally called
**Subgame Perfect Equilibrium** — Nash Equilibrium applied at every node of
the game tree, which rules out equilibria that only work because of a bluff
nobody would really act on.)

## The real-life lesson, both directions

### When someone threatens you
Ask: would it actually be in their interest to follow through, once the
moment of truth arrives? If not, it's probably a bluff.

- A landlord threatening eviction over a trivial dispute (eviction + re-renting
  is expensive and slow for them too)
- A country threatening a war that would wreck its own economy
- A boss threatening to fire their most productive employee over pushback
- A client threatening to walk over a minor invoice dispute

In all of these, check the threatener's own payoff at the actual moment of
follow-through — not their payoff from just scaring you.

### When you want your own threat to be believed
Just saying it isn't enough — you need to make following through genuinely
your own best interest at that future moment. This needs a **commitment
device**:

- A contract with real penalties for backing down
- A public commitment, so backing down now costs you reputation (a real
  cost, not just an empty one)
- Literally removing your own ability to back out (burning the bridge)
- A track record over repeated dealings of always following through — this
  connects straight back to [[04-repeated-games-shadow-of-the-future]]:
  reputation built over time is what makes future threats credible without
  re-proving them every time

## Where this shows up in real life

- Negotiation tactics — walk-away threats, deadlines, ultimatums: ask if
  the other side would actually prefer to follow through
- Pricing wars between competitors (same shape as the Entrant/Incumbent
  game)
- Parenting — threatened punishments that are never enforced stop working,
  because kids correctly learn the threat is empty
- Military deterrence / "red lines" — credibility of a threat depends on
  whether following through actually serves the threatener's own interest
  when the moment arrives
