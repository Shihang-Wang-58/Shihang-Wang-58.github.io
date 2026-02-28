---
layout: page
title: "DeepmRNALoc: Deep Learning-Based mRNA Subcellular Localization Predictor"
description: A novel predictor of eukaryotic mRNA subcellular localization based on deep learning.
img:
importance: 3
category: AI for Drug Design
---

<div class="publications">

<h3 class="mt-0">Authors</h3>

<p>
<strong>Shihang Wang</strong>, Zhehan Shen, Taigang Liu, Wei Long, Linhua Jiang, <a href="https://scholar.google.com/citations?user=1sdUrZMAAAAJ&hl=zh-CN">Sihua Peng</a>
</p>

<p>
<em>Molecules</em>, 2023 &nbsp;|&nbsp; Volume 28, Issue 5, 2284
</p>

<div class="links mb-3">
  <a href="https://www.mdpi.com/1420-3049/28/5/2284" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener noreferrer">Paper</a>
</div>

</div>

---

## Abstract

DeepmRNALoc is a novel computational tool designed to predict the subcellular localization of eukaryotic mRNAs using deep learning. Understanding where mRNAs are localized within cells is crucial for comprehending gene regulation and cellular function. Traditional experimental methods for determining mRNA localization are time-consuming and expensive, making computational prediction methods highly valuable.

---

## Method

DeepmRNALoc leverages deep learning to learn sequence-level features of mRNAs that determine their subcellular localization:

- **Sequence Encoding**: mRNA sequences are encoded using multiple representation schemes to capture diverse sequential features
- **Deep Neural Network**: A multi-layer neural network architecture processes the encoded sequences to learn complex localization patterns
- **Multi-Label Prediction**: The model supports prediction of multiple subcellular localizations, reflecting the biological reality that mRNAs can localize to multiple compartments

---

## Key Results

- **High Accuracy**: DeepmRNALoc achieves competitive prediction performance compared to existing methods
- **Multi-Label Support**: Capable of predicting multiple localization sites for a single mRNA
- **Feature Learning**: Automatically learns relevant sequence features without manual feature engineering
- **Practical Tool**: Provides an easy-to-use tool for the bioinformatics community

---

## BibTeX

```bibtex
@article{wang2023deepmrnaloc,
  title={DeepmRNALoc: a novel predictor of eukaryotic mRNA subcellular localization based on deep learning},
  author={Wang, Shihang and Shen, Zhehan and Liu, Taigang and Long, Wei and Jiang, Linhua and Peng, Sihua},
  journal={Molecules},
  volume={28},
  number={5},
  pages={2284},
  year={2023},
  publisher={MDPI}
}
```
