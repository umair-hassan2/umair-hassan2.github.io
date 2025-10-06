---
permalink: /portfolio/
title: "Portfolio"
author_profile: true
---

## Research Projects

### ViT-Insight: Vision Transformer Attention Explorer (2025)

Interactive visualization of per-layer attention in ViT models, tracing how input patches collectively contribute to model predictions across layers and heads.

**Key Features:**
- Multi-label support for comprehensive analysis
- Layer-range selection for targeted exploration  
- Customizable heatmap overlays for detailed visualization
- Dynamic GIF generation showing layer-wise attention evolution
- Attention Rollout computation for understanding decision pathways

**Impact:** Enhanced transparency and trust in transformer-based vision models, providing a tool for explainable AI research and evaluation of vision-language alignment.

**Links:** [GitHub](https://github.com/umair-hassan2/vit-insight) | [Demo](https://vit-insight-demo.vercel.app) (Coming Soon)

---

### Valorant Object Detection with Google PaliGemma (2025)

Fine-tuned Google PaliGemma-2 (3B multimodal model) using QLoRA (4-bit quantization) for domain-specific object detection in Valorant gameplay.

**Technical Implementation:**
- Model: Google PaliGemma-2 (3B parameters)
- Fine-tuning: QLoRA (4-bit quantization) for efficient training
- Framework: Hugging Face Processor + Model APIs
- Evaluation: IoU, mAP@[0.50:0.95], AP@0.50/0.75, Accuracy, and Recall

**Results:**
- 61% improvement in overall mAP
- 75% improvement on small objects (critical for gameplay detection)
- Public release on Hugging Face for reproducibility and benchmarking

**Links:** [GitHub](https://github.com/umair-hassan2/paligemma-3b-finetuning) | [Hugging Face Model](https://huggingface.co/umairhassan02/paligemma2_finetuned) (Coming Soon)
