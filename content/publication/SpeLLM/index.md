---
title: "SpeLLM: Character-Level Multi-Head Decoding"

authors:
- amit
- me

publication_types: ["3"]
Date: 2025-07-28
publishDate: 2025-07-2800:00:00Z
publication: arXiv:2507.16323

abstract: "Scaling LLM vocabulary is often used to reduce input sequence length and alleviate attention&#39;s quadratic cost. Yet, current LLM architectures impose a critical bottleneck to this procedure: the output projection layer scales linearly with vocabulary size, rendering substantial expansion impractical. We propose SpeLLM, a method that decouples input and output vocabularies by predicting character-level strings through multiple output heads. In SpeLLM, each of the <i>k</i> linear heads predicts a single character simultaneously, enabling the model to represent a much larger output space using smaller, independent linear heads. We present a self-distillation approach for converting a standard LLM to a SpeLLM. Our experiments with four pre-trained LLMs show their SpeLLM variants achieve competitive performance on downstream tasks while reducing runtime by 5.1% on average across models. Our approach provides a potential avenue for reducing LLM costs, while increasing support for underrepresented languages and domains."

tags:
- understanding_models

links:
url_pdf: "https://arxiv.org/abs/2507.16323"
url_code: "https://github.com/schwartz-lab-NLP/SpeLLM"
---
