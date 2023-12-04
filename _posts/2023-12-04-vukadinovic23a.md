---
title: 'GANcMRI: Cardiac magnetic resonance video generation and physiologic guidance
  using latent space prompting'
abstract: Generative artificial intelligence can be applied to medical imaging on
  tasks such as privacy-preserving image generation and super-resolution and denoising
  of existing images. Few prior approaches have used cardiac magnetic resonance imaging
  (cMRI) as a modality given the complexity of videos (the addition of the temporal
  dimension) as well as the limited scale of publicly available datasets. We introduce
  GANcMRI, a generative adversarial network that can synthesize cMRI videos with physiological
  guidance based on latent space prompting. GANcMRI uses a StyleGAN framework to learn
  the latent space from individual video frames and leverages the time-dependent trajectory
  between end-systolic and end-diastolic frames in the latent space to predict progression
  and generate motion over time. We proposed various methods for modeling latent time-dependent
  trajectories and found that our Frame-to-frame approach generates the best motion
  and video quality. GANcMRI generated high-quality cMRI image frames that are indistinguishable
  by cardiologists, however, artifacts in video generation allow cardiologists to
  still recognize the difference between real and generated videos. The generated
  cMRI videos can be prompted to apply physiology-based adjustments which produces
  clinically relevant phenotypes recognizable by cardiologists. GANcMRI has many potential
  applications such as data augmentation, education, anomaly detection, and preoperative
  planning.
software: https://github.com/vukadinovic936/GANcMRI
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: vukadinovic23a
month: 0
tex_title: 'GANcMRI: Cardiac magnetic resonance video generation and physiologic guidance
  using latent space prompting'
firstpage: 594
lastpage: 606
page: 594-606
order: 594
cycles: false
bibtex_author: Vukadinovic, Milos and Kwan, Alan C and Li, Debiao and Ouyang, David
author:
- given: Milos
  family: Vukadinovic
- given: Alan C
  family: Kwan
- given: Debiao
  family: Li
- given: David
  family: Ouyang
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
pdf: https://proceedings.mlr.press/v225/vukadinovic23a/vukadinovic23a.pdf
extras:
- label: Supplementary ZIP
  link: https://proceedings.mlr.press/v225/vukadinovic23a/vukadinovic23a-supp.zip
- label: Supplementary PDF
  link: https://proceedings.mlr.press/v225/vukadinovic23a/vukadinovic23a-supp.pdf
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
