---
abstract: Deep neural networks for image-based screening and computer-aided diagnosis
  have achieved expert-level performance on various medical imaging modalities, including
  chest radiographs. Recently, several works have indicated that these state-of-the-art
  classifiers can be biased with respect to sensitive patient attributes, such as
  race or gender, leading to growing concerns about demographic disparities and discrimination
  resulting from algorithmic and model-based decision-making in healthcare. Fair machine
  learning has focused on mitigating such biases against disadvantaged or marginalised
  groups, mainly concentrating on tabular data or natural images. This work presents
  two novel intra-processing techniques based on fine-tuning and pruning an already-trained
  neural network. These methods are simple yet effective and can be readily applied
  post hoc in a setting where the protected attribute is unknown during the model
  development and test time. In addition, we compare several intra and post-processing
  approaches applied to debiasing deep chest X-ray classifiers. To the best of our
  knowledge, this is one of the first efforts studying debiasing methods on chest
  radiographs. Our results suggest that the considered approaches successfully mitigate
  biases in fully connected and convolutional neural networks offering stable performance
  under various settings. The discussed methods can help achieve group fairness of
  deep medical image classifiers when deploying them in domains with different fairness
  considerations and constraints.
booktitle: Proceedings of the 7th Machine Learning for Healthcare Conference
title: Debiasing Deep Chest X-Ray Classifiers using Intra- and Post-processing Methods
volume: '182'
year: '2022'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: marcinkevics22a
month: 0
tex_title: Debiasing Deep Chest X-Ray Classifiers using Intra- and Post-processing
  Methods
firstpage: 504
lastpage: 536
page: 504-536
order: 504
cycles: false
bibtex_author: Marcinkevics, Ricards and Ozkan, Ece and Vogt, Julia E.
author:
- given: Ricards
  family: Marcinkevics
- given: Ece
  family: Ozkan
- given: Julia E.
  family: Vogt
date: 2022-12-31
address:
container-title: Proceedings of the 7th Machine Learning for Healthcare Conference
genre: inproceedings
issued:
  date-parts:
  - 2022
  - 12
  - 31
pdf: https://proceedings.mlr.press/v182/marcinkevics22a/marcinkevics22a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
