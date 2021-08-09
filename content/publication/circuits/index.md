---
title: "On the Power of Saturated Transformers: A View from Circuit Complexity"
authors:
- will
- yoav
- me
- noah
publication_types: ["3"]
Date: 2021-07-01
publishDate: 2021-07-01T00:00:00Z
abstract: "Transformers have become a standard architecture for many NLP problems. This has motivated theoretically analyzing their capabilities as models of language, in order to understand what makes them successful, and what their potential weaknesses might be. Recent work has shown that transformers with hard attention are quite limited in capacity, and in fact can be simulated by constant-depth circuits. However, hard attention is a restrictive assumption, which may complicate the relevance of these results for practical transformers. In this work, we analyze the circuit complexity of transformers with saturated attention: a generalization of hard attention that more closely captures the attention patterns learnable in practical transformers. We show that saturated transformers transcend the limitations of hard-attention transformers. With some minor assumptions, we prove that the number of bits needed to represent a saturated transformer memory vector is O(logn), which implies saturated transformers can be simulated by log-depth circuits. Thus, the jump from hard to saturated attention can be understood as increasing the transformer's effective circuit depth by a factor of O(logn)." 
tags:
- understanding_models 
links:
url_pdf: 'https://arxiv.org/abs/2106.16213'
---
