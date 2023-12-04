---
title: Temporal Supervised Contrastive Learning for Modeling Patient Risk Progression
abstract: 'We consider the problem of predicting how the likelihood of an outcome
  of interest for a patient changes over time as we observe more of the patient’s
  data. To solve this problem, we propose a supervised contrastive learning framework
  that learns an embedding representation for each time step of a patient time series.
  Our framework learns the embedding space to have the following properties: (1){~}nearby
  points in the embedding space have similar predicted class probabilities, (2){~}adjacent
  time steps of the same time series map to nearby points in the embedding space,
  and (3){~}time steps with very different raw feature vectors map to far apart regions
  of the embedding space. To achieve property (3), we employ a nearest neighbor pairing
  mechanism in the raw feature space. This mechanism also serves as an alternative
  to “data augmentation”, a key ingredient of contrastive learning, which lacks a
  standard procedure that is adequately realistic for clinical tabular data, to our
  knowledge. We demonstrate that our approach outperforms state-of-the-art baselines
  in predicting mortality of septic patients (MIMIC-III dataset) and tracking progression
  of cognitive impairment (ADNI dataset). Our method also consistently recovers the
  correct synthetic dataset embedding structure across experiments, a feat not achieved
  by baselines. Our ablation experiments show the pivotal role of our nearest neighbor
  pairing.'
software: https://github.com/Shahriarnz14/Temporal-Supervised-Contrastive-Learning
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: noroozizadeh23a
month: 0
tex_title: Temporal Supervised Contrastive Learning for Modeling Patient Risk Progression
firstpage: 403
lastpage: 427
page: 403-427
order: 403
cycles: false
bibtex_author: Noroozizadeh, Shahriar and Weiss, Jeremy C. and Chen, George H.
author:
- given: Shahriar
  family: Noroozizadeh
- given: Jeremy C.
  family: Weiss
- given: George H.
  family: Chen
date: 2023-12-04
address: 
container-title: Proceedings of the 3rd Machine Learning for Health Symposium
volume: '225'
genre: inproceedings
issued:
  date-parts:
  - 2023
  - 12
  - 4
pdf: https://proceedings.mlr.press/v225/noroozizadeh23a/noroozizadeh23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
