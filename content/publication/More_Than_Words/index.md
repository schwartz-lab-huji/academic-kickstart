---
title: "More Than Words: Compositional Tokenization for Efficient Language Models"

authors:
- yuval_reif
- guy_kaplan
- me

publication_types: ["1"]
Date: 2026-10-09
publishDate: 2026-10-0900:00:00Z
publication: In <i>Proc. of COLM 2026 <b>(oral presentation)</b></i>

abstract: "Language models process and generate text sequentially in token units, and the tokenizer determines how much text each inference step covers. Under standard tokenization, a short English phrase such as &#34;On the table.&#34; is usually produced as four separate predictions for the preposition (On), article (the), noun (table), and punctuation (.), where each consumes a sequence position and adds inference cost. We introduce CoBPE, a compositional tokenization approach that represents such phrases as a lexical base token (table) attached with a small set of reusable surface modifiers, composed in embedding space at input and predicted jointly at output. In controlled pretraining from scratch at 780M and 1.3B scales, CoBPE shortens sequences by 30% and improves average downstream performance by 1.2 points relative to standard BPE under matched training compute. Our results suggest that part of what is now expressed through token sequences can instead be modeled through structured representations, opening a broad design space for more token-efficient and capable language models."

links:
url_pdf: "https://arxiv.org/abs/2610.05597"
---
