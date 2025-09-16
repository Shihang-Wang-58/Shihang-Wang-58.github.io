---
layout: poster
title: "PhenoModel in 9th iHuman Conference"
date: 2024-10-15
category: AI
status: presented
conference: "9th iHuman Conference"
image: "/assets/img/posters/PhenoModel_poster.png"
preview: "/assets/img/posters/PhenoModel_poster.png"
pdf: "/assets/pdf/ml_drug_discovery_poster.pdf"
---

PhenoModel is a cutting-edge molecular representation foundation model that integrates cell phenotype data to enhance the characterization of molecules. By leveraging the rich information embedded in cell images, PhenoModel significantly improves performance in various drug discovery tasks, particularly in virtual screening. Based on PhenoModel, we developed an active compound screening pipeline called PhenoScreen to further screen other molecules with similar activities but novel scaffolds according to the known active compounds. For simple use, you can use PhenoScreen on a [webserver](https://bailab.siais.shanghaitech.edu.cn/services/phenomodel).

## Key Features

- Enhanced Molecular Representation: Combines molecular structure data with cell phenotype information to create a more comprehensive representation of molecules.
- Superior Performance in Virtual Screening: Demonstrates excellent performance in identifying active molecules across various targets, outperforming traditional methods.
- Flexible Application: Applicable to a wide range of tasks including molecular property prediction and phenotype-based drug discovery.

## Methods

- Molecular Feature Extraction: Uses a four-layer Weisfeiler-Lehman Network (WLN) pre-trained with GeminiMol weights to encode molecular structures into high-dimensional embeddings.
- Cell Image Feature Extraction: Applies a ViT model based on QFormer to encode cell images, incorporating a novel Quadrangle Attention mechanism to handle varying object sizes, shapes, and orientations.
- Dual-space Joint Training: Simultaneously trains molecular and image encoders using contrastive learning to align features and enhance model performance.
- Feature Fusion: Integrates molecular and cell image features to create a unified representation that captures both structural and activity-related information.
