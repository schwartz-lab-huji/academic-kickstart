---
title: "Data Contamination: From Memorization to Exploitation"
authors:
- inbal
- me
publication_types: ["1"]
Date: 2022-03-05
publishDate: 2022-03-05T00:00:00Z
publication: In *Proc. of ACL 2022*
abstract: 'Pretrained language models are typically trained on massive web-based datasets, which are often “contaminated” with downstream test sets. It is not clear to what extent models exploit the contaminated data for downstream tasks. We present a principled method to study this question. We pretrain BERT models on joint corpora of Wikipedia and labeled downstream datasets, and fine-tune them on the relevant task. Comparing performance between samples seen and unseen during pretraining enables us to define and quantify levels of memorization and exploitation. Experiments with two models and three downstream tasks show that exploitation exists in some cases, but in others the models memorize the contaminated data, but do not exploit it. We show that these two measures are affected by different factors such as the number of duplications of the contaminated data and the model size. Our results highlight the importance of analyzing massive web-scale datasets to verify that progress in NLP is obtained by better language understanding and not better data exploitation.'
tags:
- improved_evaluation

links:
url_pdf: 'http://arxiv.org/abs/2203.08242'
url_code: 'https://github.com/schwartz-lab-NLP/data_contamination'
---
