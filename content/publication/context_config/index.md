---
title: "Automatic selection of context configurations for improved (and fast) class-specific word representations"
authors:
- ivan
- me
- ari
- roi
- annak
publication_types: ["1"]
Date: 2017-07-01
publishDate: 2020-04-01T00:00:00Z
publication: In *Proc. of CoNLL 2017*
abstract: "This paper is concerned with identifying contexts useful for training word representation models for different word classes such as adjectives (A), verbs (V), and nouns (N). We introduce a simple yet effective framework for an automatic selection of class-specific context configurations. We construct a context configuration space based on universal dependency relations between words, and efficiently search this space with an adapted beam search algorithm. In word similarity tasks for each word class, we show that our framework is both effective and efficient. Particularly, it improves the Spearman's rho correlation with human scores on SimLex-999 over the best previously proposed class-specific contexts by 6 (A), 6 (V) and 5 (N) rho points. With our selected context configurations, we train on only 14% (A), 26.2% (V), and 33.6% (N) of all dependency-based contexts, resulting in a reduced training time. Our results generalise: we show that the configurations our algorithm learns for one English training setup outperform previously proposed context types in another training setup for English. Moreover, basing the configuration space on universal dependencies, it is possible to transfer the learned configurations to German and Italian. We also demonstrate improved per-class results over other context types in these two languages."
tags:
- word_representations
links:
url_pdf: 'http://arxiv.org/abs/1608.05528'
url_slides: 'papers/context_config/context_config_slides.pdf'
---
