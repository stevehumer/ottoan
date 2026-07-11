---
title: Conway's Law
description: Organizations ship their communication structure, whether they mean to or not.
tags:
  - budding
  - org-design
---

Organizations design systems that mirror their own communication structure. Teams that don't talk end up owning components that don't integrate cleanly — and vice versa. Your org chart becomes your architecture whether you plan it or not.

The actionable version is the **Inverse Conway Maneuver**: instead of reorganizing to match whatever architecture accumulated by accident, deliberately design the team structure you want the architecture to converge toward. Team boundaries are architecture decisions wearing an HR costume.

For quality work this cuts deep. Where the test-ownership boundaries sit *is* the quality architecture: a central test team that owns "all the testing" produces exactly the integration seams and hand-off defects you'd predict from the communication paths. Embedded quality engineers on stream-aligned teams, supported by a platform pod, produce a different defect profile — because they produce a different conversation graph.

Related:

- [[theory-of-constraints|Theory of Constraints]] — once structure is right, find where the flow actually chokes
- [[small-batches-fast-feedback|Small batches, fast feedback]] — hand-offs between teams are where batches grow and feedback dies
- [[build-quality-in|Build quality in]] — ownership boundaries determine who *can* build quality in
