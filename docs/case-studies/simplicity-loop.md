# Case study: the Simplicity Loop (pruning for fruit)

> A worked instance of CMD. A sermon supplies a *telos* and a *guardrail* that a
> complexity-reducing mechanism cannot supply for itself; the mechanism supplies the
> structure that turns the sermon from exhortation into default behavior. Read
> [`../orientation.md`](../orientation.md) first — this case study assumes Throne, not Babel.

## The sermon

> "Every branch in me that beareth not fruit he taketh away; and every branch that beareth
> fruit, he pruneth it, that it may bring forth more fruit." — John 15:2

Two cuts, not one. The dead branch is **taken away**. The living, *fruitful* branch is
**pruned** — cut back precisely because it is alive, so it bears more. The vinedresser's aim
is never a smaller vine. It is a larger harvest. The cut is in service of the fruit, and the
vine's purpose is not on the table.

## The moral

In building, the standing temptation is the opposite of laziness: it is the *vanity build* —
the clever abstraction, the extra layer, the configurable knob, the general solution to a
specific problem. Each works. Each flatters the builder. And each is a tax paid by everyone
downstream, in three currencies that decide whether the work lives: **understanding** (every
concept a reader must hold), **adoption** (every barrier to someone joining), and **security**
(every line is attack surface, every interaction is something to audit). Complexity is rarely
removed by the person who added it, because removing working code feels like loss.

The moral John 15:2 codes is sharper than "keep it simple." It is: *prune the living for more
fruit — and never cut into the vine's purpose.* Both halves matter. The first licenses cutting
code that works. The second forbids cutting that buys cleanliness at the cost of the goal.

## The two gaps (the CMD move)

**Mechanism design cannot, by itself, tell essential complexity from excess.** A mechanism that
optimizes a complexity metric — lines of code, cyclomatic complexity, file count — measures
*smaller*, not *more fruitful*. Pointed at a real codebase it Goodharts: it will cut a load-
bearing solver because the solver is "complex," trading away a capability to improve a number.
A pure minimizer has no principled stopping point and drifts toward minimalism-as-vanity, which
is the same vanity it set out to remove, wearing the opposite coat. The mechanism can see the
size of a branch. It cannot, from inside, see the fruit.

**Exhortation cannot, by itself, stop the vanity build.** "You aren't gonna need it" is the
most-preached and least-kept rule in engineering. The same word-and-deed gap the faith names in
Matthew 15:8 shows up at the keyboard: the builder agrees simplicity is a virtue and ships the
clever layer anyway, under deadline, because the abstraction is satisfying and the cut is
painful. Appeal has a ceiling here too.

## Why they fit

The two ceilings are the same shape from opposite sides of the line between what is measurable
and what is willed.

**The sermon supplies the objective function the mechanism lacks.** John 15:2 gives the cut a
*telos* — fruit, not smallness — and a *guardrail* — *more, never less; the vine's purpose is
sacred.* That is exactly the missing specification. With it, the mechanism's three buckets
become well-defined: take away the **dead** (no fruit), keep the **fruitful-essential** (the
goal is impossible without it, at this complexity — essential complexity is not over-engineering
and pruning it is the forbidden cut), and prune the **fruitful-excess** (the goal would be met
identically with less). The hard discrimination — essential versus excess — is decided against
the goal the branch serves, and when it is unclear, the guardrail rules: keep it, because you do
not compromise the goal on a guess.

**The mechanism supplies the structure the sermon lacks.** A loop does by construction what
exhortation cannot do by appeal. Dead branches are removed automatically, but only when the full
test suite stays green — a cut that reddens a test was never dead, it was load-bearing, and it is
reverted. Living-branch prunes are never auto-applied; each is *staged* with the fruit it adds and
a proof that every goal and invariant still holds, and a separate verifier confirms behavior is
preserved before it is even proposed. The vanity build becomes unprofitable: there is now a
standing process whose default is to find and surface it, and inventing a cut to look productive
is itself ruled out — pruning for pruning's sake is the precise failure the guardrail forbids.

## Throne, not Babel

The loop never becomes the vinedresser. It *takes away* dead wood on its own, because that cannot
harm the vine. But it only *proposes* pruning a living, fruitful branch — the judgment that a
working capability is excess rather than essential is reserved for the gardener, never automated.
This is not a limitation bolted on for safety; it is the sermon's own structure. In John 15 the
Father prunes the living branches; the branch does not prune itself. The mechanism is built to
the same boundary, and the boundary is exactly what makes an autonomous process unable to ever
amputate the work it serves.

The order holds: sermon → moral → design intent → mechanism. The moral is coded into the *intent*
of the loop (cut for fruit, never compromise the goal), not into a rule that replaces the
gardener's discernment. A complexity mechanism without this moral is a strictly worse thing — a
minimizer that will eventually cut the heart out of the work to improve a metric. The sermon is
what makes the mechanism safe to run.

## The mechanism, in one line

Maximize fruit (understanding × adoption × security) by removing complexity — dead branches
autonomously, living branches by proposal — under a hard invariant that no cut may reduce a goal,
a capability, or a security property. More fruit, never less tree.

---

*Reference implementation (one tradition's tooling, not part of the argument): the loop runs as a
standing process over the author's codebases, taking the lean-like-Bitcoin discipline as its first
scope. The mechanism is useful to a builder of any faith or none; the telos that makes it safe is
the one placed here.*
