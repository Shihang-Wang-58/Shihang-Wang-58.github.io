---
layout: page
title: "PhenoModel: A Multimodal Phenotypic Drug Design Foundation Model"
description: A molecular representation foundation model integrating cell phenotype data for virtual screening and active compound discovery.
importance: 1
category: AI for Drug Design
github: https://github.com/Shihang-Wang-58/PhenoScreen
---

<div class="publications">

<h3 class="mt-0">Authors</h3>

<p>
<strong>Shihang Wang</strong>, Qilei Han, Weichen Qin, Lin Wang, Junhong Yuan, Yiqun Zhao, Pengxuan Ren, Yunze Zhang, Yilin Tang, Ruifeng Li, et al.
</p>

<p>
<em>Acta Pharmacologica Sinica B (APSB)</em>, 2025
</p>

<div class="links mb-3">
  <a href="https://www.sciencedirect.com/science/article/pii/S2211383525006446" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener noreferrer">Paper</a>
  <a href="https://github.com/Shihang-Wang-58/PhenoScreen" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener noreferrer">Code</a>
  <a href="https://mp.weixin.qq.com/s/uF3xh_dgTkcCbNDD_JpezA" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener noreferrer">中文解读</a>
</div>

</div>

---

## Abstract

PhenoModel is a cutting-edge molecular representation foundation model that integrates cell phenotype data to enhance the characterization of molecules. By leveraging the rich information embedded in cell images, PhenoModel significantly improves performance in various drug discovery tasks, particularly in virtual screening.

Based on PhenoModel, we developed an active compound screening pipeline called **PhenoScreen** to further screen other molecules with similar activities but novel scaffolds according to the known active compounds.

---

## Method

PhenoModel is built on a **dual-space contrastive learning framework** that links chemical perturbations to cellular morphology:

- **Chemical Space**: Molecular structures are encoded using graph neural networks to capture chemical properties
- **Phenotypic Space**: Cell painting images are processed using vision encoders to capture cellular morphological responses to chemical perturbations
- **Contrastive Learning**: The two spaces are aligned through contrastive learning, creating a unified representation that captures both chemical and phenotypic information
- **PhenoScreen Pipeline**: An active compound screening pipeline that leverages the learned representation to identify molecules with similar biological activities but novel scaffolds

---

## Key Results

- **Enhanced Molecular Representation**: PhenoModel captures phenotypic information that traditional molecular representations miss
- **Improved Virtual Screening**: Significant performance gains across multiple drug discovery benchmarks
- **Novel Active Compound Discovery**: Successfully identified novel potential inhibitors of multiple cancer cells
- **Foundation Model**: The pretrained model can be fine-tuned for various downstream drug discovery tasks

---

## BibTeX

```bibtex
@article{wang2024phenomodel,
  title={PhenoModel: A multimodal phenotypic drug design foundation model for discovering novel potential inhibitors of multiple cancer cells},
  author={Wang, Shihang and Han, Qilei and Qin, Weichen and Wang, Lin and Yuan, Junhong and Zhao, Yiqun and Ren, Pengxuan and Zhang, Yunze and Tang, Yilin and Li, Ruifeng and others},
  journal={Acta Pharmacologica Sinica B},
  year={2025},
  publisher={Elsevier}
}
```
