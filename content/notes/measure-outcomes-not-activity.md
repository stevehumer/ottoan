---
title: Measure outcomes, not activity
description: Tickets closed and test cases executed measure motion. Escape rate, cycle time, and the DORA four measure results.
tags:
  - budding
  - quality
  - flow
---

Activity metrics measure motion: tickets closed, test cases executed, hours logged, coverage percentages. Outcome metrics measure results: defect escape rate, cycle time, and the DORA four from *Accelerate* —

| Metric | What it tells you |
| --- | --- |
| Deployment frequency | How often you successfully ship |
| Lead time for changes | Commit to running in production |
| Change failure rate | Share of changes needing remediation |
| Time to restore | How fast you recover |

The research finding that makes these four special: they predict organizational performance better than team size, methodology, or process-maturity theater.

The trap with activity metrics isn't just that they're uninformative — it's that they're *steerable*. Any team under pressure can raise test-case counts without touching product risk. Outcome metrics resist gaming because they're anchored to what actually happened in production.

Two qualifiers I want to keep honest about:

- Outcome metrics are lagging. You still need leading signals day-to-day — just don't let the leading signals become the goal (Goodhart's Law).
- A metric without [[psychological-safety]] becomes a weapon, and weaponized metrics get gamed fastest of all.

Related:

- [[mechanisms-not-memos]] — outcome data is how you audit whether a mechanism works
- [[small-batches-fast-feedback]] — the DORA four largely measure batch size and feedback speed
- [[theory-of-constraints]] — activity metrics reward polishing non-constraints
