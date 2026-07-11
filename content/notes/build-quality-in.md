---
title: Build quality in, don't inspect it in
description: Quality is a property of how work gets done, not a gate at the end.
tags:
  - budding
  - quality
---

Deming's third point (from *Out of the Crisis*): cease dependence on inspection to achieve quality. A gate at the end of the line catches defects **after** they're expensive to fix — and as the number of teams grows, the gate becomes the bottleneck long before it becomes effective.

The alternative isn't "less testing." It's making good practice cheap and automatic so quality becomes a property of *how the work gets done*: self-service test automation, shift-left testing, standardized exit criteria that live inside the workflow rather than beside it.

This reframes what a quality engineering organization is *for*. QE-as-gate inspects other people's output and inherits the blame for whatever slips through. QE-as-enabler builds the platforms, practices, and skills that let delivery teams own their own quality — which is the only version that scales.

Two ideas make this workable in practice:

- [[mechanisms-not-memos]] — built-in quality has to be the default path, not a plea
- [[measure-outcomes-not-activity]] — you'll know it's working from escape rates and cycle time, not test-case counts

And one idea explains why the gate fails structurally, not just economically: a gate is a hand-off, and [[small-batches-fast-feedback|slow feedback across hand-offs]] is where defects go to compound.
