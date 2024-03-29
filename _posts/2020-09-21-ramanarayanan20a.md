---
title: 'MAC-ReconNet: A Multiple Acquisition Context based Convolutional Neural Network
  for MR Image Reconstruction using Dynamic Weight Prediction'
abstract: Convolutional Neural network-based MR reconstruction methods have shown
  to provide fast and high quality reconstructions. A primary drawback with a CNN-based
  model is that it lacks flexibility and can effectively operate only for a specific
  acquisition context limiting practical applicability. By acquisition context, we
  mean a specific combination of three input settings considered namely, the anatomy
  under study, undersampling mask pattern and acceleration factor for undersampling.
  The model could be trained jointly on images combining multiple contexts. However
  the model does not meet the performance of context specific models nor extensible
  to contexts unseen at train time. This necessitates a modification to the existing
  architecture in generating context specific weights so as to incorporate flexibility
  to multiple contexts. We propose a multiple acquisition context based network, called
  MAC-ReconNet for MRI reconstruction, flexible to multiple acquisition contexts and
  generalizable to unseen contexts for applicability in real scenarios. The proposed
  network has an MRI reconstruction module and a dynamic weight prediction (DWP) module.
  The DWP module takes the corresponding acquisition context information as input
  and learns the context-specific weights of the reconstruction module which changes
  dynamically with context at run time. We show that the proposed approach can handle
  multiple contexts based on cardiac and brain datasets, Gaussian and Cartesian undersampling
  patterns and five acceleration factors. The proposed network outperforms the naive
  jointly trained model and gives competitive results with the context-specific models
  both quantitatively and qualitatively. We also demonstrate the generalizability
  of our model by testing on contexts unseen at train time.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: ramanarayanan20a
month: 0
tex_title: 'MAC-ReconNet: A Multiple Acquisition Context based Convolutional Neural
  Network for MR Image Reconstruction using Dynamic Weight Prediction'
firstpage: 696
lastpage: 708
page: 696-708
order: 696
cycles: false
bibtex_author: Ramanarayanan, Sriprabha and Murugesan, Balamurali and Ram, Keerthi
  and Sivaprakasam, Mohanasankar
author:
- given: Sriprabha
  family: Ramanarayanan
- given: Balamurali
  family: Murugesan
- given: Keerthi
  family: Ram
- given: Mohanasankar
  family: Sivaprakasam
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
pdf: http://proceedings.mlr.press/v121/ramanarayanan20a/ramanarayanan20a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
