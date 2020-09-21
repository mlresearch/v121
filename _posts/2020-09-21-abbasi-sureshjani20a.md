---
title: 4D Semantic Cardiac Magnetic Resonance Image Synthesis on XCAT Anatomical Model
abstract: We propose a hybrid controllable image generation method to synthesize anatomically
  meaningful 3D+t labeled Cardiac Magnetic Resonance (CMR) images. Our hybrid method
  takes the mechanistic 4D eXtended CArdiac Torso (XCAT) heart model as the anatomical
  ground truth and synthesizes CMR images via a data-driven Generative Adversarial
  Network (GAN). We employ the state-of-the-art SPatially Adaptive De-normalization
  (SPADE) technique for conditional image synthesis to preserve the semantic spatial
  information of ground truth anatomy. Using the parameterized motion model of the
  XCAT heart, we generate labels for 25 time frames of the heart for one cardiac cycle
  at 18 locations for the short axis view. Subsequently, realistic images are generated
  from these labels, with modality-specific features that are learned from real CMR
  image data. We demonstrate that style transfer from another cardiac image can be
  accomplished by using a style encoder network. Due to the flexibility of XCAT in
  creating new heart models, this approach can result in a realistic virtual population
  to address different challenges the medical image analysis research community is
  facing such as expensive data collection. Our proposed method has a great potential
  to synthesize 4D controllable CMR images with annotations and adaptable styles to
  be used in various supervised multi-site, multi-vendor applications in medical image
  analysis.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: abbasi-sureshjani20a
month: 0
tex_title: 4D Semantic Cardiac Magnetic Resonance Image Synthesis on XCAT Anatomical
  Model
firstpage: 6
lastpage: 18
page: 6-18
order: 6
cycles: false
bibtex_author: Abbasi-Sureshjani, Samaneh and Amirrajab, Sina and Lorenz, Cristian
  and Weese, Juergen and Pluim, Josien and Breeuwer, Marcel
author:
- given: Samaneh
  family: Abbasi-Sureshjani
- given: Sina
  family: Amirrajab
- given: Cristian
  family: Lorenz
- given: Juergen
  family: Weese
- given: Josien
  family: Pluim
- given: Marcel
  family: Breeuwer
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
pdf: http://proceedings.mlr.press/v121/abbasi-sureshjani20a/abbasi-sureshjani20a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
