---
title: "Fine-Tuning Pretrained Language Models: Weight Initializations, Data Orders, and Early Stopping"
authors:
- jesse
- gabrielh
- me
- ali
- hannaneh
- noah
publication_types: ["3"]
Date: 2020-02-01
publishDate: 2020-02-01T00:00:00Z
abstract: "Fine-tuning pretrained contextual word embedding models to supervised downstream tasks has become commonplace in natural language processing. This process, however, is often brittle: even with the same hyperparameter values, distinct random seeds can lead to substantially different results. To better understand this phenomenon, we experiment with four datasets from the GLUE benchmark, fine-tuning BERT hundreds of times on each while varying only the random seeds. We find substantial performance increases compared to previously reported results, and we quantify how the performance of the best-found model varies as a function of the number of fine-tuning trials. Further, we examine two factors influenced by the choice of random seed: weight initialization and training data order. We find that both contribute comparably to the variance of out-of-sample performance, and that some weight initializations perform well across all tasks explored. On small datasets, we observe that many fine-tuning trials diverge part of the way through training, and we offer best practices for practitioners to stop training less promising runs early. We publicly release all of our experimental data, including training and validation scores for 2,100 trials, to encourage further analysis of training dynamics during fine-tuning."
tags:
- greenai
links:
url_pdf: 'https://arxiv.org/abs/2002.06305'
---
