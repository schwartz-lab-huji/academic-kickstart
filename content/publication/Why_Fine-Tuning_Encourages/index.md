---
title: "Why Fine-Tuning Encourages Hallucinations and How to Fix It"

authors:
- guy_kaplan
- Zorik Gekhman
- Zhen Zhu
- Lotem Rozner
- yuval_reif
- swabha
- Derek Hoiem
- me

publication_types: ["1"]
Date: 2026-04-23
publishDate: 2026-04-2300:00:00Z
publication: In <i>Proc. of COLM 2026</i>

abstract: "Large language models are prone to hallucinating factually incorrect statements. A key source of these errors is exposure to new factual information through supervised fine-tuning (SFT), which can increase hallucinations w.r.t. knowledge acquired during pre-training. In this work, we explore whether SFT-induced hallucinations can be mitigated using established tools from the continual learning literature, since they arise as a by-product of knowledge degradation during training. We propose a self-distillation-based SFT method that facilitates effective factual learning while minimizing hallucinations w.r.t. pre-existing knowledge by regularizing output-distribution drift. We also show that, in settings where new knowledge acquisition is unnecessary, suppressing factual plasticity by freezing parameter groups, can preserve task performance while reducing hallucinations. Lastly, we investigate the mechanism behind SFT-induced hallucinations through three hypotheses: capacity limitations, behavior cloning, and localized interference. Our experiments show that a main driver is interference among overlapping semantic representations, and that self-distillation succeeds by mitigating this interference."

links:
url_pdf: "https://arxiv.org/abs/2604.15574"
---
