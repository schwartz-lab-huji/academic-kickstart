---
title: "Fighting Bias with Bias: Promoting Model Robustness by Amplifying Dataset Biases"
authors:
- yuval_reif
- me
publication_types: ["1"]
Date: 2023-05-03
publishDate: 2023-05-03T00:00:00Z
publication: In *Findings of ACL 2023*
abstract: 'NLP models often rely on superficial cues known as dataset biases to achieve impressive performance, and can fail on examples where these biases do not hold. Recent work sought to develop robust, unbiased models by filtering biased examples from training sets. In this work, we argue that such filtering can obscure the true capabilities of models to overcome biases, which might never be removed in full from the dataset. We suggest that in order to drive the development of models robust to subtle biases, dataset biases should be amplified in the training set. We introduce an evaluation framework defined by a bias-amplified training set and an anti-biased test set, both automatically extracted from existing datasets. Experiments across three notions of bias, four datasets and two models show that our framework is substantially more challenging for models than the original data splits, and even more challenging than hand-crafted challenge sets. Our evaluation framework can use any existing dataset, even those considered obsolete, to test model robustness. We hope our work will guide the development of robust models that do not rely on superficial biases and correlations. To this end, we publicly release our code and data.'
tags:
- improved_evaluation


links:
url_pdf: 'https://arxiv.org/abs/2305.18917'
url_code: 'https://github.com/schwartz-lab-NLP/fight-bias-with-bias'

---
