# UrbanSight Analytics: Smart City Demographics & Security 🏙️👁️

> **🏆 Presented at the 17th Student Research Conference on Applied Computing (SRC 2026) at Zayed University.**

## Overview
UrbanSight Analytics is a comprehensive, real-time "AI Profiler" designed for intelligent surveillance and modern Human-Computer Interaction (HCI). Moving beyond traditional biometric systems, this project emphasizes **soft biometrics**—extracting semantic descriptions of subjects in unconstrained environments. 

The system accurately profiles physical and behavioral traits, addressing the inherent complexities of varying lighting, pose, and occlusion in real-world video feeds.

## Key Features
* **Facial & Demographic Profiling:** Real-time detection of Age, Gender (via Xception), and Race/Ethnicity.
* **Physical Attribute Segmentation:** Precise Hair segmentation (using U-Net) and Skin Tone analysis.
* **Apparel Recognition:** Clothing attribute and color detection using Vision Transformers (ViT) and KNN classifiers.
* **Optimized Inference:** Utilizes lightweight `.onnx`, `.keras`, and `.safetensors` models for efficient real-time execution.

## System Architecture & Models
This project integrates multiple specialized deep learning architectures:
* **Face Detection:** OpenCV Haarcascades (`haarcascade_frontalface_default.xml`)
* **Gender Classification:** Fine-tuned Xception Network
* **Hair Segmentation:** U-Net
* **Clothing/Color:** ViT (Vision Transformer) & KNN Classifier
* **Age & Race:** ONNX-optimized multi-class models

## Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/pattern_recognition_y4.git](https://github.com/yourusername/pattern_recognition_y4.git)
   cd pattern_recognition_y4
