# 01 — Game Theory 101 & the Prisoner's Dilemma

## What is game theory, really?

It's the study of situations where what's smart for you depends on what
other people do — not just your own preferences in isolation. Any time
you're thinking "I'd do X... but only if they don't do Y," you're already
thinking in game theory terms.

Every one of these situations breaks down into three things:

1. **Players** — who's choosing
2. **Strategies** — what each person can choose
3. **Payoffs** — what each person gets, for every combination of choices

## The Prisoner's Dilemma

Two suspects get caught and interrogated in separate rooms (no talking to
each other). Each one can **stay silent** or **betray** the other.
Outcome, in years of prison (lower is better):

|                     | B stays silent | B betrays   |
|---------------------|-----------------|-------------|
| **A stays silent**  | A: 1, B: 1      | A: 3, B: 0  |
| **A betrays**       | A: 0, B: 3      | A: 2, B: 2  |

### Why "betray" wins, logically

Put yourself in A's seat. You don't know what B will do, so check both
possibilities:

- If B stays silent → betraying gets you 0 years instead of 1. Betray wins.
- If B betrays → betraying gets you 2 years instead of 3. Betray wins.

Betraying is better **no matter what B does**. You don't even need to guess
B's move — betray always wins for you. That's called a **dominant
strategy**.

Since B is thinking the same way, both betray. Result: **2 years each.**

### The actual dilemma

If they'd both just stayed silent, they'd each only get **1 year** — better
for both! But nobody can risk it, because trusting the other guy and getting
betrayed is the worst possible outcome (3 years). So both play it "safe" and
both end up worse off than if they'd cooperated.

**This is the real lesson:** everyone acting in their own rational
self-interest can land the whole group in a worse spot than if they'd
cooperated — purely because nobody can trust the other side not to defect.

### Where this shows up in real life

- Two competing stores cutting prices into a price war neither one wanted
- Roommates not cleaning up, each hoping someone else does it first
- Countries stockpiling weapons when everyone would prefer disarmament
- Companies dumping environmental costs onto everyone else instead of eating
  the cleanup cost themselves
- Any "tragedy of the commons" — overfishing, traffic, shared office fridge

**How to use this:** when you spot a group making a collectively dumb
decision, ask — is this actually a trust problem, not a stupidity problem?
If so, the fix usually isn't "convince people to be nicer" — it's changing
the incentives (contracts, reputation, repeated interactions, regulation) so
that cooperating becomes the *individually* smart move too.

### Preview: Nash Equilibrium

(betray, betray) is also an example of a **Nash Equilibrium** — a state
where neither player wants to change their own move, given what the other
is doing. More on this next.
