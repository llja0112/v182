---
abstract: Two major causes of death in the United States and worldwide are stroke
  and myocardial infarction. The underlying cause of both is thrombi released from
  ruptured or eroded unstable atherosclerotic plaques that occlude vessels in the
  heart (myocardial infarction) or the brain (stroke). Clinical studies show that
  plaque composition plays a more important role than lesion size in plaque rupture
  or erosion events. To determine the plaque composition, various cell types in 3D
  cardiovascular immunofluorescent images of plaque lesions are counted. However,
  counting these cells manually is expensive, time-consuming, and prone to human error.
  These challenges of manual counting motivate the need for an automated approach
  to localize and count the cells in images. The purpose of this study is to develop
  an automatic approach to accurately detect and count cells in 3D immunofluorescent
  images with minimal annotation effort. In this study, we used a weakly supervised
  learning approach to train the HoVer-Net segmentation model using point annotations
  to detect nuclei in fluorescent images. The advantage of using point annotations
  is that they require less effort as opposed to pixel-wise annotation. To train the
  HoVer-Net model using point annotations, we adopted a popularly used cluster labeling
  approach to transform point annotations into accurate binary masks of cell nuclei.
  Traditionally, these approaches have generated binary masks from point annotations,
  leaving a region around the object unlabeled (which is typically ignored during
  model training). However, these areas may contain important information that helps
  determine the boundary between cells. Therefore, we used the entropy minimization
  loss function in these areas to encourage the model to output more confident predictions
  on the unlabeled areas. Our comparison studies indicate that the HoVer-Net model
  trained using our weakly supervised learning approach outperforms baseline methods
  on the cardiovascular dataset. In addition, we evaluated and compared the performance
  of the trained HoVer-Net model to other methods on another cardiovascular dataset,
  which also utilizes DAPI to identify nuclei, but is from a different mouse model
  stained and imaged independently from the first cardiovascular dataset. The comparison
  results show the high generalization capability of the HoVer-Net model trained using
  a weakly supervised learning approach and assessed with standard detection metrics.
booktitle: Proceedings of the 7th Machine Learning for Healthcare Conference
title: Weakly Supervised Deep Instance Nuclei Detection using Points Annotation in
  3D Cardiovascular Immunofluorescent Images
volume: '182'
year: '2022'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: moradinasab22a
month: 0
tex_title: Weakly Supervised Deep Instance Nuclei Detection using Points Annotation
  in 3D Cardiovascular Immunofluorescent Images
firstpage: 565
lastpage: 584
page: 565-584
order: 565
cycles: false
bibtex_author: Moradinasab, Nazanin and Sharma, Yash and Shankman, Laura S. and Owens,
  Gary K. and Brown, Donald E.
author:
- given: Nazanin
  family: Moradinasab
- given: Yash
  family: Sharma
- given: Laura S.
  family: Shankman
- given: Gary K.
  family: Owens
- given: Donald E.
  family: Brown
date: 2022-12-31
address:
container-title: Proceedings of the 7th Machine Learning for Healthcare Conference
genre: inproceedings
issued:
  date-parts:
  - 2022
  - 12
  - 31
pdf: https://proceedings.mlr.press/v182/moradinasab22a/moradinasab22a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
