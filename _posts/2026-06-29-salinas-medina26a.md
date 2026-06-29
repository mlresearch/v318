---
title: 'RAG-Safe: A Recall-First Safety Framework Comparing Open-Source and Commercial
  LLM Moderation Pipelines'
abstract: 'False negatives—missed detections of harmful content—remain the dominant
  risk in safety-critical moderation pipelines. We introduce RAG-Safe, a recall-first
  framework that integrates distribution-preserving contrastive augmentation, committee-diverse
  retrieval, and a recall-oriented decision policy into a unified moderation architecture.
  The framework is evaluated using a compact, fully auditable testbed designed to
  enforce strict leakage control: original samples alone determine the train–test
  split, and all paraphrases inherit their parent assignment. Within this controlled
  setting, conventional retrieval-augmented pipelines—both commercial (API embeddings
  + hosted LLM) and open-source (FAISS + local LLaMA-3)—consistently under-detect
  unsafe content (FLAGGED recall 0.44). Applying RAG-Safe raises FLAGGED recall to
  approximately 0.56 across both stacks while preserving overall accuracy ( 0.66)
  and macro-F1 ( 0.65). A non-RAG classifier baseline provided in our public repository
  shows similar recallfirst behaviour, reinforcing that these gains are not architecture-specific.
  Rather than comparing individual model components, we interpret the results as pipeline-level
  evidence that boundary-focused augmentation, retrieval diversity, and calibrated
  thresholds jointly shift LLM moderation into a safer operating regime. We conclude
  by discussing limitations—particularly domain transferability and adversarial robustness—and
  outline directions for scaling RAG-Safe to broader moderation contexts. Keywords:
  Content moderation, Recall-first classification, Distribution-preserving data augmentation,
  Committee-based retrieval, Retrieval-augmented large language models, Safety-critical
  AI'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: salinas-medina26a
month: 0
tex_title: 'RAG-Safe: A Recall-First Safety Framework Comparing Open-Source and Commercial
  LLM Moderation Pipelines'
firstpage: 709
lastpage: 722
page: 709-722
order: 709
cycles: false
bibtex_author: Salinas-Medina, Alejandro and Liu, Xue
author:
- given: Alejandro
  family: Salinas-Medina
- given: Xue
  family: Liu
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
pdf: https://raw.githubusercontent.com/mlresearch/v318/main/assets/salinas-medina26a/salinas-medina26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
