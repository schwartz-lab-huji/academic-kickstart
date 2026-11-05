---
title: "Vocab Diet: Reshaping the Vocabulary of LLMs with Vector Arithmetic"

authors:
- yuval_reif
- guy_kaplan
- me

publication_types: ["1"]
Date: 2025-10-27
publishDate: 2025-10-2700:00:00Z
publication: In <i>Findings of ACL 2026</i>

abstract: "Large language models (LLMs) often encode word-form variation (e.g., walk vs. walked) as linear directions in the embedding space. However, standard tokenization algorithms treat such variants as distinct words with different vocabulary entries, quickly filling the size-capped token vocabulary with surface-form variation (e.g., walk, walking, Walk) at the expense of diversity and multilingual coverage. We show that many of these variations can be captured by transformation vectors: additive offsets that yield the appropriate word representation when applied to a base form embedding, in both the input and output spaces. Building on this, we propose a compact reshaping of the vocabulary: instead of assigning unique tokens to each surface form, we compose them from shared base form and transformation vectors (e.g., walked is walk+past tense). Our approach is lightweight, keeping the pretrained backbone frozen and only training small adaptation modules. We apply it across five languages and multiple LLMs in both pretraining and post-hoc adaptation, freeing 10-40% of vocabulary slots to be reallocated where tokenization is inefficient. Importantly, we do so while also expanding vocabulary coverage to out-of-vocabulary words, and with minimal impact on downstream performance. Our findings motivate a rethinking of vocabulary design, towards a representation that better matches the underlying structure of language and the practical needs of multilingual coverage."

links:
url_pdf: "https://arxiv.org/abs/2510.17001"
url_project: "https://vocabdiet.github.io"
---
