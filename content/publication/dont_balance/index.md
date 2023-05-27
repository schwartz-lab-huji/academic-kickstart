---
title: "On the Limitations of Dataset Balancing: The Lost Battle Against Spurious Correlations"
authors:
- me
- gabi
publication_types: ["1"]
Date: 2022-04-07
publishDate: 2022-04-04T00:00:00Z
publication: In *Findings of NAACL 2022*
abstract: 'Recent work has shown that deep learning models in NLP are highly sensitive to low-level correlations between simple features and specific output labels, leading to overfitting and lack of generalization. To mitigate this problem, a common practice is to balance datasets by adding new instances or by filtering out "easy" instances (Sakaguchi et al., 2020), culminating in a recent proposal to eliminate single-word correlations altogether (Gardner et al., 2021). In this opinion paper, we identify that despite these efforts, increasingly-powerful models keep exploiting ever-smaller spurious correlations, and as a result even balancing all single-word features is insufficient for mitigating all of these correlations. In parallel, a truly balanced dataset may be bound to "throw the baby out with the bathwater" and miss important signal encoding common sense and world knowledge. We highlight several alternatives to dataset balancing, focusing on enhancing datasets with richer contexts, allowing models to abstain and interact with users, and turning from large-scale fine-tuning to zero- or few-shot setups.'

tags:
- improved_evaluation 

links:
url_pdf: 'http://arxiv.org/abs/2204.12708'
#url_slides: 'https://homes.cs.washington.edu/~hapeng/slides/peng2018rational.pdf'
#url_code: 'https://github.com/Noahs-ARK/rational-recurrences'
#url_video: 'https://vimeo.com/305209046'
---
