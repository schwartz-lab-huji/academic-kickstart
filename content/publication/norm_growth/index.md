---
title: "Effects of Parameter Norm Growth During Transformer Training: Inductive Bias from Gradient Descent"
authors:
- will
- vivek
- yoav
- me
- noah
publication_types: ["1"]
Date: 2021-09-09
publishDate: 2021-09-09T00:00:00Z
publication: In *Proc. of EMNLP 2021*
abstract: 'The capacity of neural networks like the widely adopted transformer is known to be very high. Evidence is emerging that they learn successfully due to inductive bias in the training routine, typically a variant of gradient descent (GD). To better understand this bias, we study the tendency for transformer parameters to grow in magnitude (l2 norm) during training, and its implications for the emergent representations within self attention layers. Empirically, we document norm growth in the training of transformer language models, including T5 during its pretraining. As the parameters grow in magnitude, we prove that the network approximates a discretized network with saturated activation functions. Such "saturated" networks are known to have a reduced capacity compared to the full network family that can be described in terms of formal languages and automata. Our results suggest saturation is a new characterization of an inductive bias implicit in GD of particular interest for NLP. We leverage the emergent discrete structure in a saturated transformer to analyze the role of different attention heads, finding that some focus locally on a small number of positions, while other heads compute global averages, allowing counting. We believe understanding the interplay between these two capabilities may shed further light on the structure of computation within large transformers.'

tags:
- understanding_models 
links:
url_pdf: 'https://arxiv.org/abs/2010.09697'
url_code: 'https://github.com/viking-sudo-rm/norm-growth'
---
