# CMD Thesis: Christian Mechanism Design

> Complete means ready for critique, not finished. Opened 2026-06-14.

## 1. Lineage

Christian Mechanism Design is a variant of Augmented Mechanism Design (AMD).
AMD's core move is to augment a mathematical invariant rather than replace a
market or a government. Its accountability ordering is Physics over Constitution
over Government: a constraint enforced by physics outranks one enforced by a
constitution, which outranks one enforced by a government, because each lower
layer can be captured by the layer it is supposed to bind.

CMD extends that ordering by one layer at the top. Above physics it places
conscience, the internalized accountability of an agent who has bound their own
utility function. Physics enforces what is observable. Conscience enforces what
is not. CMD is the study of mechanisms that use both.

## 2. The airgap, stated plainly

Let an agent have a true private utility function u and a professed utility
function u'. A mechanism observes only signals: bids, stakes, on-chain actions,
contractible outcomes. It can shape behavior only through those signals.

The airgap is the claim that for any purely economic mechanism there exist
states in which the agent's payoff-maximizing action under u diverges from the
action the mechanism intends, and the mechanism cannot tell, because the
divergence lives in the unobserved part of u. Front-running, hidden defection,
and performative compliance all live in that gap. You can shrink it with better
observability, but you cannot close it from inside the economic layer, because
the will is never a signal.

This is the same ceiling Christianity names as hypocrisy: the gap between u'
(professed) and u (revealed). "This people honors me with their lips, but their
heart is far from me."

## 3. The symmetry

Two systems each have a ceiling. Mechanism design can specify behavior but
cannot reach intent. Christianity can address intent but cannot, by appeal
alone, specify behavior reliably under pressure. The ceilings are complementary,
not parallel, which is why one can serve as the other's floor.

**Christianity as the off-chain enforcer.**
A genuine internalized commitment changes u itself. The agent who has taken up
the cross has made defection internally costly, not because a mechanism punishes
it but because their own utility function now charges for it. From the
mechanism's side this looks like an agent whose u has moved toward u'. The
airgap narrows from the human side, in exactly the region no on-chain rule could
reach.

**Mechanism design as the anti-hypocrisy structure.**
A believer's problem is that u' and u diverge under load. Mechanisms are
precisely tools for making divergence costly or visible. Commit-reveal forces
the profession to be staked before the result is known. Costly signaling makes
sincerity and its signal the same act. Fruit-inspection makes the revealed
behavior the thing that is scored. None of these convert a person. They give a
willing person a structure in which living the profession is the
payoff-maximizing path, so the gap closes from the design side.

## 4. A worked mechanism: almsgiving without the left hand

"When you give to the needy, do not let your left hand know what your right hand
is doing" (Matthew 6:3). Read as a mechanism specification, this is a
commit-reveal scheme with the individual reveal permanently suppressed.

Design a mutual-aid covenant:

1. **Commit.** Each member privately commits a time-locked pledge. The
   commitment is a hash; the amount and identity are hidden. The lock is the
   cross: a binding pre-commitment whose later abandonment is internally costly.
2. **Reveal in aggregate only.** The pool's total is revealed and disbursed. No
   individual contribution is ever made public.
3. **Properties.**
   - The status payoff of visible giving is removed. You cannot give to be seen,
     because no one sees (Matthew 6:1). Performative givers have no reason to
     enter.
   - The cost of the time-lock filters for sincerity, and because the cost is
     borne privately, the filter cannot double as a public signal. Filter
     without signal. This is stricter than ordinary costly signaling and matches
     the text exactly.
   - Defection after commit is unprofitable on-chain (the lock) and unprofitable
     off-chain (conscience). The airgap is closed from both sides at once.

This is the same commit-reveal spine as a fair batch auction, retargeted from
price discovery to sincerity discovery. The mechanism is not new. Its
application to the word-deed gap is.

## 5. Objections

**It instrumentalizes faith.**
CMD treats commitment as a primitive without adjudicating its source. A genuine
believer loses nothing: the mechanism only makes their professed values easier
to live structurally. It does not reduce faith to utility. It gives faith better
scaffolding. The honest framing is that CMD is agnostic about why the commitment
is real, and only requires that it is.

**Mechanisms that fix behavior are coercive.**
Voluntary entry is the AMD guardrail and it is load-bearing here. The cross is
taken up, never imposed. A mechanism no one is forced into is a tool, not a
cage. CMD reveals and aligns; it never compels belief.

**Why Christianity specifically.**
Because it carries the sharpest internalized honesty commitment in the culture
this is being built in ("let your yes be yes, and your no, no"), and the
sharpest internal critique of hypocrisy. The structure generalizes to any
costly-commitment moral tradition. Christianity is the most load-bearing
instantiation, not the only possible one.

**The airgap is unclosable in principle.**
By pure economics, largely yes. CMD does not claim to close it on-chain. It
claims the off-chain half is closable by an internalized enforcer, and that
costly moral commitment is exactly such an enforcer. CMD supplies the half the
chain cannot.

## 6. What this is and is not

It is a design discipline: build coordination mechanisms that assume and reward
an internalized honesty commitment, and build that commitment a structure in
which honesty is the dominant strategy. It is not a church, not a doctrine, and
not a claim that mechanism design needs religion or that religion needs
mechanism design. It is the observation that, taken to their logical
conclusions, each completes the other.
