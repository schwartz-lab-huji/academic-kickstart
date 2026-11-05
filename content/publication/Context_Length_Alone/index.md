---
title: "Context Length Alone Hurts LLM Performance Despite Perfect Retrieval"

authors:
- Yufeng Du
- Minyang Tian
- Srikanth Ronanki
- Subendhu Rongali
- Sravan Bodapati
- Aram Galstyan
- Azton Wells
- me
- Eliu A Huerta
- hao

publication_types: ["1"]
Date: 2025-10-08
publishDate: 2025-10-0800:00:00Z
publication: In *Findings of EMNLP 2025*

abstract: "Large language models (LLMs) often fail to scale their performance on long-context tasks performance in line with the context lengths they support. This gap is commonly attributed to retrieval failures -- the models&#39; inability to identify relevant information in the long inputs. Accordingly, recent efforts often focus on evaluating and improving LLMs&#39; retrieval performance: if retrieval is perfect, a model should, in principle, perform just as well on a long input as it does on a short one -- or should it? This paper presents findings that the answer to this question may be negative. Our systematic experiments across 5 open- and closed-source LLMs on math, question answering, and coding tasks reveal that, even when models can perfectly retrieve all relevant information, their performance still degrades substantially (13.9%--85%) as input length increases but remains well within the models&#39; claimed lengths. This failure occurs even when the irrelevant tokens are replaced with minimally distracting whitespace, and, more surprisingly, when they are all masked and the models are forced to attend only to the relevant tokens. A similar performance drop is observed when all relevant evidence is placed immediately before the question. Our findings reveal a previously-unrealized limitation: the sheer length of the input alone can hurt LLM performance, independent of retrieval quality and without any distraction. They motivate our simple, model-agnostic mitigation strategy that transforms a long-context task into a short-context one by prompting the model to recite the retrieved evidence before attempting to solve the problem. On RULER, we observe a consistent improvement of GPT-4o up to 4% on an already strong baseline."

links:
url_pdf: "https://arxiv.org/abs/2510.05381"
---
