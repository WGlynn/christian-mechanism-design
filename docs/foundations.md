# CMD Foundations

> Status: developing. This is the theoretical spine of Christian Mechanism
> Design. Slow burn. This is the last design, so the groundwork is the point.
>
> Rule for this document: a section is "solid" only when it could survive a
> hostile reviewer. Nothing downstream gets built until the section it depends on
> is solid. The mechanisms catalog is illustration, not foundation, and it waits.

## 0. What this document is

The theoretical spine. Definitions, the guardrail, the central claim, the
strongest objection, and the open questions. Everything else in the repo hangs
off this. If a claim is not anchored here, it is provisional.

## 1. Position in the AMD family

CMD is a variant of Augmented Mechanism Design.

- Inherited from AMD: augment, do not replace; structural properties over
  discretionary policy; an accountability hierarchy where lower layers cannot
  capture higher ones.
- Added by CMD: a layer of accountability above physics (conscience), and a
  source above the mechanism (the moral).

What CMD adds that AMD does not already contain, in one sentence a skeptic should
grant: AMD augments a mathematical invariant; CMD augments a *moral* invariant it
does not itself generate, using the same discipline.

## 2. Definitions

Pinned precisely, because the guardrail in section 3 is only as checkable as
these are sharp.

- **Word-deed gap (hypocrisy).** The divergence between a professed utility
  function u' and a revealed utility function u.
- **The airgap.** The region of u that no purely economic mechanism can observe
  or contract on. For any mechanism acting only on observable signals, there
  exist preference profiles where the agent's optimal action under private u
  diverges undetectably from the intended one.
- **Internalized enforcer.** A change in u itself, not an external penalty added
  on top of u. It moves the agent's true preferences, not their constraints.
- **Moral-into-intent.** The one-directional map: sermon, then moral, then design
  intent, then mechanism. The reverse is forbidden (section 3, T4).
- **The two planes.** Every claimed function of a mechanism is either
  *horizontal* (person to person, person to community) or *vertical* (person to
  God). CMD mechanisms operate only on the horizontal plane.
- **Sacrament (the boundary).** For CMD's purposes, an act the tradition holds to
  effect or mediate a vertical relation, grace conferred, sin absolved, communion
  enacted, whose efficacy is held to come from God and not from the mechanics of
  the act. Its defining property here: its function is vertical and
  non-substitutable. It is not a thing a design can perform. CMD never enters the
  vertical plane, so it never touches the sacrament.

## 3. The guardrail: the Babel test

Non-negotiable. `orientation.md` is canonical; this is its decision procedure.

Given a candidate mechanism M with claimed function F, M is Babel (reject) if any
of the following is true:

- **T1, vertical-claim.** Does F include any person-to-God function: conferring
  grace, forgiving sin, sanctifying, mediating salvation? If yes, reject.
- **T2, substitution.** Does M present itself as a replacement for, or the
  equivalent of, a sacramental act ("this *is* confession / baptism /
  communion")? If yes, reject.
- **T3, object-of-trust.** Does M ask to be trusted, revered, or have faith
  placed in it the way the sacred is trusted? Is the code the object of faith? If
  yes, reject.
- **T4, direction.** Does the design run moral, then intent, then mechanism
  (forward)? Or does it elevate the mechanism to generate or define the moral
  (reverse)? Reverse, reject.

M passes iff T1-T3 are "no" and T4 is "forward."

Worked both sides. *Almsgiving pool* (section 4): horizontal (members to members),
claims no grace, asks no faith in itself, runs moral-to-mechanism. Passes.
*"Confession-as-code"*: claims to absolve or to stand in for the sacrament,
vertical. Fails T1 and T2. Babel.

## 4. The central claim

Stated as a proposition with three separable clauses, each labeled honestly for
what it is. The intellectual honesty here is load-bearing: a heuristic must not
wear the clothes of a proof.

1. **For any purely economic mechanism, the airgap is nonempty.**
   *Label: theorem-grade, with established lineage.* This is a restatement in our
   terms of the limits on eliciting private types without cost (the incomplete-
   contracts and revelation-limit tradition). A fully rigorous statement requires
   fixing the model, which this document defers, but the claim is not in serious
   doubt.

2. **A genuine internalized honesty commitment is an enforcer that acts exactly
   inside the airgap.**
   *Label: definitional, near-tautological, and that is a strength.* By how we
   defined the internalized enforcer (a change in u) and the airgap (the
   unobserved region of u), this is true by construction. It establishes that the
   framework is coherent, not that such commitments are common. Whether real
   people carry them is an empirical matter, named in clause 3's dependence.

3. **A well-formed mechanism makes the word-deed gap unprofitable from the design
   side.**
   *Label: design heuristic, supported by examples, not proven in general.* "Well-
   formed" carries weight we have not discharged. We can show particular
   mechanisms do this (commit-reveal, costly signaling, fruit-scored attribution).
   We cannot yet show all well-formed mechanisms do, nor define "well-formed"
   independently of the result.

Honest synthesis: CMD is a research program and a design philosophy, not a
theorem. Clause 1 has theorem-grade lineage; clause 2 is definitional; clause 3
is a heuristic with examples. One rigorous leg, one coherent leg, one promising
leg. Saying so plainly is what makes the framework worth trusting.

## 5. The strongest objection, steelmanned

The objection most likely to be fatal, stated at full strength before it is
answered.

**The decoration objection.** Mechanism design already has costly signaling,
commitment devices, and revealed-preference verification. Writing a Bible verse
over each one adds no constraint, predicts nothing new, and changes no design
choice. The moral-into-intent map is post-hoc storytelling: you build a good
mechanism, then find a verse that fits. Operationally, CMD equals AMD, and the
Christianity is inert ornament. If true, this guts the thesis.

**The honest answer.** The objection wins one point and loses two, and the
scorecard should be kept openly.

- *Conceded.* On the pure-mathematics axis, a CMD mechanism is just a good
  mechanism. The math is not new. CMD never claimed novel math, and any account
  that implies it does is wrong.
- *Lost, point one: the input.* Christianity is a generative source of design
  intents and a selection filter on which gaps are worth closing. A designer
  mining the Sermon on the Mount for word-deed gaps will find and prioritize
  different mechanisms than one maximizing throughput. The moral is not
  decoration on the output; it is the search heuristic on the input. It changes
  *which* mechanisms get built, even if each, once built, is "just" good design.
- *Lost, point two: complementarity.* Pure mechanism design treats u as fixed and
  exogenous. CMD's distinctive bet is that the internalized commitment and the
  mechanism are complementary, each raising the other's marginal product (the
  bidirectional loop of the README). That is a substantive empirical claim a
  commitment-blind account cannot make.

