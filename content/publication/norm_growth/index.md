---
title: "Parameter Norm Growth During Training of Transformers"
authors:
- will
- vivek
- yoav
- me
- noah
publication_types: ["3"]
Date: 2020-10-20
publishDate: 2020-10-20T00:00:00Z
abstract: "The capacity of neural networks like the widely adopted transformer is known to be very high. Evidence is emerging that they learn successfully due to inductive bias in the training routine, typically some variant of gradient descent (GD). To better understand this bias, we study the tendency of transformer parameters to grow in magnitude during training.  We find, both theoretically and empirically, that, in certain contexts, GD increases the parameter L2 norm up to a threshold that itself increases with training-set accuracy. This means increasing training accuracy over time enables the norm to increase. Empirically, we show that the norm grows continuously over pretraining for T5 (Raffel et al., 2019). We show that pretrained T5 approximates a semi-discretized network with saturated activation functions. Such \"saturated\" networks are known to have a reduced capacity compared to the original network family that can be described in automata-theoretic terms. This suggests saturation is a new characterization of an inductive bias implicit in GD that is of particular interest for NLP. While our experiments focus on transformers, our theoretical analysis extends to other architectures with similar formal properties, such as feedforward ReLU networks."
tags:
- understanding_models 
links:
url_pdf: 'https://arxiv.org/abs/2010.09697'
---
