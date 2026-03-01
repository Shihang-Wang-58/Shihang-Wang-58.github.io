---
layout: page
title: "DeepSA: Deep Learning-Driven Predictor of Compound Synthesis Accessibility"
description: A deep learning model that predicts the synthesis accessibility of compounds with high accuracy, helping researchers select cost-effective molecules for synthesis.
importance: 1
category: AI for Drug Design
github: https://github.com/Shihang-Wang-58/DeepSA
---

<div class="publications">

<h3 class="mt-0">Authors</h3>

<p>
<strong>Shihang Wang</strong>, Lin Wang, Fenglei Li, <a href="https://scholar.google.com.hk/citations?user=FZ3zkfcAAAAJ&hl=zh-CN">Fang Bai</a>
</p>

<p>
<em>Journal of Cheminformatics</em>, 2023
</p>

<div class="links mb-3">
  <a href="https://jcheminf.biomedcentral.com/articles/10.1186/s13321-023-00771-3" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener noreferrer">Paper</a>
  <a href="https://github.com/Shihang-Wang-58/DeepSA" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener noreferrer">Code</a>
  <a href="https://bailab.siais.shanghaitech.edu.cn/deepsa" class="btn btn-sm z-depth-0" role="button" target="_blank" rel="noopener noreferrer">Web Server</a>
</div>

</div>

---

## Abstract

DeepSA is proposed to predict synthesis accessibility of compounds, and has a much higher early enrichment rate in discriminating molecules that are difficult to synthesize. This helps users to select less expensive molecules for synthesis, thus reducing the time for drug discovery and development.

Traditional synthesis accessibility scoring methods like SAScore rely on fragment-based rules and often fail to capture the complex structural features that make a molecule hard to synthesize. DeepSA leverages deep learning to learn these complex patterns directly from molecular data, providing more reliable predictions of synthesis difficulty.

---

## Method

DeepSA employs a graph neural network (GNN) architecture to predict compound synthesis accessibility. The model takes molecular graphs as input, where atoms are represented as nodes and bonds as edges. Through multiple message-passing layers, the model learns rich representations of molecular structures that capture the intricate relationships between structural features and synthesis difficulty.

The key components of DeepSA include:

- **Molecular Graph Representation**: Compounds are encoded as molecular graphs with atom and bond features
- **Graph Neural Network**: Multi-layer message passing to capture structural patterns
- **Synthesis Accessibility Score**: A continuous score indicating the ease of synthesis

---

## Key Results

- **Superior Performance**: DeepSA achieves significantly higher early enrichment rates compared to existing methods like SAScore and SCScore
- **Broad Applicability**: The model generalizes well across diverse chemical spaces
- **Practical Utility**: Integrated into a web server for easy access by the research community
- **Drug Discovery Impact**: Helps reduce costs by filtering out synthetically intractable molecules early in the drug design pipeline

---

## BibTeX

```bibtex
@article{wang2023deepsa,
  title={DeepSA: a deep-learning driven predictor of compound synthesis accessibility},
  author={Wang, Shihang and Wang, Lin and Li, Fenglei and Bai, Fang},
  journal={Journal of Cheminformatics},
  volume={15},
  number={1},
  pages={103},
  year={2023},
  publisher={Springer},
  doi={10.1186/s13321-023-00771-3}
}
```
