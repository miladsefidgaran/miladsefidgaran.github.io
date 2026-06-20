---
layout: page
title: research
permalink: /research/
description: Generalization in machine learning, and what it tells us about large language models.
nav: true
nav_order: 2
---

Most of my work comes back to a single question: can we understand generalization well enough to actually do something with it? In recent years that question has pulled me toward the foundations of large language models.

### Generalization of modern learning

I work on generalization bounds that stay meaningful for the large, overparameterized models people actually use, including data-dependent bounds and ones based on conditional mutual information. Lately this has grown to include the algorithms behind language models themselves, such as next-token prediction.

Related: generalization of next-token prediction (ISIT 2026); projection and quantization (NeurIPS 2025, oral); variable-size compressibility (IEEE T-IT 2024).

### Representation learning and information-theoretic priors

I look at how to shape a model's latent space using priors learned from the data, so that the representations are both more useful and easier to give guarantees for. This turns out to be closely tied to how language models organize their own representation spaces.

Related: Gaussian mixture priors (ICLR 2025, spotlight); minimum description length guarantees (NeurIPS 2023).

### Compression, quantization, and efficient models

A recurring theme in my work is how far you can compress a model, through projection and quantization, before it starts to lose the ability to generalize. This is the theory side of making large models cheaper to run.

Related: projection and quantization (NeurIPS 2025, oral); heavy tails in SGD and compressibility (NeurIPS 2021).

### Distributed and federated learning

I have spent a good deal of time on what communication really buys you when training is spread across many machines. One result I am fond of is that communicating less often can sometimes give better generalization, not worse.

Related: you may communicate less often (ICML 2024); rate-distortion bounds for distributed learning (NeurIPS 2022); clients and server communication (IEEE T-IT 2026).

### Current directions

Right now I am working on inference-time methods that make use of the representation spaces of large language models, and on diversity-aware zero-shot reinforcement learning. Papers on both are in preparation.