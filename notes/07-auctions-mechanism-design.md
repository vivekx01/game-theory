# 07 — Auctions & Mechanism Design

## Flipping the whole approach

Everything so far asked: "given this game, what will rational people do?"
**Mechanism design** flips it: "what rules can I set so that rational
self-interest produces the outcome *I* want?" You're not predicting
behavior anymore — you're designing the game itself to engineer it.

## First-price sealed-bid auction

Everyone secretly submits one bid; highest bidder wins and pays **their
own bid**.

Bidding your true max value here is actually a bad move: if you win, you
pay exactly what the item is worth to you, so your profit is **zero**. The
real tension is between bidding high (better odds of winning) and bidding
low (bigger profit if you do win) — there's no dominant strategy, you have
to guess what everyone else will bid and shade your bid below your true
value to leave room for profit.

## Second-price auction (Vickrey auction)

Same setup, but the winner pays the **second-highest bid**, not their
own.

### Why bidding your true value is now a dominant strategy

- **Bid above your true value:** this can only change the outcome by
  making you win a case you'd otherwise lose. But then the price you pay
  (the second-highest bid) sits between your true value and your inflated
  bid — you're now paying more than the item is worth to you. Pure loss,
  no upside.
- **Bid below your true value:** this can only change the outcome by
  making you lose a case you'd otherwise win. But you were about to pay
  the *second*-highest bid anyway (not your own) — which in that case
  would've been below your true value. You just threw away a profitable
  win for nothing.

Bidding above value only risks loss; bidding below value only risks
missing free profit sitting on the table. So bidding your exact true value
can't be beaten in either direction — a genuine **dominant strategy**,
same category as betraying in the Prisoner's Dilemma.

## The real insight

The seller didn't need to ask anyone to be honest. They picked a **rule**
(pay the second price, not your own bid) that makes honesty the personally
optimal move, with zero need for trust or enforcement. That's mechanism
design in one sentence: design the rules so that selfish behavior and the
outcome you want for everyone become the same thing.

## Where this shows up in real life

- Online ad auctions (Google/Facebook-style ad placement) are variants of
  this exact mechanism
- Matching systems — organ donation allocation, school/residency
  assignment algorithms — are explicitly built so that reporting your true
  preference is the best strategy, removing the incentive to game the
  system
- Negotiation and deal structure — some structures make lying about your
  real walk-away number pointless; others make it tempting. The structure
  itself decides which, not the people's honesty

**How to use this:** when you're the one setting up a system — splitting
costs with roommates, running an internal team process, negotiating a deal
structure, running a sale — don't just hope people act in good faith. Ask:
"is there a rule I can pick where someone's own self-interest naturally
produces the honest or fair outcome, without needing me to police it?"
That's a much more durable fix than appealing to trust or fairness
directly.
