---
title: "Superficial Reflection or Genuine Thought? A Fine-Grained Cognitive Analysis of Large Reasoning Models"
collection: publications
permalink: /publication/2026-AACL-CognitiveAnalysis
redirect_from:
  - /publication/2025-arXiv-ProbingPsyche
excerpt: 'A fine-grained taxonomy and the CAPO annotation framework reveal how large reasoning models organise information, reflect, and self-correct, with validation across model generations and reasoning domains.'
# Website entry date; the proceedings publication month is recorded separately.
date: 2026-09-07
publication_month: 'November 2026'
venue: 'Findings of the Association for Computational Linguistics: IJCNLP-AACL 2026'
publication_status: published
paperurl: 'https://aclanthology.org/2026.findings-aacl.229.pdf'
pdfurl: 'https://aclanthology.org/2026.findings-aacl.229.pdf'
doi: '10.18653/2026.findings-aacl.229'
anthologyurl: 'https://aclanthology.org/2026.findings-aacl.229/'
arxivurl: 'https://arxiv.org/abs/2512.00729'
arxiv_label: 'Earlier arXiv version'
codeurl: 'https://github.com/hehepig4/psyche'
citation: 'Yuxiang Chen<sup>&#42;</sup>, Zuohan Wu<sup>&#42;</sup>, Ziwei Wang, Xiangning Yu, Xujia Li, Linyi Yang, Mengyue Yang, Jun Wang, Lei Chen. &quot;Superficial Reflection or Genuine Thought? A Fine-Grained Cognitive Analysis of Large Reasoning Models.&quot; <i>Findings of the Association for Computational Linguistics: IJCNLP-AACL 2026</i>, pp. 4530-4548, 2026. Association for Computational Linguistics. DOI: 10.18653/2026.findings-aacl.229. <sup>&#42;</sup>Equal contribution.'
---

## Abstract

Motivated by the observed human-like behaviours in Large Reasoning Models (LRMs), this paper introduces a comprehensive taxonomy to characterise atomic reasoning steps and analyse the reasoning behaviours of LRMs. Grounded in human cognitive processes, we propose a taxonomy comprising five groups and seventeen categories. Through this taxonomy, we conduct an in-depth analysis of contemporary LRMs and distil four actionable takeaways for model optimisation. Most notably, we reveal that prevailing post-answer "double-checks" are largely superficial and rarely yield substantive revisions. A targeted intervention further shows that explicitly eliciting richer reflection processes can substantially improve failed self-correction. To support this large-scale study, we propose CAPO, an automated annotation method used to construct a dataset of 277,534 reasoning steps with strong agreement with human expert annotations. We further validate the main behavioural patterns on a newer reasoning model and a coding domain, demonstrating the broader applicability of the proposed taxonomy. All source code and data are available at [github.com/hehepig4/psyche](https://github.com/hehepig4/psyche).

## Key Contributions

- A taxonomy with five groups and seventeen categories for analysing observable reasoning behaviours, using human cognition as a descriptive framework.
- CAPO, an automated annotation method supporting a corpus of 277,534 reasoning steps.
- An analysis of information organisation, analogy and hypothesis generation, reflection, and redundancy, including a targeted intervention to improve failed self-correction.
- Validation of the main behavioural patterns on a newer reasoning model and a coding domain.

## Publication Details

- **Venue**: Findings of the Association for Computational Linguistics: IJCNLP-AACL 2026
- **Published**: {{ page.publication_month }}
- **Pages**: 4530-4548
- **Publisher**: Association for Computational Linguistics
- **Location**: Hengqin, China
- **Status**: Published
- **ACL Anthology**: [2026.findings-aacl.229](https://aclanthology.org/2026.findings-aacl.229/)
- **DOI**: [10.18653/2026.findings-aacl.229](https://doi.org/10.18653/2026.findings-aacl.229)
- **Paper**: [Official proceedings PDF](https://aclanthology.org/2026.findings-aacl.229.pdf)
- **Code and data**: [GitHub](https://github.com/hehepig4/psyche)
- **Earlier version**: [arXiv:2512.00729](https://arxiv.org/abs/2512.00729), originally titled *Probing the "Psyche" of Large Reasoning Models: Understanding Through a Human Lens* (2025).

## Authors

Yuxiang Chen<sup>&#42;</sup>, **Zuohan Wu**<sup>&#42;</sup>, Ziwei Wang, Xiangning Yu, Xujia Li<sup>&#8224;</sup>, Linyi Yang, Mengyue Yang, Jun Wang, Lei Chen

<sup>&#42;</sup>Equal contribution. <sup>&#8224;</sup>Corresponding author.

## BibTeX

{% raw %}
```bibtex
@inproceedings{chen-etal-2026-superficial,
    title = "Superficial Reflection or Genuine Thought? A Fine-Grained Cognitive Analysis of Large Reasoning Models",
    author = "Chen, Yuxiang  and
      Wu, Zuohan  and
      Wang, Ziwei  and
      Yu, Xiangning  and
      Li, Xujia  and
      Yang, Linyi  and
      Yang, Mengyue  and
      Wang, Jun  and
      Chen, Lei",
    editor = "Zhang, Yue  and
      Xu, Ruifeng  and
      Purwarianti, Ayu  and
      Rong, Tong  and
      Suzuki, Jun",
    booktitle = "Findings of the {A}ssociation for {C}omputational {L}inguistics: {IJCNLP}-{AACL} 2026",
    month = nov,
    year = "2026",
    address = "Hengqin, China",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2026.findings-aacl.229/",
    doi = "10.18653/2026.findings-aacl.229",
    pages = "4530--4548",
    ISBN = "979-8-89176-444-6"
}
```
{% endraw %}
