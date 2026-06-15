# The Correspondence

> The claim the rest of the repo leans on, stated precisely. The README says the
> two ceilings are "the same shape, pointed in opposite directions."
> `foundations.md` defines the airgap and the internalized enforcer separately.
> This document states the pairing between them, the conditions under which it
> holds, and the exact sense in which the two halves close one gap. It is the
> spine of the spine. Complete means ready for critique, not finished.

## 1. What is being paired

CMD's whole bet is a correspondence between two things that look unrelated:

- a **mechanism invariant**, a structural property a designed mechanism enforces
  on observable signals, and
- a **moral commitment**, an internalized change in an agent's own utility
  function.

The thesis is not that these are similar. It is that they are two enforcers of
the *same constraint*, acting on the *same gap*, from opposite sides of the line
that divides the observable from the private. One acts on the signal. The other
acts on the will. The constraint they jointly enforce is: profession equals
deed.

## 2. The line, and the two sides of it

Fix one agent. Partition everything about that agent into two regions by a single
test, can a mechanism observe and contract on it.

- **Observable.** Bids, stakes, on-chain actions, timestamps, revealed outcomes.
  A mechanism can price these, lock these, score these.
- **Private.** The true utility function u, the will, the intent, the off-chain
  act no signal reports. A mechanism cannot reach in here. This is the airgap,
  defined in `foundations.md` section 2.

The word-deed gap straddles the line. Profession u' is partly observable, you can
hear it. The deed under pressure is governed by u, which lives on the private
side. Hypocrisy is exactly the case where the observable profession and the
private preference disagree, and the disagreement hides on the side no mechanism
can read.

A purely economic mechanism can therefore only ever pull on the observable side
of the gap. That is its ceiling, and it is a ceiling of *location*, not of
cleverness. No improvement in mechanism design moves the line, because the will
is never a signal.

## 3. The pairing, stated

A mechanism invariant and a moral commitment **correspond** when they enforce the
same constraint C on the same agent, the mechanism acting on the observable side
of the line and the commitment acting on the private side.

Write it as a closure. Let the constraint be C, "profession equals deed."

- The mechanism enforces C restricted to the observable region. Call this the
  observable closure. It is total on what it can see and empty on what it cannot.
- The commitment enforces C restricted to the private region. It changes u so
  that defection is internally costly. It is total on the will and silent on the
  signal, because it adds no external penalty.

Neither closure is complete alone. The observable closure leaves the private
region open, which is the airgap. The private closure leaves the observable
region unstructured, which is why exhortation without structure drifts under
load. The two closures have disjoint reach and a shared boundary. Their union
covers the whole gap. That union, and only that union, closes C across the line.

This is the precise content of "same shape, opposite directions." Same
constraint C. Same agent. Disjoint, complementary regions of reach. The
correspondence is not an analogy between two systems. It is a partition of one
enforcement problem into the only two pieces it has.

## 4. Why it is closure and not double-counting

A fair objection: if the mechanism already makes defection unprofitable, what does
the commitment add, and vice versa. The answer is that each is load-bearing
exactly where the other has no reach, so there is no overlap to double-count.

- Where behavior is observable, the mechanism binds and the commitment is
  redundant. A bound agent needs no conscience to be held to a locked stake.
- Where behavior is private, the commitment binds and the mechanism is blind. A
  conscience-bound agent keeps the deed aligned in the region no stake can lock.

The gap is closed at every point by exactly one of the two, and the point of
handoff is the observable-private line. This is why the loop in the README is
bidirectional without being circular. The mechanism does not enforce the private
region through the commitment, nor the commitment the observable region through
the mechanism. Each does its own half. The bidirectionality is that each makes
the other's half *worth doing*: structure is wasted on an agent with no internal
commitment to align, and commitment is strained on an agent with no structure to
carry the observable load.

## 5. When the correspondence holds, and when it fails

The pairing is conditional. State the conditions so the failures are checkable.

The correspondence holds for a given (mechanism, commitment, agent) when all of:

1. **Same constraint.** The mechanism invariant and the moral commitment are two
   enforcements of one C, not two different constraints that happen to co-occur.
   If the mechanism enforces throughput and the commitment enforces honesty, there
   is no correspondence, only coincidence.
2. **Genuine internalization.** The commitment is a real change in u, not a
   profession of one. A professed-but-unheld commitment lives entirely on the
   observable side and closes nothing on the private side. This is clause 2 of
   `foundations.md` section 4, and it is where the framework's empirical risk
   sits.
3. **Disjoint reach respected.** The mechanism does not try to legislate the
   private region (that overreach is one road to Babel, the code claiming the
   will), and the commitment is not asked to substitute for missing structure on
   the observable side (that is exhortation pretending to be design).

It fails when any condition breaks:

- **Constraint mismatch** gives coincidence dressed as correspondence. Guarded by
  condition 1, and this is the decoration objection's true target: an inert pairing
  is one where C is not actually shared.
- **Hollow commitment** gives a one-sided closure that still has the airgap open.
  The mechanism runs, the conscience does not, and defection lives in the private
  region untouched. Guarded by condition 2, and unguaranteeable in principle,
  because internalization is itself a private-region fact. CMD can require it; it
  cannot verify it. Named honestly, not dodged.
- **Reach violation** is the Babel failure on one side and the exhortation failure
  on the other. Guarded by condition 3, which is the Babel test (`foundations.md`
  section 3) seen from the correspondence angle: T1 through T3 forbid the mechanism
  from claiming the private and the sacred, T4 keeps the moral upstream of the
  mechanism so the two enforce one C rather than the mechanism inventing its own.

## 6. What this buys, stated plainly

The correspondence is the reason the two-system claim is structural and not
poetic. It says the airgap is not closed by adding religion to economics. It is
closed because the gap has exactly two regions, the observable and the private,
and there is exactly one kind of enforcer for each, and the moral commitment and
the mechanism invariant are those two enforcers. The framework is the observation
that the partition is forced. Once you see the gap has two sides and that no
single enforcer spans both, the pairing is not a design choice. It is the shape
of the problem.

This does not make CMD a theorem. Conditions 2 and 3 carry empirical and
disciplinary weight that no proof discharges, exactly as `foundations.md` section
4 labels. It makes the correspondence the honest center of the framework: a forced
partition, a complementary pair of closures, and a clear, checkable account of
when the pairing is real and when it is only a verse written over a mechanism.
