## Hi there 👋

# Weichen Cheng

> Undergraduate researcher at the School of Artificial Intelligence, China University of Mining and Technology-Beijing.  
> Research interests: **Computer Vision**, **Semantic Segmentation**, **Rock Slope Crack Detection**, real-world model evaluation, and multimodal representation.

[![GitHub](https://img.shields.io/badge/GitHub-The--sunlight-24292f?logo=github)](https://github.com/The-sunlight)
[![arXiv](https://img.shields.io/badge/arXiv-2604.06728-b31b1b)](https://arxiv.org/abs/2604.06728)
[![Research](https://img.shields.io/badge/Focus-Computer%20Vision-2f6462)](#selected-work)

## About

I am interested in reliable perception for subtle and noisy real-world signals. My current work focuses on dense prediction for crack-like structures, public-to-real domain shift, real-domain error analysis, and robust multimodal fusion.

I prefer protocol-first research practice: clear baselines, reproducible experiment logs, conservative claims, and visible error analysis.

## Research Interests

- **Semantic Segmentation:** crack segmentation, thin-structure perception, dense prediction benchmarks.
- **Rock Slope Crack Detection:** geological hazard perception, real-domain error audit, morphology-aware data selection.
- **Robust Visual Perception:** domain shift, real-domain error analysis, thin-structure segmentation, and reliable model evaluation.
- **Multimodal Representation:** text-image interaction, modality reliability, multimodal sarcasm detection.

## Selected Work

### URMF: Uncertainty-aware Robust Multimodal Fusion for Multimodal Sarcasm Detection

**Zhenyu Wang, Weichen Cheng, Weijia Li, Junjie Mou, Zongyou Zhao, Guoying Zhang**  
Accepted by ICIC 2026 · arXiv preprint

URMF models textual, visual, and interaction-aware representations with uncertainty estimates, then dynamically adjusts multimodal fusion to suppress unreliable evidence in multimodal sarcasm detection.

[arXiv](https://arxiv.org/abs/2604.06728) · [PDF](https://arxiv.org/pdf/2604.06728)

### Morphology-Guided Cross-Domain Crack Segmentation of Mining Slope Images with Limited Target Annotations

A MMSegmentation-based research codebase for crack segmentation, public-to-real transfer, and real-domain error analysis. The project focuses on building strong segmentation baselines, evaluating domain shift from public crack datasets to real mining slope scenes, and analyzing typical failure modes such as missed thin cracks, broken connectivity, and false positives caused by complex rock textures.

The current data-side direction is morphology-guided source adaptation: instead of selecting public source images by whole-image visual similarity, the project audits crack-centric morphology such as skeleton length, width, thin-crack ratio, connected components, continuity, local contrast, and nearby texture complexity.

[Code](https://github.com/The-sunlight/mmseg-crack) · [Project Notes](https://github.com/The-sunlight/mmseg-crack/blob/main/docs/project/START_HERE.md) · [Experiment Log](https://github.com/The-sunlight/mmseg-crack/blob/main/docs/project/logs/experiment_log.md)

## Technical Stack

`Python` · `PyTorch` · `MMSegmentation` · `OpenMMLab` · `SegFormer` · `U-Net` · `DeepLabV3+` · `Experiment Protocols`

## GitHub Overview

![GitHub stats](https://github-readme-stats.vercel.app/api?username=The-sunlight&show_icons=true&hide_border=true&theme=default)

![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=The-sunlight&layout=compact&hide_border=true&theme=default)
