---
abstract: This paper introduces a novel non-parametric deep model for estimating time-to-event
  (survival analysis) in presence of censored data and competing risks. The model
  is designed based on the sequence-to-sequence (Seq2Seq) architecture, therefore
  we name it Survival Seq2Seq. The first recurrent neural network (RNN) layer of the
  encoder of our model is made up of Gated Recurrent Unit with Decay (GRU-D) cells.
  These cells have the ability to effectively impute not-missing-at-random values
  of longitudinal datasets with very high missing rates, such as electronic health
  records (EHRs). The decoder of Survival Seq2Seq generates a probability distribution
  function (PDF) for each competing risk without assuming any prior distribution for
  the risks. Taking advantage of RNN cells, the decoder is able to generate smooth
  and virtually spike-free PDFs. This is beyond the capability of existing non-parametric
  deep models for survival analysis. Training results on synthetic and medical datasets
  prove that Survival Seq2Seq surpasses other existing deep survival models in terms
  of the accuracy of predictions and the quality of generated PDFs.
booktitle: Proceedings of the 7th Machine Learning for Healthcare Conference
title: 'Survival Seq2Seq: A Survival Model based on Sequence to Sequence Architecture'
volume: '182'
year: '2022'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: pourjafari22a
month: 0
tex_title: 'Survival Seq2Seq: A Survival Model based on Sequence to Sequence Architecture'
firstpage: 79
lastpage: 100
page: 79-100
order: 79
cycles: false
bibtex_author: Pourjafari, Ebrahim and Ziaei, Navid and Rezaei, Mohammad R. and Sameizadeh,
  Amir and Shafiee, Mohammad and Alavinia, Mohammad and Abolghasemian, Mansour and
  Sajadi, Nick
author:
- given: Ebrahim
  family: Pourjafari
- given: Navid
  family: Ziaei
- given: Mohammad R.
  family: Rezaei
- given: Amir
  family: Sameizadeh
- given: Mohammad
  family: Shafiee
- given: Mohammad
  family: Alavinia
- given: Mansour
  family: Abolghasemian
- given: Nick
  family: Sajadi
date: 2022-12-31
address:
container-title: Proceedings of the 7th Machine Learning for Healthcare Conference
genre: inproceedings
issued:
  date-parts:
  - 2022
  - 12
  - 31
pdf: https://proceedings.mlr.press/v182/pourjafari22a/pourjafari22a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
