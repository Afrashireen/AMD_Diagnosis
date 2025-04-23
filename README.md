# Interpretable AI for Diagnosis of Age-Related Macular Degeneration

# Project Overview:

This project aims to create an interpretable, AI-based system to diagnose Age-Related Macular Degeneration (AMD) from fundus images. The solution combines the powerful image classification abilities of EfficientNet-B0 with Explainable AI (XAI) techniques like LIME and Grad-CAM++ to ensure clinical transparency and trust.

# Abstract:

AMD is a major cause of blindness in the elderly. While AI can assist in automated diagnosis, black-box models hinder medical adoption. This project presents a system that integrates EfficientNet-B0 for classification and XAI tools (LIME, Grad-CAM++) for interpretability—offering both high accuracy (98.33%) and clinician-friendly visual explanations.

# Methodology:

1. Data Preprocessing
Normalization
Contrast enhancement
Image resizing

2. Model: EfficientNet-B0
Transfer learning approach
Classifies fundus images into AMD or Non-AMD

3. Explainability
LIME: Shows region influence using color overlays
Grad-CAM++: Heatmaps to localize key retinal areas influencing decisions

# Performance:

Metric	Score
Accuracy	98.33%
Precision	98.37%
Recall	98.33%
F1-Score	98.32%

# Future Scope:

Integration of OCT scans for multi-modal diagnosis
Cloud and mobile app deployment for remote AMD screening
Real-world validation in hospitals and telemedicine setups
