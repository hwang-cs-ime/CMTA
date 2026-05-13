# CMTA
This is the official code for ``CMTA: Leveraging Cross-Modal Temporal Artifacts for Generalizable AI-Generated Video Detection''


### [CMTA: Leveraging Cross-Modal Temporal Artifacts for Generalizable AI-Generated Video Detection](https://arxiv.org/abs/2605.00630)
Official PyTorch implementation of the paper: **"CMTA: Leveraging Cross-Modal Temporal Artifacts for Generalizable AI-Generated Video Detection"**.

[![arXiv](https://img.shields.io/badge/arXiv-2605.00630-b31b1b.svg)](https://arxiv.org/abs/2605.00630)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 📌 Introduction

<div align="justify">
The proliferation of advanced AI video synthesis techniques poses an unprecedented challenge to digital video authenticity. Existing AI-generated video (AIGV) detection methods primarily focus on uni-modal or spatiotemporal artifacts, but they overlook the rich cues within the visual-textual cross-modal space, especially the temporal stability of semantic alignment. In this work, we identify a distinctive fingerprint in AIGVs, termed <b>cross-modal temporal artifact (CMTA)</b>. Unlike real videos that exhibit natural temporal fluctuations in cross-modal alignment due to semantic variations, AIGVs display unnaturally stable semantic trajectories governed by given input prompts. To bridge this gap, we propose the CMTA framework, a cross-modal detection approach that captures these unique temporal artifacts through joint cross-modal embedding and multi-grained temporal modeling. Specifically, CMTA leverages BLIP to generate frame-level image captions and utilizes CLIP to extract corresponding visual-textual representations. A coarse-grained temporal modeling branch is then designed to characterize temporal fluctuations in cross-modal alignment with a GRU. In parallel, a fine-grained branch is constructed to capture intricate inter-frame variations from integrated visual-textual features with a Transformer encoder.
</div>



---

## 🚀 News
* **[2026.05]** Inference code and Pre-trained models will be released!
