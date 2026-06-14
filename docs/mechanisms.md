# CMD Mechanisms

A catalog of concrete mechanisms in the Christian Mechanism Design family. Each
one names the word-deed gap it closes, the scripture it operationalizes, and the
structural property doing the work. The pattern is always the same: take a
verse that has been read for two thousand years as exhortation, and read it
instead as a mechanism specification.

## 1. Almsgiving without the left hand

A commit-reveal scheme with the individual reveal permanently suppressed.
Removes the status payoff of visible giving so performative givers have no reason
to enter; the private cost filters for sincerity without doubling as a public
signal. Full write-up in [`cmd-thesis.md`](cmd-thesis.md) section 4.

- Gap closed: giving to be seen rather than to give.
- Scripture: Matthew 6:1-4.
- Property: filter without signal.

## 2. The Pharisee filter

A reputation mechanism in which status cannot be claimed, only earned through
measured fruit. It targets the oldest hypocrisy in the text: the one who takes
the seat of honor on the strength of profession rather than deed.

**Design.**

1. **No self-conferred standing.** A member's weight in the community, in
   governance votes, in resource distribution, in whose proposal is heard, is a
   pure function of observed contribution. Titles, seniority, and declared
   devotion carry zero coefficient.
2. **Fruit is the only input.** Contribution is scored from realized downstream
   value: what was actually built, given, mended, or carried, and who relied on
   it. This is a Shapley attribution over the dependency graph of the
   community's work, the same construction used to attribute credit fairly in an
   open-source ecosystem.
3. **The score decays.** Past fruit discounts over time, so standing must be
   continually re-earned. You cannot coast on a reputation. "By their fruits"
   is present tense.

**Properties.**

- The Pharisee equilibrium is unprofitable. Professing much and doing little
  yields no standing, because profession has no coefficient and the score reads
  only deeds (Matthew 23:3, they say and do not).
- The unseen servant is correctly weighted. Quiet, load-bearing contribution
  scores exactly as high as its realized downstream value, regardless of whether
  it was announced (Matthew 25:21, the faithful servant).
- It is anti-fragile to performance. Because the input is fruit and not
  signaling, increasing the visible signal without increasing the fruit does
  nothing. The cheap path to status is closed by construction.

- Gap closed: standing claimed by word rather than earned by deed.
- Scripture: Matthew 7:16, Matthew 23:3, Matthew 25:14-30.
- Property: revealed-preference scoring with decay; profession has no
  coefficient.

## To design

Open slots in the catalog. Each is a verse waiting to be read as a mechanism.

- **Confession as commit of defection.** A private, costly acknowledgment that
  binds future behavior, read as the commit phase of a self-correction loop
  (Matthew 5:23-24, reconcile before you offer).
- **The narrow gate as a voluntary high-cost entry filter** that selects for
  commitment without compelling it (Matthew 7:13-14).
- **Forgiveness as a debt-clearing mechanism** that prevents a community from
  accumulating unpayable grudge-debt and deadlocking (Matthew 18:21-35).
- **The watchman as a staked early-warning role** with skin in the game for
  silence (Ezekiel 33).
