---
title: "Global Divergence, Local Convergence: Representation Geometry in SSMs and Transformers"

authors:
- amit
- me

publication_types: ["1"]
Date: 2026-10-12
publishDate: 2026-10-1200:00:00Z
publication: In <i>Proc. of EMNLP 2026</i>

abstract: "Recent state-space models (SSMs) such as Mamba achieve language modeling performance comparable to transformers despite relying on fundamentally different architectures. This raises an important question: how do these structural differences influence the geometry and functional nature of their internal representations? We study this question through a multi-scale analysis of representations in transformers, SSMs, and hybrid architecture. First, we find that SSMs distribute their representational information evenly across all dimensions, whereas transformer representations are heavily dominated by a single principal direction. By evaluating hybrid architectures, we observe that the representation space becomes increasingly skewed toward a single dominant direction after each attention layer. Next, we explore how the different geometric spread of representations impacts representational capacity through compressibility. Surprisingly, we find that despite their contrasting geometric structures, both architectures exhibit tightly matched effective capacities. We further investigate whether this skewed geometry affects how concepts are encoded. Using rank-constrained probes, we demonstrate that both architectures encode concepts in subspaces of surprisingly similar dimensionality. Furthermore, we demonstrate that the transformers&#39; dominant principal direction does not inherently encode more conceptual information. Finally, we zoom in and examine the alignment between manifolds, either by analyzing representations of specific topics or by looking at the nearest neighborhoods of tokens, and find that they are highly aligned. Ultimately, our analysis suggests that while transformers and SSMs induce different usage of latent space, they display a striking functional convergence at the level of local semantic manifolds."

links:
url_pdf: "https://arxiv.org/abs/2609.08692"
---
