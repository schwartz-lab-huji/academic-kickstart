---
title: "The Larger the Better? Improved LLM Code-Generation via Budget Reallocation"

authors:
- michael_hassidstar
- Tal Remez*
- Jonas Gehring
- me
- yossi_adi
publication_types: ["1"]
Date: 2024-04-02
publishDate: 2024-04-02T00:00:00Z
publication: In <i>Proc. of COLM 2024</i>

abstract: 'It is a common belief that large language models (LLMs) are better than smaller-sized ones. However, larger models also require significantly more time and compute during inference. This begs the question: what happens when both models operate under the same budget? (e.g., compute, run-time). To address this question, we analyze code generation LLMs of various sizes and make comparisons such as running a 70B model once vs. generating five outputs from a 13B model and selecting one. Our findings reveal that, in a standard unit-test setup, the repeated use of smaller models can yield consistent improvements, with gains of up to 15% across five tasks. On the other hand, in scenarios where unit-tests are unavailable, a ranking-based selection of candidates from the smaller model falls short of the performance of a single output from larger ones. Our results highlight the potential of using smaller models instead of larger ones, and the importance of studying approaches for ranking LLM outputs.'

tags:
- greenai
- multimodality


links:
url_pdf: 'https://arxiv.org/abs/2404.00725'
url_project: 'https://github.com/slp-rl/budget-realloc'

---