CMD does no work at the pure-math layer and real work at the input-selection and
human-enforcement layers. That is the defensible position, and it concedes
exactly what it should.

## 6. Moral-truth adjudication

The hard question: a mechanism is only as good as the moral it encodes is true.
Who adjudicates "true"? Can CMD stay agnostic?

The dilemma. If CMD must adjudicate moral truth, it collapses into theology and
loses its engineering generality. If it stays fully agnostic, "true moral" is
undefined and the framework floats.

The resolution is the AMD move, applied to ethics. CMD operates *conditionally*:

    IF moral m is held true, THEN a mechanism encoding m as intent
    aligns horizontal behavior toward m.

CMD supplies the conditional engineering. The tradition supplies the antecedent,
which morals are true. CMD never rules on which tradition is right. This is
augment-do-not-replace pointed at the moral invariant: the tradition is the
invariant CMD does not generate, and CMD augments it with structure.

This is exactly why the framework is faith-agnostic at the engineering layer
(README point 1): moral-truth adjudication is externalized to the tradition the
designer commits to.

The residual risk, named and not dodged: garbage in. A false moral encoded
faithfully produces faithfully-aligned bad behavior. CMD cannot protect against a
false antecedent; that protection lives entirely in the tradition's own truth.
CMD is a force-multiplier on the moral, for good or ill. This is why the
guardrail and the choice of tradition are load-bearing, not incidental.

## 7. The genus: Moral Mechanism Design

CMD is one species. The genus is **Moral Mechanism Design (MMD)**: encode the
morals of a tradition-held-true as the design intent of coordination mechanisms,
one direction only, never replacing the tradition's sacred core.

A tradition can host an MMD species if it has three things:

1. a corpus of moral teaching (the source of design intents),
2. an internalized-commitment practice (the off-chain enforcer of section 2), and
3. a notion of the sacred that must not be mechanized (the Babel boundary).

What is universal (the genus): the moral-to-intent direction, the Babel boundary,
and the enforcer-mechanism complementarity. What is tradition-specific (the
species): the actual morals, and the actual location of the sacred boundary.

Honest scope: the genus is a frame, not yet a worked theory for any tradition but
Christianity. CMD is the species under construction. The others are named, not
built. Christianity is first because it is the tradition the author puts his
faith in and places his bet on, not because of any claim to superiority (README
point 2).

## 8. Relationship to the canon

Each connection stated precisely.

- **Honesty as a structural load-bearing property.** CMD clause 3 *is* this
  property with an explicit moral source. "Let your yes be yes" is its scriptural
  statement.
- **Filter coincidence.** The costly commitment (the cross) both filters for
  sincerity and signals it. CMD instances are points in the filter-signal design
  space; the almsgiving pool is the strict corner, filter without signal.
- **The airgap problem.** CMD is a closure path: the human-side closure via the
  internalized enforcer, complementary to a chain-side closure via consensus
  mechanisms. CMD supplies the off-chain half.
- **Augmented governance, Physics over Constitution over Government.** CMD extends
  the stack upward, conscience above physics, and the Babel boundary is the rule
  that the mechanism (a lower layer) never claims the apex. The throne stays
  unoccupied by code.
- **Augment, do not replace.** CMD's whole orientation, and the moral-truth
  externalization of section 6, is this principle applied to ethics.
- **Cincinnatus and structural humility.** The mechanism gives up the seat. It
  points back at the moral, not at itself. Surrendering the throne is the design
  target, not a side effect.
- **Structure does the work.** CMD names the structural property (a moral encoded
  as a behavior-aligning constraint) and lets it carry the load, instead of
  relying on exhortation or policy.

## 9. Open questions and build order

Still open, the slow burn:

- Is clause 1 worth formalizing fully, or is its lineage enough for our purposes?
- Failure modes: how does a CMD mechanism go wrong even when it passes the Babel
  test? (Goodhart on fruit-scoring is the first candidate.)
- Coercion creep: does community adoption make "voluntary entry" a fiction, and
  what structural guard answers that?

Build order: nothing is built until its dependency in sections 1 through 6 is
solid. The catalog waits. The theory comes first, on purpose.
