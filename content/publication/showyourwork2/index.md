---
title: "Expected Validation Performanceand Estimation of a Random Variable's Maximum"
authors:
- jesse
- suchin
- dallas
- me
- noah
publication_types: ["1"]
Date: 2021-09-09
publishDate: 2021-09-09T00:00:00Z
publication: In *Findings of EMNLP 2021*
abstract: "NLP is often supported by experimental results, and improved reporting of such results can lead to better understanding and more reproducible science. In this paper we analyze three statistical estimators for expected validation performance, a tool used for reporting performance (e.g., accuracy) as a function of computational budget (e.g., number of hyperparameter tuning experiments). Where previous work analyzing such estimators focused on the bias, we also examine the variance and mean squared error (MSE). In both synthetic and realistic scenarios, we evaluate three estimators and find the unbiased estimator has the highest variance, and the estimator with the smallest variance has the largest bias; the estimator with the smallest MSE strikes a balance between bias and variance, displaying a classic bias-variance tradeoff. We use expected validation performance to compare between different models, and analyze how frequently each estimator leads to drawing incorrect conclusions about which of two models performs best. We find that the two biased estimators lead to the fewest incorrect conclusions, which hints at the importance of minimizing variance and MSE."
tags:
- greenai
links:
url_pdf: 'https://arxiv.org/abs/2110.00613'
---