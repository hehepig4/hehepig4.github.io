---
title: "RuleMem: Active Rule Memory for Long-Term Conversational Agents"
collection: publications
permalink: /publication/2026-arXiv-RuleMem
excerpt: 'RuleMem learns reusable natural-language rules from dialogue history to guide memory retrieval and answer generation in long-term conversational agents.'
date: 2026-09-03
venue: 'arXiv preprint arXiv:2609.03915'
publication_status: preprint
paperurl: 'https://arxiv.org/abs/2609.03915'
pdfurl: 'https://arxiv.org/pdf/2609.03915'
arxivurl: 'https://arxiv.org/abs/2609.03915'
citation: 'Xingyuan Zeng, Zuohan Wu, Yue Wang, Chen Zhang, Quanming Yao, Wei Liu, Jiuke Wang, Libin Zheng, Jian Yin. &quot;RuleMem: Active Rule Memory for Long-Term Conversational Agents.&quot; <i>arXiv preprint arXiv:2609.03915</i>, 2026.'
---

## Overview

**RuleMem** equips conversational agents with reusable rules learned from earlier interactions. It expresses these rules as natural-language Horn clauses and checks them using Rule Perplexity Consistency (RPC). The resulting memory helps retrieve evidence that may be distant in wording and provides a logical structure for producing answers.

The framework is evaluated on LoCoMo and LongMemEval_s*, with comparisons to existing conversational memory approaches. Its central goal is to make past interactions useful for both retrieval and reasoning over long dialogue histories.

## Key Contributions

- A rule-based memory representation derived from conversation history.
- RPC-based validation of induced rules.
- Rule-guided evidence retrieval and answer generation, evaluated on two long-term conversational benchmarks.

## Publication Details

- **Venue**: arXiv preprint
- **Year**: 2026
- **Submitted**: September 3, 2026
- **arXiv**: [2609.03915](https://arxiv.org/abs/2609.03915)
- **Paper**: [PDF](https://arxiv.org/pdf/2609.03915)

## Authors

Xingyuan Zeng, **Zuohan Wu**, Yue Wang, Chen Zhang, Quanming Yao, Wei Liu, Jiuke Wang, Libin Zheng, Jian Yin

## BibTeX

{% raw %}
```bibtex
@misc{zeng2026rulemem,
  author        = {Xingyuan Zeng and
                   Zuohan Wu and
                   Yue Wang and
                   Chen Zhang and
                   Quanming Yao and
                   Wei Liu and
                   Jiuke Wang and
                   Libin Zheng and
                   Jian Yin},
  title         = {RuleMem: Active Rule Memory for Long-Term Conversational Agents},
  year          = {2026},
  eprint        = {2609.03915},
  archivePrefix = {arXiv},
  primaryClass  = {cs.CL},
  url           = {https://arxiv.org/abs/2609.03915}
}
```
{% endraw %}
