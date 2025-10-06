---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Download CV
[Download PDF]({{ base_path }}/files/cv.pdf){: .btn .btn--primary .btn--large}

## Education
**Punjab University College of IT (PUCIT), Lahore, Pakistan**  
Bachelor of Science in Software Engineering (2020–2024)  
CGPA: 3.71 / 4.00

**Relevant Coursework:** Data Structures & Algorithms, Distributed Systems, Databases, Machine Learning, AI & Computer Vision

## Work Experience

**Motive Inc. (formerly KeepTruckin), Backend Software Engineer (L2)**  
*Aug 2024–Present | Remote, San Francisco, CA*

- Spearheaded automation for promotional campaigns (Ruby on Rails, Go, PostgreSQL), boosting ATPV from $500M → $800M and raising in-network transactions from 42% → 55%, saving $1M+ in discounts.
- Built a secure SFTP/FTP integration library in Ruby and data ingestion pipelines (250K records/day) with AWS S3, SQS, Docker, and Kubernetes.
- Integrated an OCR model into Mastercard transaction spend breakdown using customer receipts, boosting categorization accuracy and reducing financial discrepancies.
- Acted as primary on-call engineer for transaction gateways, pricing pipelines, and APIs, leveraging Datadog, Kibana, and Python to triage and resolve live issues under strict SLAs.

**Teaching Assistant Roles**
- CC-211 Object Oriented Programming, Teaching Assistant (Spring 2024)
- CC-211-L Object Oriented Programming Lab, Teaching Assistant (Spring 2024)

## Research Projects

**ViT-Insight: Vision Transformer Attention Explorer (2025)**
- Developed an interactive platform to visualize per-layer attention maps and compute Attention Rollout in ViT models
- Implemented multi-label support, layer-range selection, and customizable heatmap overlays
- Generated dynamic GIFs to demonstrate layer-wise attention evolution
- Enhanced transparency and trust in transformer-based vision models

**Valorant Object Detection with Google PaliGemma (2025)**
- Fine-tuned Google PaliGemma-2 (3B multimodal model) using QLoRA (4-bit quantization)
- Built inference pipeline with Hugging Face Processor + Model APIs
- Achieved 61% improvement in overall mAP; largest gains on small objects (+75%)
- Released fine-tuned model publicly on Hugging Face for reproducibility

## Publications
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

## Achievements
- Represented Pakistan at the ICPC Asia West finals
- Secured Gold (2024) and Silver (2025) medals at the ICPC Asia Topi Regionals
- Ranked 7th nationally (solo) in Meta HackerCup 2023
- Recognized among the Top 1% IT graduates by HEC Pakistan
- Multiple podium finishes in national programming competitions (PUCON'23, INMIC'24, DAIRA'24, Electrocon'24, Technocon'24, BrainX'24)

## Community Involvement
- PUCON'24 Programming Competition, Judge & Problem Setter (June 2024)
- Google Developers Student Club PUCIT, Mentor (April 2024-June 2024)

## Skills
- **Programming Languages:** Python, Ruby, Go, JavaScript, Java, C++
- **Machine Learning:** PyTorch, Hugging Face, Transformers, Computer Vision
- **Backend Technologies:** Ruby on Rails, PostgreSQL, AWS (S3, SQS), Docker, Kubernetes
- **Tools:** Git, Datadog, Kibana, Jupyter Notebooks, Linux
