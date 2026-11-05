---
title: "Beyond State Capacity: Why Retrieval Breaks in Mamba"

authors:
- Nir Yarden
- amit
- me

publication_types: ["3"]
Date: 2026-10-22
publishDate: 2026-10-2200:00:00Z
publication: arXiv:2610.19709

abstract: "Mamba models underperform Transformers on in-context retrieval. This gap is usually attributed to Mamba&#39;s fixed-size recurrent state, which loses information as the context grows. We challenge this assumption by focusing on query-first retrieval, a setup in which the query precedes the context and state capacity should not be the binding constraint. We show that even in this setting Mamba lags substantially behind Transformers, despite its selection mechanism, which was designed to distinguish relevant content from distractors. We then demonstrate that the Mamba selection gates have sufficient control over the state updates to influence the model output: intervening on specific gates alone can swing accuracy between extremes. However, as gates are input-dependent, they require the incoming token&#39;s representation to encode its relevance to the query. We therefore probe token representations across layers, and find that the relevance signal emerges only gradually with model depth, and that the gates begin to reflect it only several layers deeper. Crucially, we find that gates in retrieval-critical layers are not yet aligned with relevance. The selection mechanism is thus expressive enough to solve the task, but it commonly operates on a relevance signal that has not yet arrived. Mamba&#39;s retrieval bottleneck therefore extends beyond state capacity: even when capacity is sufficient, the delayed emergence of relevance information across depth often prevents successful retrieval."

links:
url_pdf: "https://arxiv.org/abs/2610.19709"
---
