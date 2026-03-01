---
layout: page
title: "GeminiMol: Conformational Space Profiling for Molecular Representation"
description: A molecular representation method that enhances ligand-based drug discovery by profiling conformational space.
importance: 2
category: Molecular Representation
---

<div class="publications">

<h3 class="mt-0">Authors</h3>

<p>
Lin Wang, <strong>Shihang Wang</strong>, Hao Yang, Shiwei Li, Xinyu Wang, Yongqi Zhou, Siyuan Tian, Lu Liu, <a href="https://scholar.google.com.hk/citations?user=FZ3zkfcAAAAJ&hl=zh-CN">Fang Bai</a>
</p>

<p>
<em>Advanced Science</em>, 2024 &nbsp;|&nbsp; Volume 11, Issue 40, 2403998
</p>

<div class="links mb-3">
  <a href="https://onlinelibrary.wiley.com/doi/10.1002/advs.202403998" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener noreferrer">Paper</a>
  <a href="https://github.com/Wang-Lin-boop/GeminiMol" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener noreferrer">Code</a>
</div>

</div>

---

## Abstract

GeminiMol enhances generic molecular representation for AI-powered ligand-based drug discovery by profiling the conformational space of molecules. Instead of relying on single static molecular structures, GeminiMol systematically explores and encodes the three-dimensional conformational diversity of molecules, capturing the dynamic nature of molecular flexibility that is critical for biological activity.

---

## Method

GeminiMol introduces a novel approach to molecular representation:

- **Conformational Space Profiling**: Systematically generates and encodes multiple 3D conformations of each molecule
- **Multi-Conformer Encoding**: Uses deep learning to aggregate information from diverse conformations into a single comprehensive representation
- **Similarity Learning**: Trains the model to capture molecular similarities that are relevant to biological activity through contrastive learning
- **Generic Representation**: The learned representation transfers effectively across different downstream tasks

---

## Key Results

- **State-of-the-Art Performance**: Achieves top results on multiple molecular property prediction benchmarks
- **Ligand-Based Drug Discovery**: Significantly improves virtual screening performance for various drug targets
- **Conformational Sensitivity**: Captures activity-relevant conformational information that static representations miss
- **Broad Applicability**: Effective across diverse chemical spaces and drug discovery tasks

---

## BibTeX

```bibtex
@article{wang2024conformational,
  title={Conformational Space Profiling Enhances Generic Molecular Representation for AI-Powered Ligand-Based Drug Discovery},
  author={Wang, Lin and Wang, Shihang and Yang, Hao and Li, Shiwei and Wang, Xinyu and Zhou, Yongqi and Tian, Siyuan and Liu, Lu and Bai, Fang},
  journal={Advanced Science},
  volume={11},
  number={40},
  pages={2403998},
  year={2024},
  publisher={Wiley Online Library}
}
```
