# NECOMIMI: Neural-Cognitive Multimodal EEG-Informed Image Generation with Diffusion Models
[![arXiv](https://img.shields.io/badge/arXiv-2410.00712-b31b1b.svg?style=flat-square)](https://arxiv.org/abs/2410.00712)  
## Abstract
NECOMIMI introduces a groundbreaking framework for generating images directly from EEG signals using advanced diffusion models. This work not only pushes the boundaries of EEG-image classification but extends into image generation, presenting a novel EEG encoder, NERV, that shows state-of-the-art performance across multiple zero-shot classification tasks.
![2024-12-02 09-38-43 的螢幕擷圖](https://github.com/user-attachments/assets/73f39ff1-e874-43b5-a953-fbfeacadf5e3)

## Introduction
EEG has been a valuable tool in clinical settings, like diagnosing epilepsy and depression. However, with technological advancements, its application has expanded into real-time brain function analysis and now, into the challenging field of image generation from neural signals.

## Methodology
![2024-12-02 09-39-15 的螢幕擷圖](https://github.com/user-attachments/assets/129e02b3-6824-4ce9-8057-ecd3d2679d04)

This paper describes a comprehensive methodology that combines EEG signal processing and diffusion models to generate images. We introduce a novel two-stage image generation process and establish the CAT Score as a new metric tailored for EEG-to-image evaluation, setting a benchmark on the ThingsEEG dataset.
![2024-12-02 09-40-00 的螢幕擷圖](https://github.com/user-attachments/assets/dea2321b-4cb0-45c9-b9f2-9c3e653fbd62)

## Key Contributions
- Introduction of the NERV EEG encoder that demonstrates exceptional performance in EEG-based image generation.
- Development of a two-stage generative framework that enhances image quality and semantic accuracy.
- Proposal of the Category-based Assessment Table (CAT) Score for evaluating EEG-informed image generation.

## Experiments and Findings
Experiments demonstrate NERV's effectiveness across several zero-shot classification tasks, with a detailed exploration of the conceptual challenges in translating EEG data into precise visual representations. Despite its advancements, the generated images predominantly abstract, highlighting the inherent difficulties in processing EEG signals.

## Citation
Hope this results and idea is helpful. I would appreciate you citing us in your paper, and the github.

```
@article{chen2024necomimi,
  title={NECOMIMI: Neural-Cognitive Multimodal EEG-informed Image Generation with Diffusion Models},
  author={Chen, Chi-Sheng},
  journal={arXiv preprint arXiv:2410.00712},
  year={2024}
}
```
