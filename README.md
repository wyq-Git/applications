<div align=center>
  <h1>Applications</h1>
  <p><a href="./README_ZH.md">查看中文</a></p>
</div>

This repository provides a curated collection of AI application examples built with **MindSpore**, covering domains such as Computer Vision, NLP, GANs, Diffusion Models, LLMs, RAG, and Agents. Each case is organized by **domain**, **stage** (training, finetuning, inference), and **model**, offering reusable implementations for representative tasks. It serves as a practical reference for developers to explore and extend AI solutions within the MindSpore ecosystem.

## 📢 News

- **2025-11-07 [Feature Optimization]**：Repository refactored for clearer application navigation; added CI pipeline for more standardized contributions. ([*View details*](xxx))

## Prerequisites

Before starting this course, you should be familiar with:

- Basic Python programming
- Basic Linux commands
- Using Jupyter Notebook
- Using Docker images

You can take the [Prerequisite Test](exam_link) to assess your readiness.

## Environment Setup

To ensure all example code runs smoothly, set up your environment using one of the following methods.

### Install Dependencies

Confirm your Python version meets the course requirements, then run:

```bash
pip install -r requirements.txt
```

### Use Docker Image

Prebuilt Dockerfiles are provided to simplify environment setup.

You can find all course images in the [dockerfile](./dockerfile/) directory and pull the one that fits your hardware:

| Platform | Image Name     | Tag      | Description               | Dockerfile     |
| :------ | :-------------- | :------- | :------------------------ | :------------- |
| CPU     | xxx             | xxx      | xxx                       | xxx            |
| GPU     | xxx             | xxx      | xxx                       | xxx            |
| NPU     | xxx             | xxx      | xxx                       | xxx            |

For details, see [Using Docker Images](./dockerfile/README.md).

## Application List

| **Domain**  | **Stage**    | **Model**    | **Case**                     | **Cloud Lab** |
|-------------|--------------|--------------|------------------------------|---------------|
| CV          | Finetuning   | MobileNetV2  | [Garbage Classification](./cv/finetune/mobilenetv2/garbage_classification.ipynb) | [Launch Experiment](link) |
| CV          | Finetuning   | ResNet       | [Skin Disease Identification](./cv/finetune/resnet/skin_disease_identification.ipynb) | [Launch Experiment](link) |
| CV          | Finetuning   | ResNet       | [Chinese Herbal Classification](./cv/finetune/resnet/zhongyiyao_classification.ipynb) | [Launch Experiment](link) |
| GAN         | Finetuning   | CycleGAN     | [Bamboo Leaf Style Font Generation](./gan/finetune/cyclegan/bamboo_leaf_style_font_generation.ipynb) | [Launch Experiment](link) |
| GAN         | Inference    | CycleGAN     | [Mural Line Drawings Generation](./gan/inference/cyclegan/mural_restoration.ipynb) | [Launch Experiment](link) |
| LLM         | Finetuning   | GIT          | [Image Captioning](./gan/inference/cyclegan/mural_restoration.ipynb) | [Launch Experiment](link) |
| LLM         | Finetuning   | LayoutLMv2   | [Word Tagging for Scanned Receipts](./llm/finetune/layoutlmv2/Fine_tuning_LayoutLMv2ForTokenClassification_on_CORD.ipynb) | [Launch Experiment](link) |
| LLM         | Finetuning   | T5           | [Email Summarization](./llm/finetune/t5/Fine_tuning_English_T5_base_on_CNN_Daily_Mail_for_summarization.ipynb) | [Launch Experiment](link) |
| LLM         | Inference    | Audio Spectrogram Transformer | [Audio Classification](./llm/inference/audio_spectrogram_transformer/Audio%20Spectrogram%20Transformer.ipynb) | [Launch Experiment](link) |
| LLM         | Inference    | BEIT         | [Maksed Image Modelling](./llm/inference/beit/Understading_BeitForMaskedImageModeling_Mindspore.ipynb) | [Launch Experiment](link) |
| LLM         | Inference    | BERT         | [Named Identity Recognition](./llm/inference/bert/Bert_NER.ipynb) | [Launch Experiment](link) |
| LLM         | Inference    | GPT-J       | [Emotion Classification](./llm/inference/gptj/Inference_with_GPT_J_6B.ipynb) | [Launch Experiment](link) |
| LLM         | Inference    | SAM         | [Segmentation](./llm/inference/sam/SAM.ipynb) | [Launch Experiment](link) |
| LLM         | Inference    | TAPAS       | [Table Understanding](./llm/inference/tapas/TAPAS.ipynb) | [Launch Experiment](link) |


*“Cloud Lab” = interactive sandbox with prebuilt environment & resources.*

## Version Management

This repository is updated in sync with **MindSpore** and the **MindSpore NLP** Suite.

New releases of this repository are published approximately **every three months**.

| Branch/Version  | Python | MindSpore | MindSpore NLP |
| :------ | :----- |:------ |:------ |
| master | xxx    | xxx    | xxx    |
| r1.0   | xxx    | xxx    | xxx    |

## FAQ

- **Q1**：xxx
    - **A**：xxx

## Contributing

We welcome bug reports, suggestions, and code contributions via [Issues](Issue_link) or [PRs](PR_link). Please follow our submission guidelines — all PRs are reviewed and merged by @xing-yiren and another committer. Your contributions make the project stronger!

**Guidelines**: [Issue & PR Submission](WIKI_link)

## Contributors

Special thanks to all contributors for improving this project!

<div align=center style="margin-top: 30px;">
  <a href="https://github.com/mindspore-courses/applications/graphs/contributors">
    <img src="https://contrib.rocks/image?repo=mindspore-courses/applications" />
  </a>
</div>
