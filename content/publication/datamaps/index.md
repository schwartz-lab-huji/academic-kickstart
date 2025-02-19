---
title: "Dataset Cartography: Mapping and Diagnosing Datasets with Training Dynamics"
authors:
- swabha
- me
- nicholas
- yizhong
- hannaneh
- noah
- yejin

publication_types: ["1"]
Date: 2020-09-14
publishDate: 2020-09-01T00:00:00Z
publication: In *Proc. of EMNLP 2020*
abstract: "Large datasets have become commonplace in NLP research. However, the increased emphasis on data quantity has made it challenging to assess the quality of data. We introduce \"Data Maps\"---a model-based tool to characterize and diagnose datasets. We leverage a largely ignored source of information: the behavior of the model on individual instances during training (training dynamics) for building data maps. This yields two intuitive measures for each example---the model's confidence in the true class, and the variability of this confidence across epochs, in a single run of training. Experiments on four datasets show that these model-dependent measures reveal three distinct regions in the data map, each with pronounced characteristics. First, our data maps show the presence of \"ambiguous\" regions with respect to the model, which contribute the most towards out-of-distribution generalization. Second, the most populous regions in the data are \"easy to learn\" for the model, and play an important role in model optimization. Finally, data maps uncover a region with instances that the model finds \"hard to learn\"; these often correspond to labeling errors. Our results indicate that a shift in focus from quantity to quality of data could lead to robust models and improved out-of-distribution generalization."
tags:
- improved_evaluation
- greenai
links:
url_code: 'https://github.com/allenai/cartography'
url_pdf: 'https://arxiv.org/abs/2009.10795'
url_video: 'https://slideslive.com/38939175/dataset-cartography-mapping-and-diagnosing-datasets-with-training-dynamics'
#url_poster: 'poster.pdf'


---
