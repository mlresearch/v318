---
title: Multi-Objective Reference-Aligned Machine Unlearning
abstract: Machine unlearning aims to remove the influence of specific training samples
  while preserving the model’s utility. Existing single-objective approaches, such
  as gradient ascent or random relabeling, often induce catastrophic forgetting due
  to conflicting optimization dynamics and unbounded forgetting objectives that cause
  the model to drift from its pre-trained knowledge. We propose Reference-Aligned
  UnLearning (RAUL), a multi-objective framework that jointly optimizes forgetting
  and retention by replacing unbounded loss maximization with a bounded KL alignment
  of predictions on forgotten samples toward a reference distribution representing
  unseen data, instantiated either as a uniform distribution or an empirical distribution
  from a held-out reference set, which constrains the forgetting objective and reduces
  gradient conflict with retention. The resulting multi-objective optimization (MOO)
  problem is solved via Jacobian descent, which aggregates multiple gradients into
  a direction that does not conflict. Our results demonstrate that RAUL achieves the
  closest gap compared to full retraining.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: khosrowshahli26a
month: 0
tex_title: Multi-Objective Reference-Aligned Machine Unlearning
firstpage: 833
lastpage: 839
page: 833-839
order: 833
cycles: false
bibtex_author: Khosrowshahli, Rasa and Asobiela, Stephen and Ombuki-Berman, Beatrice
  and Rahnamayan, Shahryrar
author:
- given: Rasa
  family: Khosrowshahli
- given: Stephen
  family: Asobiela
- given: Beatrice
  family: Ombuki-Berman
- given: Shahryrar
  family: Rahnamayan
date: 2026-06-29
address:
container-title: Proceedings of the The 39th Canadian Conference on Artificial Intelligence
volume: '318'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 6
  - 29
pdf: https://raw.githubusercontent.com/mlresearch/v318/main/assets/khosrowshahli26a/khosrowshahli26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
