---
title: Cluster-Aware Retrieval-Augmented Generation with Hybrid Retrieval for Faithful
  Medical Report Summarization
abstract: 'Large Language Models (LLMs) can generate fluent medical summaries but
  may hallucinate facts not supported by source clinical text, limiting safe clinical
  adoption. In our prior work, we improved relevance through embedding-based patient
  clustering and cluster-wise GPT-4.0 summarization; however, summaries could still
  include unsupported claims due to a lack of explicit evidence grounding. This paper
  extends that pipeline with a cluster-aware Retrieval-Augmented Generation (RAG)
  layer to ground summaries in retrieved evidence. For each cluster, we construct
  two evidence artifacts: (i) a Cluster Profile aggregating clinical statistics (e.g.,
  means, ranges, abnormality rates), and (ii) a Snippet Bank of patient report excerpts.
  Evidence is retrieved via a hybrid retriever that combines TF-IDF and dense-embedding
  similarity with weighted scoring. We enforce citation-constrained prompting, requiring
  each major claim to cite retrieved evidence or be marked as “insufficient evidence”.
  We evaluate cluster-wise RAG summaries using metrics for faithfulness (supported-claim
  rate), completeness (coverage of key abnormal indicators), and safety and overreach
  (diagnostic, medication, and absolute claims). Experiments on a synthetic hypertension
  dataset (150 patients stratified into low-, average-, and high-risk) show that our
  approach reduces hallucinations while preserving the personalization benefits of
  clustering.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: torabizadeh26a
month: 0
tex_title: Cluster-Aware Retrieval-Augmented Generation with Hybrid Retrieval for
  Faithful Medical Report Summarization
firstpage: 1162
lastpage: 1168
page: 1162-1168
order: 1162
cycles: false
bibtex_author: Torabizadeh, Kiarash and Hedjam, Rachid and Allaoui, Mebarka and Abdulrazak,
  Bessam
author:
- given: Kiarash
  family: Torabizadeh
- given: Rachid
  family: Hedjam
- given: Mebarka
  family: Allaoui
- given: Bessam
  family: Abdulrazak
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
pdf: https://raw.githubusercontent.com/mlresearch/v318/main/assets/torabizadeh26a/torabizadeh26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
