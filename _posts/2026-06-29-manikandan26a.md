---
title: 'GlossAdapter: Enhancing word sense disambiguation via LoRA adapters'
abstract: Word sense disambiguation (WSD) is a long-standing problem in natural language
  processing (NLP). Recently, fine-tuned large pre-trained models with gloss and other
  lexical information have been used for WSD. But these models are parameter inefficient
  as the entire model needs to be trained. To deal with the problem, we propose GlossAdapter
  to WSD via Low-Rank Adaptation (LoRA) adapter modules and Part of Speech (POS) filtering.
  LoRA modules are parameter-efficient as they add only a few trainable parameters
  for a task, keeping the original weights of the pre-trained model frozen while maintaining
  the model quality. The proposed POS filtering aligns target word context with WordNet
  lexical categories to construct sentence-gloss pairs for effective model training.
  We fine-tune our model with SemCor3.0 dataset, and evaluated it with benchmark datasets
  Senseval-2, Senseval-3, SemEval-2013, and SemEval-2015. We perform experiments based
  on BERTbase and RoBERTalarge models. By adding only 0.5% of the parameters for RoBERTalarge,
  the results show that our LoRA adapter-based model combined with POS filtering outperforms
  the other state-of-the-art models.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: manikandan26a
month: 0
tex_title: 'GlossAdapter: Enhancing word sense disambiguation via LoRA adapters'
firstpage: 1044
lastpage: 1051
page: 1044-1051
order: 1044
cycles: false
bibtex_author: Manikandan, Vijayalakshmi and Wen, Dunwei and Dewan, M. Ali Akber
author:
- given: Vijayalakshmi
  family: Manikandan
- given: Dunwei
  family: Wen
- given: M. Ali Akber
  family: Dewan
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
pdf: https://raw.githubusercontent.com/mlresearch/v318/main/assets/manikandan26a/manikandan26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
