---
title: "Transformers are Multi-State RNNs"
news: '<a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://www.marktechpost.com/2024/01/15/this-ai-paper-demonstrates-how-decoder-only-transformers-mimic-infinite-multi-state-recurrent-neural-networks-rnns-and-introduces-tova-for-enhanced-efficiency/"  target="_blank" rel="noopener noreferrer">MarkTechPost</a>'

authors:
- matanelstar
- michael_hassidstar
- yossi_adi
- me
publication_types: ["3"]
Date: 2024-01-12
publishDate: 2024-01-12T00:00:00Z
publication: <i>arXiv:2401.06104</i>

abstract: 'Transformers are considered conceptually different compared to the previous generation of state-of-the-art NLP models - recurrent neural networks (RNNs). In this work, we demonstrate that decoder-only transformers can in fact be conceptualized as infinite multi-state RNNs - an RNN variant with unlimited hidden state size. We further show that pretrained transformers can be converted into finite multi-state RNNs by fixing the size of their hidden state. We observe that several existing transformers cache compression techniques can be framed as such conversion policies, and introduce a novel policy, TOVA, which is simpler compared to these policies. Our experiments with several long range tasks indicate that TOVA outperforms all other baseline policies, while being nearly on par with the full (infinite) model, and using in some cases only 18 of the original cache size. Our results indicate that transformer decoder LLMs often behave in practice as RNNs. They also lay out the option of mitigating one of their most painful computational bottlenecks - the size of their cache memory. We publicly release our code.'

tags:
- greenai
- understanding_models 


links:
url_pdf: 'https://arxiv.org/abs/2401.06104'
url_project: 'https://github.com/schwartz-lab-NLP/TOVA'

---
