---
layout: default2
permalink: /competition/
title: Call for Competition
nav: true
nav_order: 3
---

### Competition

**Proposed competition, subject to workshop acceptance.**

Can a model's task reasoning remain robust when contextual signals strongly correlated during training become unreliable at test time? This competition is a focused empirical case study of separating task-relevant computation from unreliable contextual information under distribution shift.

We adapt the [code-execution dataset](https://huggingface.co/datasets/plstcharles-saifh/pyine-v1-traces) with contextual labels and attributes. Systems must infer when to trust, ignore, or discount contextual cues while predicting the correct execution outcome of a Python program.

The benchmark will include helpful, misleading, and shifted contexts. We welcome prompting, retrieval or external verification, modular architectures, fine-tuning, and other training strategies. The benchmark is one instance of the broader coupling problem, rather than a complete test of decoupled intelligence.

### Submission and Evaluation

Submit a reproducible system, ideally including:

- A hosted Hugging Face model checkpoint
- Open-source training and inference code
- A two-page summary of the approach

Final evaluation uses a private withheld test set and reports predictive performance together with efficiency or cost metrics. Rankings also consider reproducibility and scientific insight. Detailed metrics, leaderboard, starter kit, and submission instructions will be announced at launch.

### Eligibility

Organizers and anyone with access to the private test set are ineligible for awards. Organizer baselines will appear only as reference entries.

Members of the organizers' institutions may participate, but their entries will be assessed only by organizers from other institutions.

### Tentative Timeline

All deadlines are Anywhere on Earth (AoE), subject to workshop acceptance.

- December 15, 2026: competition launch, training and validation data, starter kit, and public leaderboard
- March 1, 2027: final submission deadline for the reproducible system and two-page summary
- March 22, 2027: private-test evaluation complete; finalists and winners notified
- April 29 or 30, 2027: workshop and winner presentations (exact day TBD)

Winners unable to travel in exceptional circumstances may provide a pre-recorded talk. Competition data, leaderboard, and winning systems' code and checkpoints will remain publicly available after the workshop.
