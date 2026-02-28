---
layout: page
title: "DeepPSA: Geometric Deep Learning for PROTAC Synthetic Accessibility"
description: A geometric deep learning model for predicting PROTAC synthetic accessibility.
img:
importance: 2
category: AI for Drug Design
---

<div class="publications">

<h3 class="mt-0">Authors</h3>

<p>
Ran Zhang, <strong>Shihang Wang</strong>, <a href="https://scholar.google.com/citations?user=WCGVnfYAAAAJ">Lin Wang</a>, Siyuan Tian, Yilin Tang, <a href="https://scholar.google.com.hk/citations?user=FZ3zkfcAAAAJ&hl=zh-CN">Fang Bai</a>
</p>

<p>
<em>Journal of Chemical Information and Modeling (JCIM)</em>, 2025
</p>

<div class="links mb-3">
  <a href="https://doi.org/10.1021/acs.jcim.5c00366" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener noreferrer">Paper</a>
</div>

</div>

---

## Abstract

DeepPSA is a geometric deep learning model specifically designed for predicting the synthetic accessibility of PROTACs (Proteolysis Targeting Chimeras). PROTACs are a promising new class of therapeutics that degrade target proteins rather than inhibiting them. However, their synthesis is often challenging due to their complex bifunctional structure. DeepPSA addresses this challenge by providing accurate predictions of synthesis difficulty.

---

## Method

DeepPSA employs geometric deep learning to capture the unique structural features of PROTACs:

- **3D Molecular Representation**: PROTACs are represented as 3D molecular graphs capturing spatial relationships
- **Geometric Neural Network**: A geometry-aware network that processes both topological and spatial information
- **PROTAC-Specific Features**: The model incorporates features specific to the three-component structure of PROTACs (warhead, linker, and E3 ligase ligand)
- **Synthesis Accessibility Score**: Outputs a continuous score indicating the synthetic difficulty of the PROTAC

---

## Key Results

- **PROTAC-Specific Predictions**: First dedicated model for PROTAC synthetic accessibility prediction
- **Geometric Awareness**: Captures 3D structural information critical for assessing PROTAC synthesis difficulty
- **Practical Utility**: Helps medicinal chemists prioritize PROTAC candidates for synthesis
- **Complementary to DeepSA**: Extends the synthesis accessibility prediction paradigm to the PROTAC modality

---

## BibTeX

```bibtex
@article{zhang2025deeppsa,
  title={DeepPSA: A Geometric Deep Learning Model for PROTAC Synthetic Accessibility Prediction},
  author={Zhang, Ran and Wang, Shihang and Wang, Lin and Tian, Siyuan and Tang, Yilin and Bai, Fang},
  journal={Journal of Chemical Information and Modeling},
  year={2025},
  doi={10.1021/acs.jcim.5c00366}
}
```
