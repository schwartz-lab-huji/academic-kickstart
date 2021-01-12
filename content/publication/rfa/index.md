---
title: "Random Feature Attention"
authors:
- hao
- lingpeng
- nikos
- dani
- me
- noah
publication_types: ["1"]
Date: 2021-01-12
publishDate: 2020-05-04T00:00:00Z
publication: In *Proc. of ICLR 2021* <span style="color:red">Spotlight presentation</span>
abstract: "Transformers are state-of-the-art models for a variety of sequence modeling tasks. At their core is an attention function which models pairwise interactions between the inputs at every timestep.  While attention is powerful, it doesnot scale efficiently to long sequences due to its quadratic time and space complexity in the sequence length.   We propose  RFA,  a linear time and space attention that uses random feature methods to approximate the softmax function, and explore its applications  in  transformers.   RFA offers  a  straightforward  way  of  learning  with recency bias through an optional gating mechanism and can be used as a drop-in replacement for conventional softmax attention. Experiments on language modeling and machine translation demonstrate that RFA achieves similar or better performance compared to strong transformer baselines.  In the machine translation experiment, RFA decodes twice as fast as a vanilla transformer. Compared to existing efficient transformer variants, RFA is competitive in terms of both accuracy and efficiency on three long text classification datasets.   Our analysis shows that RFA's efficiency gains are especially notable on long sequences, suggesting that RFA will be particularly useful in tasks that require working with large inputs, fast decoding speed, or low memory footprints."
tags:
- greenai
- understanding_models

links:
url_pdf: 'https://openreview.net/pdf?id=QtTKTdVrFBB'
---
