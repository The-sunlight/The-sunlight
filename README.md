## Hi there 👋
# Weichen Cheng

> Undergraduate researcher at the School of Artificial Intelligence, China University of Mining and Technology-Beijing.  
> Research interests: **Computer Vision**, **Semantic Segmentation**, **Rock Slope Crack Detection**, uncertainty-aware learning, and multimodal representation.

[![GitHub](https://img.shields.io/badge/GitHub-The--sunlight-24292f?logo=github)](https://github.com/The-sunlight)
[![arXiv](https://img.shields.io/badge/arXiv-2604.06728-b31b1b)](https://arxiv.org/abs/2604.06728)
[![Research](https://img.shields.io/badge/Focus-Computer%20Vision-2f6462)](#selected-work)

## About

I am interested in reliable perception for subtle and noisy real-world signals. My current work focuses on dense prediction for crack-like structures, domain-shift-aware evaluation, uncertainty-guided model analysis, and robust multimodal fusion.

I prefer protocol-first research practice: clear baselines, reproducible experiment logs, conservative claims, and visible error analysis.

## Visual Highlights

### Rock Slope Crack Segmentation

<p align="center">
  <img src="assets/crack_segmentation_overview.png" width="88%" alt="Rock slope crack segmentation research loop">
</p>

This project studies semantic segmentation of thin crack-like structures in real rock slope scenes. The central challenge is not only public-dataset accuracy, but the domain gap between broad public crack datasets and complex geological environments.

<p align="center">
  <img src="assets/crack_qualitative_results.png" width="88%" alt="Qualitative crack segmentation error audit panels">
</p>

The qualitative audit shows typical real-domain failure modes: low-contrast thin-crack false negatives and false positives caused by complex rock texture. These observations motivate error-type-aware data diagnosis, morphology-aware source selection, and conservative uncertainty-guided adaptation.

## Research Interests

- **Semantic Segmentation:** crack segmentation, thin-structure perception, dense prediction benchmarks.
- **Rock Slope Crack Detection:** geological hazard perception, real-domain error audit, morphology-aware data selection.
- **Uncertainty-aware Learning:** reliability estimation, hard sample routing, robust fusion and contrastive objectives.
- **Multimodal Representation:** text-image interaction, modality reliability, multimodal sarcasm detection.

## Selected Work

### URMF: Uncertainty-aware Robust Multimodal Fusion for Multimodal Sarcasm Detection

**Zhenyu Wang, Weichen Cheng, Weijia Li, Junjie Mou, Zongyou Zhao, Guoying Zhang**  
Accepted by ICIC 2026 · arXiv preprint

URMF models textual, visual, and interaction-aware representations with uncertainty estimates, then dynamically adjusts multimodal fusion to suppress unreliable evidence in multimodal sarcasm detection.

[arXiv](https://arxiv.org/abs/2604.06728) · [PDF](https://arxiv.org/pdf/2604.06728)

### Uncertainty-guided Crack Segmentation for Rock Slope Scenes

A MMSegmentation-based research codebase for crack segmentation, public-to-real transfer, real-domain error auditing, morphology-aware source selection, and uncertainty-guided anchored training. The main research loop fixes strong baselines first, evaluates real-domain transfer carefully, and uses error evidence to decide which optimization branches are worth keeping.

[Code](https://github.com/The-sunlight/mmseg-crack) · [Project Notes](https://github.com/The-sunlight/mmseg-crack/blob/main/docs/project/START_HERE.md) · [Experiment Log](https://github.com/The-sunlight/mmseg-crack/blob/main/docs/experiment_logs/crack_public_resplit_segformer_b3_journal_2026-04-13.md)

## Technical Stack

`Python` · `PyTorch` · `MMSegmentation` · `OpenMMLab` · `SegFormer` · `U-Net` · `DeepLabV3+` · `Experiment Protocols`

## GitHub Overview

![GitHub stats](https://github-readme-stats.vercel.app/api?username=The-sunlight&show_icons=true&hide_border=true&theme=default)

![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=The-sunlight&layout=compact&hide_border=true&theme=default)

