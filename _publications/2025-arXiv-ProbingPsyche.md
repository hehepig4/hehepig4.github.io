---
title: "Probing the 'Psyche' of Large Reasoning Models: Understanding Through a Human Lens"
collection: publications
permalink: /publication/2025-arXiv-ProbingPsyche
excerpt: 'This paper introduces a comprehensive taxonomy to characterize atomic reasoning steps in large reasoning models, grounding their understanding in human cognitive processes.'
date: 2025-11-30
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2512.00729'
citation: 'Yuxiang Chen, Zuohan Wu, Ziwei Wang, Xiangning Yu, Xujia Li, Linyi Yang, Mengyue Yang, Jun Wang, Lei Chen. &quot;Probing the Psyche of Large Reasoning Models: Understanding Through a Human Lens.&quot; <i>arXiv preprint arXiv:2512.00729</i>, 2025.'
---

## Abstract

Large reasoning models (LRMs) have garnered significant attention from researchers owing to their exceptional capability in addressing complex tasks. Motivated by the observed human-like behaviors in their reasoning processes, this paper introduces a comprehensive taxonomy to characterize atomic reasoning steps and probe the "psyche" of LRM intelligence. Specifically, it comprises five groups and seventeen categories derived from human mental processes, thereby grounding the understanding of LRMs in an interdisciplinary perspective.

The taxonomy is then applied for an in-depth understanding of current LRMs, resulting in a distinct labeled dataset that comprises 277,534 atomic reasoning steps. Using this resource, we analyze contemporary LRMs and distill several actionable takeaways for improving training and post-training of reasoning models. Notably, our analysis reveals that prevailing post-answer "double-checks" (self-monitoring evaluations) are largely superficial and rarely yield substantive revisions. Thus, incentivizing comprehensive multi-step reflection, rather than simple self-monitoring, may offer a more effective path forward.

To complement the taxonomy, an automatic annotation framework, named CAPO, is proposed to leverage large language models (LLMs) for generating the taxonomy-based annotations. Experimental results demonstrate that CAPO achieves higher consistency with human experts compared to baselines, facilitating a scalable and comprehensive analysis of LRMs from a human cognitive perspective.

## Key Contributions

- Introduced a comprehensive taxonomy comprising five groups and seventeen categories to characterize atomic reasoning steps in LRMs
- Created a labeled dataset with 277,534 atomic reasoning steps for analyzing LRM behaviors
- Proposed CAPO, an automatic annotation framework achieving high consistency with human experts
- Provided actionable insights for improving training and post-training of reasoning models

## Publication Details

- **Venue**: arXiv preprint
- **Year**: 2025
- **arXiv**: [2512.00729](https://arxiv.org/abs/2512.00729)
- **DOI**: [10.48550/arXiv.2512.00729](https://doi.org/10.48550/arXiv.2512.00729)

## Authors

Yuxiang Chen, **Zuohan Wu**, Ziwei Wang, Xiangning Yu, Xujia Li, Linyi Yang, Mengyue Yang, Jun Wang, Lei Chen

## BibTeX

{% raw %}
```bibtex
@article{chen2025probing,
  author       = {Yuxiang Chen and
                  Zuohan Wu and
                  Ziwei Wang and
                  Xiangning Yu and
                  Xujia Li and
                  Linyi Yang and
                  Mengyue Yang and
                  Jun Wang and
                  Lei Chen},
  title        = {Probing the "Psyche'' of Large Reasoning Models: Understanding Through a Human Lens},
  journal      = {arXiv preprint arXiv:2512.00729},
  year         = {2025},
  url          = {https://arxiv.org/abs/2512.00729},
  doi          = {10.48550/arXiv.2512.00729}
}
```
{% endraw %}
