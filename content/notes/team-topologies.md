---
title: Team Topologies
description: Four team shapes, three interaction modes — a vocabulary for designing teams on purpose.
tags:
  - budding
  - org-design
---

From Skelton & Pais. Almost every healthy team fits one of four shapes, and mixing shapes inside one team creates confusion about what the team is *for*:

- **Stream-aligned** — owns a slice of the domain end-to-end, minimal hand-offs. The default; everything else exists to serve these.
- **Platform** — provides self-service capability that reduces cognitive load for stream-aligned teams (test frameworks, test data, CI/CD).
- **Enabling** — temporarily builds a missing capability in another team, then *steps back*.
- **Complicated-subsystem** — owns one narrow, genuinely complex component.

Plus three interaction modes: **collaboration** (working closely for a period), **X-as-a-service** (consume with minimal contact — the target state for a mature platform), and **facilitating** (coaching).

The trap I watch for is the **permanent enabler**: an enabling relationship that never ends has quietly become a platform or complicated-subsystem team while still being called "enabling" — and the capability transfer it was supposed to make has silently failed. The test: is the receiving team getting more self-sufficient over time, or not?

A platform team has its own failure mode: without a real charter, backlog, and adoption metrics, it reverts to a ticket queue nobody's accountable for. Platform-as-a-product is the antidote — treat internal consumers as customers.

Related:

- [[conways-law|Conway's Law]] — the reason team shape matters at all
- [[build-quality-in|Build quality in]] — embedded QE + a platform pod is this vocabulary applied to quality
