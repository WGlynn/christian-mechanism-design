# CMD Foundations (Outline)

> Status: outline, not prose. We perfect the theory here before building
> anything on it. Slow burn. This is the last design, so the groundwork is the
> point.
>
> Rule for this document: a section is "solid" only when it could survive a
> hostile reviewer. Nothing downstream gets built until the section it depends on
> is solid. The mechanisms catalog is illustration, not foundation, and it waits.

## 0. What this document is

The theoretical spine of Christian Mechanism Design. Definitions, the central
claim, the axioms, the guardrail, and the open questions. Everything else in the
repo hangs off this. If a claim is not anchored here, it is provisional.

## 1. Position in the AMD family

- CMD is a variant of Augmented Mechanism Design.
- Inherited: augment, do not replace; structural properties over discretionary
  policy; the accountability hierarchy.
- Added: a layer of accountability above physics (conscience), and a source
  above the mechanism (the moral).
- To pin precisely: state exactly what CMD adds that AMD does not already
  contain, in one sentence that a skeptic would grant.

## 2. Definitions to fix

- **Word-deed gap (hypocrisy).** The divergence between a professed utility
  function u' and a revealed utility function u.
- **The airgap.** The region of u that no purely economic mechanism can observe
  or contract on. (Formal statement in thesis section 2; tighten here.)
- **Internalized enforcer.** A change in u itself, not an external penalty added
  on top of u.
- **Moral-into-intent.** The one-directional map: sermon, then moral, then
  design intent, then mechanism. The reverse is forbidden.
- **Sacrament.** The boundary we never cross. Define it precisely enough that the
  guardrail in section 3 is mechanically checkable, not a matter of taste.

## 3. The guardrail (non-negotiable)

- Throne, not Babel. `orientation.md` is canonical.
- Needed: a decision procedure a designer can run on any candidate mechanism.
  Draft test: does the mechanism (a) claim a sacred function, (b) mediate grace,
  or (c) ask to be trusted the way the sacrament is trusted? Any yes, reject.
- To develop: make each clause of that test unambiguous, with examples on both
  sides of the line.

## 4. The central claim

- The two ceilings are the same shape pointed opposite ways (thesis section 3).
- Formal target, to be stated as a proposition with separable clauses:
  1. For any purely economic mechanism, the airgap is nonempty.
  2. A genuine internalized honesty commitment is an enforcer that acts exactly
     inside the airgap.
  3. A well-formed mechanism makes the word-deed gap unprofitable from the design
     side.
- For each clause, label honestly: theorem, conjecture, or design heuristic. Do
  not let a heuristic wear the clothes of a proof.

## 5. Axioms and commitments

- Voluntary entry. No mechanism is imposed.
- Metaphysics-agnostic at the engineering layer. CMD functions wherever the
  commitment is genuinely internalized, without adjudicating its source.
- Moral-truth dependence. A mechanism is only as good as the moral it encodes is
  true. The hard question this raises (who adjudicates "true," and must CMD
  answer it) is deferred to section 8, not dodged.
- One direction only. The map in section 2 never reverses.

## 6. Mechanism-family criteria

- What makes a mechanism a CMD mechanism, rather than merely a good mechanism?
- Candidate criteria: its design intent traces to a named moral; it passes the
  Babel test; it closes a specific word-deed gap; its structural property is
  identified.
- To resolve: are these necessary, sufficient, or both? A clean answer is what
  turns the catalog from a list into a theory.

## 7. Relationship to the canon

- Honesty as a structural load-bearing property.
- Filter coincidence (the cost that filters sincerity is the signal of it).
- The airgap problem.
- Augmented governance and the accountability hierarchy.
- The Cincinnatus and humility discipline (the mechanism gives up the seat).
- Map each connection precisely. Stub for now.

## 8. Open theoretical questions (the slow burn)

- Who adjudicates moral truth, and can CMD stay agnostic, or must it commit?
- Generalization. If there is a family for any tradition, name the genus and the
  species. Is the genus "Moral Mechanism Design," with CMD one species?
- Is the central claim a theorem, a research program, or a design philosophy? Be
  honest, clause by clause.
- Failure modes. How does a CMD mechanism go wrong even when it passes the Babel
  test?
- The non-Christian designer. Formalize the point that the mechanisms are useful
  regardless of the designer's faith, and show why that does not weaken the
  claim.

## 9. Build order (deferred)

Nothing is built until its dependency in sections 1 through 6 is solid. The
catalog waits. The theory comes first, on purpose.
