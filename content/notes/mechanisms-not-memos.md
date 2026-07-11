---
title: Mechanisms, not memos
description: If you want a behavior to happen consistently, build a process that makes it the default — don't rely on people remembering to care.
tags:
  - budding
  - leadership
  - quality
---

An Amazon leadership idiom: good intentions don't scale, mechanisms do. If you want a behavior to happen consistently, build a process that makes it the *default path* — don't send a memo asking people to remember or care enough.

A memo says "please keep the regression suite current." A mechanism folds suite-currency into the exit-criteria checklist so a story isn't done until the tests moved with it. Same goal; only one of them still works when everyone is busy, new people join, and the original author leaves.

The test for whether you have a mechanism or a memo: **what happens when nobody is paying attention?** If the behavior degrades, it was a memo.

Two cautions I want to hold onto:

- A mechanism nobody believes in becomes compliance theater — the checklist gets ticked without the work behind it. Mechanisms need [[psychological-safety|psychological safety]] underneath them, or people optimize for passing the check rather than surfacing the truth.
- Mechanisms encode *today's* understanding. Every one needs an owner and a review trigger, or it outlives its reason and becomes bureaucracy with tenure.

Related:

- [[build-quality-in|Build quality in]] — built-in quality is essentially a portfolio of mechanisms
- [[measure-outcomes-not-activity|Measure outcomes, not activity]] — the outcome data tells you whether the mechanism works or just runs
