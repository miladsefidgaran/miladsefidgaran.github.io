---
layout: page
title: Research
permalink: /research/
nav: true
nav_order: 2
---

*What distinguishes learning from optimization is generalization.*

---

Most of my work comes back to a single question: can we understand generalization well enough to actually do something with it? In recent years, that question has led me toward structured representation learning for vision, large language models, and reinforcement learning.

### Generalization of modern learning algorithms

I work on generalization bounds that remain meaningful for the large, overparameterized models people actually use, including data-dependent bounds and bounds based on conditional mutual information. More recently, this has grown to include the algorithms behind language models themselves, such as next-token prediction.

*Related:* generalization of next-token prediction (ISIT 2026); projection and quantization (NeurIPS 2025, oral); variable-size compressibility (IEEE T-IT 2024).

### Representation learning and information-theoretic priors

I study how to simultaneously learn and shape a model's latent-space structure using priors learned from data throughout optimization. This approach, which guarantees good generalization performance as long as the learned structure remains sufficiently simple, turns out to be closely tied to how large vision and language models organize their own representation spaces.

*Related:* Gaussian mixture priors (ICLR 2025, spotlight); minimum description length guarantees (NeurIPS 2023).

### Compression, quantization, and efficient models

A recurring theme in my work is understanding how far a model can be compressed, through projection and quantization, pruning strategies, or more general lossy compression schemes, and how to enforce such compressibility during training. This is the theory side of making AI models cheaper to deploy and run.

*Related:* projection and quantization (NeurIPS 2025, oral); heavy tails in SGD and compressibility (NeurIPS 2021); minimal communication-cost learning (ISIT 2024).

### Distributed and Federated learning

I have spent a good deal of time studying what communication really buys you when training is distributed across many machines. One result I am particularly fond of is that communicating less often usually leads to better generalization, not worse, and can sometimes even reduce population risk.

*Related:* you may communicate less often (ICML 2024); rate-distortion bounds for distributed learning (NeurIPS 2022); clients and server communication (IEEE T-IT 2026).

### Current directions

My current research focuses on

- inference-time methods that make use of the representation spaces of large language models,
- learning representation structure over (stratified) manifolds and imposing such structure through curvature-aware (geometry-aware) learning algorithms,
- diversity-aware zero-shot reinforcement learning, which exploits the structure of learned representations to guarantee diversity and good coverage at inference time.