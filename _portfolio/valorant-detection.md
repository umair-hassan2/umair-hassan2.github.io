---
title: "Valorant Object Detection with Google PaliGemma"
excerpt: "Fine-tuned Google PaliGemma-2 for domain-specific object detection in Valorant gameplay using QLoRA and Hugging Face APIs."
collection: portfolio
date: 2025-01-01
---

## Valorant Object Detection with Google PaliGemma (2025)

Fine-tuned Google PaliGemma-2 (3B multimodal model) using QLoRA (4-bit quantization) for domain-specific object detection in Valorant gameplay.

### Technical Implementation:
- **Model**: Google PaliGemma-2 (3B parameters)
- **Fine-tuning**: QLoRA (4-bit quantization) for efficient training
- **Framework**: Hugging Face Processor + Model APIs
- **Evaluation**: IoU, mAP@[0.50:0.95], AP@0.50/0.75, Accuracy, and Recall

### Results:
- **61% improvement** in overall mAP
- **75% improvement** on small objects (critical for gameplay detection)
- **Public release** on Hugging Face for reproducibility and benchmarking

### Links:
- [GitHub Repository](https://github.com/umair-hassan2/valorant-detection)
- [Hugging Face Model](https://huggingface.co/umair-hassan2/valorant-paligemma) (Coming Soon)
