---
title: "How Much Does Attention Actually Attend? Questioning the Importance of Attention in Pretrained Transformers"
authors:
- michael_hassid
- hao
- Daniel Rotem
- jungo
- Ivan Montero
- noah
- me
publication_types: ["1"]
Date: 2022-10-06
publishDate: 2022-10-06T00:00:00Z
publication: In *Findings of EMNLP 2022*
abstract: 'The attention mechanism is considered the backbone of the widely-used Transformer architecture. It contextualizes the input by computing input-specific attention matrices. We find that this mechanism, while powerful and elegant, is not as important as typically thought for pretrained language models. We introduce PAPA, a new probing method that replaces the input-dependent attention matrices with constant ones&#8212;the average attention weights over multiple inputs. We use PAPA to analyze several established pretrained Transformers on six downstream tasks. We find that without any input-dependent attention, all models achieve competitive performance&#8212;an average relative drop of only 8% from the probing baseline. Further, little or no performance drop is observed when replacing half of the input-dependent attention matrices with constant (input-<i>independent</i>) ones. Interestingly, we show that better-performing models lose more from applying our method than weaker models, suggesting that the utilization of the input-dependent attention mechanism might be a factor in their success. Our results motivate research on simpler alternatives to input-dependent attention, as well as on methods for better utilization of this mechanism in the Transformer architecture.'
tags:
- understanding_models


links:
url_pdf: 'https://arxiv.org/abs/2211.03495'
url_code: 'https://github.com/schwartz-lab-NLP/papa'
news: <a class="btn btn-outline-primary my-1 mr-1 btn-sm" href="https://thegradientpub.substack.com/i/85832049/research-highlight-how-much-does-attention-actually-attend" target="_blank" rel="noopener noreferrer">The Gradient Pub</a>

---
