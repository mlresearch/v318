---
title: Cause-Conditioned Multi-Task Learning for Answerable Question Suggestion in
  MRC
abstract: 'Machine Reading Comprehension (MRC) systems struggle when user questions
  are unanswerable given the passage: most simply output “no answer”, leaving users
  without guidance on how to recover useful information. We introduce a \textit{cause-conditioned
  multi-task learning (MTL)} framework that turns failure into follow-up by jointly
  (1) classifying an input as answerable or as one of six fine-grained unanswerability
  causes (Entity Swap, Number Swap, Antonym, Negation, Mutual Exclusion, No Information),
  and (2) generating a revised, context-grounded answerable question conditioned on
  the predicted cause label and an extracted guidance sentence. Using an ensemble
  of strong readers plus LLMs-as-judges, we apply majority voting to test whether
  rewrites become answerable. A human study further assesses fluency, relevance, and
  usefulness. Our cause-conditioning MTL framework yields better recovery from unanswerable
  inputs and earns strong human ratings, advancing user-supportive, failure-aware
  MRC.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: moradisani26a
month: 0
tex_title: Cause-Conditioned Multi-Task Learning for Answerable Question Suggestion
  in MRC
firstpage: 248
lastpage: 259
page: 248-259
order: 248
cycles: false
bibtex_author: Moradisani, Hadiseh and Zarrinkalam, Fattane and Serbanescu, Julien
  and Noorian, Zeinab
author:
- given: Hadiseh
  family: Moradisani
- given: Fattane
  family: Zarrinkalam
- given: Julien
  family: Serbanescu
- given: Zeinab
  family: Noorian
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
pdf: https://raw.githubusercontent.com/mlresearch/v318/main/assets/moradisani26a/moradisani26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
