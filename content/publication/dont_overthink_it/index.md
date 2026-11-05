---
title: "Don't Overthink it. Preferring Shorter Thinking Chains for Improved LLM Reasoning"

authors:
- michael_hassid
- Gabriel Synnaeve
- yossi_adi
- me

publication_types: ["3"]
Date: 2025-05-29
publishDate: 2025-05-2900:00:00Z
publication: arXiv:2505.17813

abstract: "Reasoning large language models (LLMs) heavily rely on scaling test-time compute to perform complex reasoning tasks by generating extensive &#34;thinking&#34; chains. While demonstrating impressive results, this approach incurs significant computational costs and inference time. In this work, we challenge the assumption that long thinking chains results in better reasoning capabilities. We first demonstrate that shorter reasoning chains within individual questions are significantly more likely to yield correct answers - up to 34.5% more accurate than the longest chain sampled for the same question. Based on these results, we suggest short-m@k, a novel reasoning LLM inference method. Our method executes k independent generations in parallel and halts computation once the first m thinking processes are done. The final answer is chosen using majority voting among these m chains. Basic short-1@k demonstrates similar or even superior performance over standard majority voting in low-compute settings - using up to 40% fewer thinking tokens. short-3@k, while slightly less efficient than short-1@k, consistently surpasses majority voting across all compute budgets, while still being substantially faster (up to 33% wall time reduction). Inspired by our results, we finetune an LLM using short, long, and randomly selected reasoning chains. We then observe that training on the shorter ones leads to better performance. Our findings suggest rethinking current methods of test-time compute in reasoning LLMs, emphasizing that longer &#34;thinking&#34; does not necessarily translate to improved performance and can, counter-intuitively, lead to degraded results."

tags:
- greenai

links:
url_pdf: "https://arxiv.org/abs/2505.17813"
---
