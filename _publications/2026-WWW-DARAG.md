---
title: "DA-RAG: Dynamic Attributed Community Search for Retrieval-Augmented Generation"
collection: publications
permalink: /publication/2026-WWW-DARAG
excerpt: 'This paper proposes DA-RAG, which leverages attributed community search to dynamically extract relevant subgraphs for retrieval-augmented generation, outperforming existing RAG methods by up to 40%.'
date: 2026-01-01
venue: 'The Web Conference 2026 (WWW 2026)'
paperurl: ''
citation: 'Xingyuan Zeng, Zuohan Wu, Yue Wang, Chen Zhang, Quanming Yao, Libin Zheng, Jian Yin. &quot;DA-RAG: Dynamic Attributed Community Search for Retrieval-Augmented Generation.&quot; <i>WWW 2026</i>.'
---

## Abstract

Owing to their unprecedented comprehension capabilities, large language models (LLMs) have become indispensable components of modern web search engines. From a technical perspective, this integration represents retrieval-augmented generation (RAG), which enhances LLMs by grounding them in external knowledge base. A prevalent technical approach in this context is graph-based RAG (G-RAG). However, current G-RAG methodologies frequently underutilize graph topology, predominantly focusing on low-order structures or pre-computed static communities. This limitation affects their effectiveness in addressing dynamic and complex queries.

Thus, we propose DA-RAG, which leverages attributed community search (ACS) to dynamically extract relevant subgraphs based on the queried question. DA-RAG captures high-order graph structures, allowing for the retrieval of self-complementary knowledge. Furthermore, DA-RAG is equipped with a chunk-layer oriented graph index, which facilitates efficient multi-granularity retrieval while significantly reducing both computational and economic costs.

We evaluate DA-RAG on multiple datasets, demonstrating that it outperforms existing RAG methods by up to 40% in head-to-head comparisons across four metrics while reducing index construction time and token overhead by up to 37% and 41%, respectively.


## Publication Details

- **Conference**: The Web Conference 2026 (WWW 2026)
- **Ranking**: CCF-A, Core A*
- **Year**: 2026
- **Status**: Accepted (January 2026)

## Authors

Xingyuan Zeng, **Zuohan Wu**, Yue Wang, Chen Zhang, Quanming Yao, Libin Zheng, Jian Yin

## BibTeX

{% raw %}
```bibtex
@inproceedings{zeng2026darag,
  author       = {Xingyuan Zeng and
                  Zuohan Wu and
                  Yue Wang and
                  Chen Zhang and
                  Quanming Yao and
                  Libin Zheng and
                  Jian Yin},
  title        = {DA-RAG: Dynamic Attributed Community Search for Retrieval-Augmented Generation},
  booktitle    = {The Web Conference 2026, {WWW} 2026},
  year         = {2026}
}
```
{% endraw %}
