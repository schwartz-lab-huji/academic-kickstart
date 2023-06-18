---
title: 'Morphosyntactic Probing of Multilingual BERT Models'
authors: 
- Judit Acs
- Endre Hamerlik
- me
- noah
- Andras Kornai

abstract: 'We introduce an extensive dataset for multilingual probing of morphological information in language models (247 tasks across 42 languages from 10 families), each consisting of a sentence with a target word and a morphological tag as the desired label, derived from the Universal Dependencies treebanks. We find that pre-trained Transformer models (mBERT and XLM-RoBERTa) learn features that attain strong performance across these tasks. We then apply two methods to locate, for each probing task, where the disambiguating information resides in the input. The first is a new perturbation method that "masks" various parts of context; the second is the classical method of Shapley values. The most intriguing finding that emerges is a strong tendency for the preceding context to hold more information relevant to the prediction than the following context.'

publication_types: ["2"]
Date: 2023-03-01
publishDate: 2023-05-25
publication: In *Natural Language Engineering 2023*
links:
url_pdf: 'https://www.cambridge.org/core/journals/natural-language-engineering/article/morphosyntactic-probing-of-multilingual-bert-models/8C0D539D3F11FB188AB73228BA7F5805'
url_code: 'https://github.com/juditacs/morphology-probes'


tags:
- 'understanding_models'
---



