---
title: "Efficient Zero-Shot and Label-free Log Anomaly Detection for Resource-Constrained Systems"
collection: publications
permalink: /publication/2026-ICDE-MaidLog
excerpt: 'MaidLog uses LLM-assisted pseudo-labels to train a generalisable, lightweight log anomaly detector. Downstream detection requires neither manual labels nor LLM inference, making it suitable for resource-constrained systems.'
date: 2026-05-01
venue: '2026 IEEE 42nd International Conference on Data Engineering (ICDE)'
publication_status: published
paperurl: 'https://doi.org/10.1109/ICDE65706.2026.00056'
pdfurl: 'https://dominatorx.github.io/files/26ICDE-p.pdf'
doi: '10.1109/ICDE65706.2026.00056'
codeurl: 'https://github.com/hehepig4/maidlog'
dblpurl: 'https://dblp.org/rec/conf/icde/WuWZZLC26.html'
citation: 'Zuohan Wu, Jiachuan Wang, Libin Zheng, Yongqi Zhang, Shuangyin Li, Lei Chen. &quot;Efficient Zero-Shot and Label-free Log Anomaly Detection for Resource-Constrained Systems.&quot; <i>2026 IEEE 42nd International Conference on Data Engineering (ICDE)</i>, pp. 671-684, 2026.'
---

## Overview

**MaidLog** separates LLM-assisted training from lightweight log anomaly detection. During training, LLMs generate and refine pseudo-labels for unlabeled source-system logs. These labels train a detector designed to generalise to unseen target systems without post-training. Downstream detection uses the trained detector alone, with no LLM calls.

This design combines zero-shot transfer and label-free training with efficient inference for resource-constrained systems. Experiments on real-world logs evaluate its accuracy, cross-system generalisation, and computational efficiency against LLM-centric and non-LLM approaches.

## Key Contributions

- An LLM-assisted pseudo-label assignment workflow that removes the need for manually labeled training data.
- A generalisable detector for zero-shot anomaly detection on unseen target systems.
- Lightweight, LLM-free inference for resource-constrained deployments.
- Evaluation on real-world datasets, including cross-system generalisation and efficiency comparisons.

## Publication Details

- **Conference**: 2026 IEEE 42nd International Conference on Data Engineering (ICDE)
- **Ranking**: CCF-A, Core A*
- **Year**: 2026
- **Pages**: 671-684
- **Publisher**: IEEE
- **DOI**: [10.1109/ICDE65706.2026.00056](https://doi.org/10.1109/ICDE65706.2026.00056)
- **Paper**: [PDF](https://dominatorx.github.io/files/26ICDE-p.pdf)
- **Code**: [GitHub](https://github.com/hehepig4/maidlog)
- **DBLP**: [Publication record](https://dblp.org/rec/conf/icde/WuWZZLC26.html)

## Authors

**Zuohan Wu**, Jiachuan Wang, Libin Zheng, Yongqi Zhang, Shuangyin Li, Lei Chen

## BibTeX

{% raw %}
```bibtex
@inproceedings{wu2026maidlog,
  author       = {Zuohan Wu and
                  Jiachuan Wang and
                  Libin Zheng and
                  Yongqi Zhang and
                  Shuangyin Li and
                  Lei Chen},
  title        = {Efficient Zero-Shot and Label-free Log Anomaly Detection for Resource-Constrained Systems},
  booktitle    = {2026 IEEE 42nd International Conference on Data Engineering (ICDE)},
  pages        = {671--684},
  publisher    = {IEEE},
  year         = {2026},
  doi          = {10.1109/ICDE65706.2026.00056},
  url          = {https://doi.org/10.1109/ICDE65706.2026.00056}
}
```
{% endraw %}
