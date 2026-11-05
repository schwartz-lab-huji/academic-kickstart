---
title: "Post-training is (Massive) Supervised Learning"

authors:
- michael_hassid
- yossi_adi
- me

publication_types: ["3"]
Date: 2026-06-09
publishDate: 2026-06-0900:00:00Z
publication: arXiv:2606.07527

abstract: "The prevailing paradigm for training LLMs has evolved to rely on a massive post-training phase consisting of SFT and RL. In this position paper, we argue that this methodology effectively marks a reversion to the ''pre-train then fine-tune'' approach of the BERT era, explicitly tailoring models to the desired behaviors and specific benchmarks on which they are evaluated. We begin with a historical overview of LLMs, describing the different phases of the LLM evolution. We argue that the current landscape is remarkably similar to the early days of LLMs, where task performance heavily relied on fitting the models to in-distribution datasets. To empirically demonstrate this, we compare pre-trained models to randomly initialized ones, by fine-tuning both variants on modern reasoning datasets and evaluating them on competitive math and code benchmarks. We show that models post-trained from scratch yield highly non-trivial performance. Our findings suggest that current post-training methodologies function primarily as a distribution-fitting mechanism. We finish by positing that developing generally capable models and systems requires moving beyond extensive post-training for predefined behaviors, shifting instead toward training procedures where models ''learn how to learn''."

links:
url_pdf: "https://arxiv.org/abs/2606.07527"
---
