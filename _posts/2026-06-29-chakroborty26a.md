---
title: A Quantitative Evaluation Protocol for Assessing the Clinical Usefulness of
  3D Saliency Explanations for MRI-based Alzheimer’s Classification
abstract: 'While Explainable AI (XAI) is widely considered essential for building
  clinical trust in MRI-based 3D deep learning models for Alzheimer’s disease (AD)
  detection, the clinical validation of these explanations is insufficiently rigorous.
  Current evaluation protocols for assessing clinical usefulness rely mainly on subjective
  visual inspections or limited attributions ’top-k’ regional overlap measures. These
  methods do not offer a standardized benchmark, making it difficult to objectively
  determine which explanation method most accurately aligns with the complex and distributed
  nature of neurodegenerative pathology. To address this gap, this paper proposes
  a quantitative evaluation protocol for assessing the clinical usefulness of 3D saliency
  maps through metric-based anatomical alignment. We implement a comprehensive scoring
  system based on AD neuropathology that assigns clinical importance weights to anatomical
  regions, allowing for mathematical verification of explanation integrity. We employ
  a variety of ranking and alignment metrics to evaluate five gradient-based XAI methods:
  Grad-CAM, Grad-CAM++, HiResCAM, Backpropagation, and Guided Backpropagation, applied
  to a pre-trained 3D DenseNet architecture. Our findings reveal notable disparities
  in usefulness that visual inspection and the existing regional overlap protocol
  often fail to detect properly. Among XAI methods, Grad-CAM++ demonstrated considerable
  instability and poor alignment with clinical relevance, while Backpropagation and
  Guided Backpropagation displayed superior spatial consistency by effectively prioritizing
  clinically significant biomarkers. This protocol provides a structured approach
  for evaluating explanation methods, advancing empirical alignment between XAI outputs
  and established pathological evidence.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chakroborty26a
month: 0
tex_title: A Quantitative Evaluation Protocol for Assessing the Clinical Usefulness
  of 3D Saliency Explanations for MRI-based Alzheimer’s Classification
firstpage: 983
lastpage: 989
page: 983-989
order: 983
cycles: false
bibtex_author: Chakroborty, Tamal and Liu, Yang
author:
- given: Tamal
  family: Chakroborty
- given: Yang
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
pdf: https://raw.githubusercontent.com/mlresearch/v318/main/assets/chakroborty26a/chakroborty26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
