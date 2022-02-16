---
title: "Data Efficient Masked Language Modeling for Vision and Language"
authors:
- yonatanbitton
- gabi
- elhadad
- me
publication_types: ["1"]
Date: 2021-09-05
publishDate: 2021-09-05T00:00:00Z
publication: In *Findings of EMNLP 2021*
tags:
- greenai
abstract: "Masked language modeling (MLM) is one of the key sub-tasks in vision-language pretraining. In the cross-modal setting, tokens in the sentence are masked at random, and the model predicts the masked tokens given the image and the text. In this paper, we observe several key disadvantages of MLM in this setting. First, as captions tend to be short, in a third of the sentences no token is sampled. Second, the majority of masked tokens are stop-words and punctuation, leading to under-utilization of the image. We investigate a range of alternative masking strategies specific to the cross-modal setting that address these shortcomings, aiming for better fusion of text and image in the learned representation. When pre-training the LXMERT model, our alternative masking strategies consistently improve over the original masking strategy on three downstream tasks, especially in low resource settings. Further, our pre-training approach substantially outperforms the baseline model on a prompt-based probing task designed to elicit image objects. These results and our analysis indicate that our method allows for better utilization of the training data." 


links:
url_pdf: 'https://arxiv.org/abs/2109.02040'
url_code: 'https://github.com/yonatanbitton/data_efficient_masked_language_modeling_for_vision_and_language'
url_video: 'https://www.youtube.com/watch?v=A-KOkb5CURA'
url_poster: 'https://yonatanbitton.github.io/publication/contrast_sets/contrast_sets_poster.pdf'
---
