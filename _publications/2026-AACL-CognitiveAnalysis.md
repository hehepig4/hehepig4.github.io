---
title: "Superficial Reflection or Genuine Thought? A Fine-Grained Cognitive Analysis of Large Reasoning Models"
collection: publications
permalink: /publication/2026-AACL-CognitiveAnalysis
redirect_from:
  - /publication/2025-arXiv-ProbingPsyche
excerpt: 'A fine-grained taxonomy and the CAPO annotation framework reveal how large reasoning models organise information, reflect, and self-correct, with validation across model generations and reasoning domains.'
date: 2026-09-07
venue: 'AACL-IJCNLP 2026'
publication_status: accepted
paperurl: '/files/2026-AACL-CognitiveAnalysis.pdf'
pdfurl: '/files/2026-AACL-CognitiveAnalysis.pdf'
arxivurl: 'https://arxiv.org/abs/2512.00729'
arxiv_label: 'Earlier arXiv version'
codeurl: 'https://github.com/hehepig4/psyche'
citation: 'Yuxiang Chen<sup>*</sup>, Zuohan Wu<sup>*</sup>, Ziwei Wang, Xiangning Yu, Xujia Li, Linyi Yang, Mengyue Yang, Jun Wang, Lei Chen. &quot;Superficial Reflection or Genuine Thought? A Fine-Grained Cognitive Analysis of Large Reasoning Models.&quot; <i>AACL-IJCNLP 2026</i>, accepted. <sup>*</sup>Equal contribution.'
---

## Abstract

Motivated by the observed human-like behaviours in Large Reasoning Models (LRMs), this paper introduces a comprehensive taxonomy to characterise atomic reasoning steps and analyse the reasoning behaviours of LRMs. Grounded in human cognitive processes, we propose a taxonomy comprising five groups and seventeen categories. Through this taxonomy, we conduct an in-depth analysis of contemporary LRMs and distil four actionable takeaways for model optimisation. Most notably, we reveal that prevailing post-answer "double-checks" are largely superficial and rarely yield substantive revisions. A targeted intervention further shows that explicitly eliciting richer reflection processes can substantially improve failed self-correction. To support this large-scale study, we propose CAPO, an automated annotation method used to construct a dataset of 277,534 reasoning steps with strong agreement with human expert annotations. We further validate the main behavioural patterns on a newer reasoning model and a coding domain, demonstrating the broader applicability of the proposed taxonomy. All source code and data are available at [github.com/hehepig4/psyche](https://github.com/hehepig4/psyche).

## Key Contributions

- A taxonomy with five groups and seventeen categories for analysing observable reasoning behaviours, using human cognition as a descriptive framework.
- CAPO, an automated annotation method supporting a corpus of 277,534 reasoning steps.
- An analysis of information organisation, analogy and hypothesis generation, reflection, and redundancy, including a targeted intervention to improve failed self-correction.
- Validation of the main behavioural patterns on a newer reasoning model and a coding domain.

## Publication Details

- **Conference**: AACL-IJCNLP 2026
- **Year**: 2026
- **Status**: Accepted; to appear
- **Paper**: [Camera-ready PDF](/files/2026-AACL-CognitiveAnalysis.pdf)
- **Code and data**: [GitHub](https://github.com/hehepig4/psyche)
- **Earlier version**: [arXiv:2512.00729](https://arxiv.org/abs/2512.00729), originally titled *Probing the "Psyche" of Large Reasoning Models: Understanding Through a Human Lens* (2025).

## Authors

Yuxiang Chen<sup>*</sup>, **Zuohan Wu**<sup>*</sup>, Ziwei Wang, Xiangning Yu, Xujia Li, Linyi Yang, Mengyue Yang, Jun Wang, Lei Chen

<sup>*</sup>Equal contribution.

## BibTeX

{% raw %}
```bibtex
@inproceedings{chen2026cognitiveanalysis,
  author       = {Yuxiang Chen and
                  Zuohan Wu and
                  Ziwei Wang and
                  Xiangning Yu and
                  Xujia Li and
                  Linyi Yang and
                  Mengyue Yang and
                  Jun Wang and
                  Lei Chen},
  title        = {Superficial Reflection or Genuine Thought? A Fine-Grained Cognitive Analysis of Large Reasoning Models},
  booktitle    = {AACL-IJCNLP 2026},
  year         = {2026},
  note         = {Accepted, to appear},
  url          = {https://hehepig4.github.io/files/2026-AACL-CognitiveAnalysis.pdf}
}
```
{% endraw %}
