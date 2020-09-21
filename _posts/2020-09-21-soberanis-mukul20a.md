---
title: Uncertainty-based Graph Convolutional Networks for Organ Segmentation Refinement
abstract: 'Organ segmentation in CT volumes is an important pre-processing step in
  many computer assisted intervention and diagnosis methods. In recent years, convolutional
  neural networks have dominated the state of the art in this task. However, since
  this problem presents a challenging environment due to high variability in the organ’s
  shape and similarity between tissues, the generation of false negative and false
  positive regions in the output segmentation is a common issue. Recent works have
  shown that the uncertainty analysis of the model can provide us with useful information
  about potential errors in the segmentation. In this context, we proposed a segmentation
  refinement method based on uncertainty analysis and graph convolutional networks.
  We employ the uncertainty levels of the convolutional network in a particular input
  volume to formulate a semi-supervised graph learning problem that is solved by training
  a graph convolutional network. To test our method we refine the initial output of
  a 2D U-Net. We validate our framework with the NIH pancreas dataset and the spleen
  dataset of the medical segmentation decathlon. We show that our method outperfroms
  the state-of-the art CRF refinement method by improving the dice score by $1%$ for
  the pancreas and $2%$ for spleen, with respect to the original U-Net’s prediction.
  Finally, we discuss the results and current limitations of the model for future
  work in this research direction. For reproducibility purposes, we make our code
  publicly available: {https://github.com/rodsom22/gcn_refinement}.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: soberanis-mukul20a
month: 0
tex_title: Uncertainty-based Graph Convolutional Networks for Organ Segmentation Refinement
firstpage: 755
lastpage: 769
page: 755-769
order: 755
cycles: false
bibtex_author: Soberanis-Mukul, Roger D. and Navab, Nassir and Albarqouni, Shadi
author:
- given: Roger D.
  family: Soberanis-Mukul
- given: Nassir
  family: Navab
- given: Shadi
  family: Albarqouni
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
pdf: http://proceedings.mlr.press/v121/soberanis-mukul20a/soberanis-mukul20a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
