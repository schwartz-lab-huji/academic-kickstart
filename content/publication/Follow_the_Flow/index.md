---
title: "Follow the Flow: On Information Flow Across Textual Tokens in Text-to-Image Models"

authors:
- Guy Kaplan*
- Michael Toker*
- yuval_reif
- Yonatan Belinkov
- me

publication_types: ["1"]
Date: 2025-04-04
publishDate: 2025-04-0400:00:00Z
publication: In <i>Proc. of ACL 2026</i>

abstract: "Text-to-image generation models suffer from alignment problems, where generated images fail to accurately capture the objects and relations in the text prompt. Prior work has focused on improving alignment by refining the diffusion process, ignoring the role of the text encoder, which guides the diffusion. In this work, we investigate how semantic information is distributed across token representations in text-to-image prompts, analyzing it at two levels: (1) in-item representation-whether individual tokens represent their lexical item (i.e., a word or expression conveying a single concept), and (2) cross-item interaction-whether information flows between tokens of different lexical items. We use patching techniques to uncover encoding patterns, and find that information is usually concentrated in only one or two of the item's tokens; for example, in the item ''San Francisco's Golden Gate Bridge'', the token ''Gate'' sufficiently captures the entire expression while the other tokens could effectively be discarded. Lexical items also tend to remain isolated; for instance, in the prompt ''a green dog'', the token ''dog'' encodes no visual information about ''green''. However, in some cases, items do influence each other's representation, often leading to misinterpretations-e.g., in the prompt ''a pool by a table'', the token ''pool'' represents a ''pool table'' after contextualization. Our findings highlight the critical role of token-level encoding in image generation, and demonstrate that simple interventions at the encoding stage can substantially improve alignment and generation quality."

links:
url_pdf: "https://arxiv.org/abs/2504.01137"
url_code: "https://github.com/tokeron/lens"
url_project: "https://guykap12.github.io/guykap12.github.io-follow_the_flow/"
---
