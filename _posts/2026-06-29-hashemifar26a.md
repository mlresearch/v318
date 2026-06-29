---
title: Diagnosing and Repairing Factual Errors in RAG under Budget Constraints
abstract: Retrieval-Augmented Generation (RAG) improves the factuality of large language
  models by grounding responses in external evidence, yet real-world deployments remain
  fragile. Failures often stem from missing or weakly relevant evidence, as well as
  from generation that does not faithfully reflect the retrieved context. Many existing
  approaches rely on fine-tuning, privileged access to internal model signals, or
  resource-insensitive escalation strategies, which limits their practicality in black-box
  and budget-constrained settings. We propose D2R-RAG (Diagnose-to-Repair RAG), a
  model-agnostic and resource-aware framework that combines lightweight failure diagnosis
  with adaptive repair. D2R-RAG derives interpretable failure signatures from observable
  signals in the query, retrieved evidence, and generated response, and then selects
  from a small set of corrective actions under explicit latency and VRAM constraints.
  Experiments on FEVER and HotpotQA show that D2R-RAG improves reliability over recent
  baselines and achieves better accuracy–efficiency trade-offs across multiple compute
  budgets. The code is available at https://github.com/CyberScienceLab/D2R-RAG/.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hashemifar26a
month: 0
tex_title: Diagnosing and Repairing Factual Errors in RAG under Budget Constraints
firstpage: 924
lastpage: 931
page: 924-931
order: 924
cycles: false
bibtex_author: Hashemifar, Soroush and Noughabi, Havva Alizadeh and Zarrinkalam, Fattane
  and Dehghantanha, Ali
author:
- given: Soroush
  family: Hashemifar
- given: Havva Alizadeh
  family: Noughabi
- given: Fattane
  family: Zarrinkalam
- given: Ali
  family: Dehghantanha
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
pdf: https://raw.githubusercontent.com/mlresearch/v318/main/assets/hashemifar26a/hashemifar26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
