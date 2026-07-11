---
title: Theory of Constraints
description: Every system has one bottleneck that governs total throughput — improve anything else and nothing changes.
tags:
  - budding
  - flow
---

From Goldratt's *The Goal*: every system has one constraint that governs its total throughput. Improving any step that isn't the constraint doesn't increase throughput — no matter how good it feels, no matter how visible the improvement.

The method, in order:

1. **Identify** the constraint
2. **Exploit** it — get the most out of it before spending anywhere else
3. **Subordinate** everything else to it
4. **Elevate** it — invest to expand its capacity
5. **Repeat** — the constraint moves

The discipline is in step 3, which almost nobody does: deliberately letting non-bottleneck work sit idle or slow down because optimizing it is waste. Most "continuous improvement" programs are a portfolio of step-4 investments applied to non-constraints.

In quality terms: if regression testing is the constraint, adding developers makes delivery *slower* (more WIP arriving at the same choke point). If one team is the constraint, that's where dedicated capacity belongs — and the assignment should be revisited when the constraint moves, because it will.

Related:

- [[small-batches-fast-feedback|Small batches, fast feedback]] — big batches hide where the constraint is
- [[measure-outcomes-not-activity|Measure outcomes, not activity]] — activity metrics reward improving non-constraints
- [[conways-law|Conway's Law]] — sometimes the constraint is a team boundary, not a team
