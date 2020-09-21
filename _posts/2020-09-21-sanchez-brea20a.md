---
title: Deep learning-based retinal vessel segmentation with cross-modal evaluation
abstract: This work proposes a general pipeline for retinal vessel segmentation on
  {\em en-face} images. The main goal is to analyse if a model trained in one of two
  modalities, Fundus Photography (FP) or Scanning Laser Ophthalmoscopy (SLO), is transferable
  to the other modality accurately. This is motivated by the lack of development and
  data available in {\em en-face} imaging modalities other than FP. FP and SLO images
  of four and two publicly available datasets, respectively, were used. First, the
  current approaches were reviewed in order to define a basic pipeline for vessel
  segmentation. A state-of-art deep learning architecture (U-net) was used, and the
  effect of varying the patch size and number of patches was studied by training,
  validating, and testing on each dataset individually. Next, the model was trained
  in either FP or SLO images, using the available datasets for a given modality combined.
  Finally, the performance of each network was tested on the other modality. The models
  trained on each dataset showed a performance comparable to the state-of-the art
  and to the inter-rater reliability. Overall, the best performance was observed for
  the largest patch size (256) and the maximum number of overlapped images in each
  dataset, with a mean sensitivity, specificity, accuracy, and Dice score of 0.89$\pm$
  0.05, 0.95$\pm$0.02, 0.95$\pm$0.02, and 0.73$\pm$0.07, respectively. Models trained
  and tested on the same modality presented a sensitivity, specificity, and accuracy
  equal or higher than 0.9. The validation on a different modality has shown significantly
  better sensitivity and Dice on those trained on FP.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sanchez-brea20a
month: 0
tex_title: Deep learning-based retinal vessel segmentation with cross-modal evaluation
firstpage: 709
lastpage: 720
page: 709-720
order: 709
cycles: false
bibtex_author: Sanchez Brea, Luisa and De Jesus, Danilo Andrade and Klein, Stefan
  and Walsum, Theo van
author:
- given: Luisa
  family: Sanchez Brea
- given: Danilo Andrade
  family: De Jesus
- given: Stefan
  family: Klein
- given: Theo van
  family: Walsum
date: 2020-09-21
address: 
container-title: Proceedings of the Third Conference on Medical Imaging with Deep
  Learning
volume: '121'
genre: inproceedings
issued:
  date-parts:
  - 2020
  - 9
  - 21
pdf: http://proceedings.mlr.press/v121/sanchez-brea20a/sanchez-brea20a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
