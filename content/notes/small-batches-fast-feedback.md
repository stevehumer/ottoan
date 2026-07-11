---
title: Small batches, fast feedback
description: Small batches with fast feedback beat large batches with slow feedback, almost without exception.
tags:
  - budding
  - flow
---

Small batches and fast feedback beat large batches and slow feedback, almost without exception. It's the closest thing delivery work has to a law of physics, and it shows up everywhere once you look: commit size, release cadence, test-cycle length, review turnaround, even how often leaders check in on an initiative.

Why it holds:

- **Defect cost compounds with delay.** A problem found in minutes is a fix; found in weeks it's an investigation, a re-learning of context, and often a negotiation about whose problem it is.
- **Big batches hide risk.** A hundred changes tested together give you one pass/fail signal for a hundred hypotheses. You learn almost nothing about *which* change did the damage.
- **Little's Law does the math**: average WIP = throughput × cycle time. When everything "feels slow," either WIP is too high or throughput dropped — usually both, and usually because batches grew.

Gene Kim's Second Way (from *The Phoenix Project*) generalizes it: amplify feedback loops right-to-left so problems surface immediately, not weeks later — which is most of the actual argument for shift-left testing, expressed as flow rather than as a slogan.

Related:

- [[theory-of-constraints]] — small batches make the real constraint visible
- [[build-quality-in]] — end-of-line inspection is a large batch of feedback, delivered late
- [[measure-outcomes-not-activity]] — lead time and deploy frequency are batch-size metrics in disguise
