---
title: "Transformers are Multi-State RNNs"
news: '<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://www.marktechpost.com/2024/01/15/this-ai-paper-demonstrates-how-decoder-only-transformers-mimic-infinite-multi-state-recurrent-neural-networks-rnns-and-introduces-tova-for-enhanced-efficiency/"  target="_blank" rel="noopener noreferrer">MarkTechPost</a>'

authors:
- matanelstar
- michael_hassidstar
- nir_yarden
- yossi_adi
- me
publication_types: ["3"]
Date: 2024-01-12
publishDate: 2024-01-12T00:00:00Z
publication: <i>arXiv:2401.06104</i>

abstract: "Transformers are considered conceptually different from the previous generation of state-of-the-art NLP models - recurrent neural networks (RNNs). In this work, we demonstrate that decoder-only transformers can in fact be conceptualized as unbounded multi-state RNNs - an RNN variant with unlimited hidden state size. We further show that transformers can be converted into bounded multi-state RNNs by fixing the size of their hidden state, effectively compressing their key-value cache. We introduce a novel, training-free compression policy - Token Omission Via Attention (TOVA). Our experiments with four long range tasks and several LLMs show that TOVA outperforms several baseline compression policies. Particularly, our results are nearly on par with the full model, using in some cases only 18 of the original cache size, which translates to 4.8X higher throughput. Our results shed light on the connection between transformers and RNNs, and help mitigate one of LLMs' most painful computational bottlenecks - the size of their key-value cache. We publicly release our code."

tags:
- greenai
- understanding_models 


links:
url_pdf: 'https://arxiv.org/abs/2401.06104'
url_project: 'https://github.com/schwartz-lab-NLP/TOVA'

---
