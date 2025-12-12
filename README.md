# Knee Osteoarthritis Classification Using Deep Learning

This repository presents a deep learning–based approach for automated classification of **Knee Osteoarthritis (OA)** severity from X-ray images using a **transfer learning framework** built on the **Xception architecture**.

The project was developed as part of **AI700-001 (Fall 2025)** at **Long Island University, Brooklyn**.

---

## 📌 Project Overview

Knee Osteoarthritis is a degenerative joint disease that affects millions worldwide. Manual grading of OA severity from X-rays is subjective and time-consuming.  
This project explores an **end-to-end deep learning solution** that balances:

- Classification performance  
- Computational efficiency  
- Model explainability (via Grad-CAM)

The system classifies knee X-rays into **five OA severity grades**:
- Healthy (Grade 0)
- Doubtful (Grade 1)
- Minimal (Grade 2)
- Moderate (Grade 3)
- Severe (Grade 4)

---

## 🧠 Methodology

- **Model Architecture:** Xception (pre-trained on ImageNet)
- **Learning Strategy:** Transfer learning with fine-tuning
- **Loss Function:** Categorical Cross-Entropy
- **Optimizer:** Adam
- **Data Augmentation:** Rotation, flipping, zoom
- **Class Imbalance Handling:** Class weighting
- **Explainability:** Grad-CAM heatmap visualization

---

## 📊 Results

- **Test Accuracy:** ~60.6%
- **Test Loss:** 0.8368
- Best performance on **Healthy** and **Severe** classes
- Mid-stage OA grades (1–3) showed higher confusion
- Grad-CAM confirmed attention on clinically relevant joint regions

---

## 🔍 Research Contribution

- Demonstrates effective OA classification using a **single, lightweight CNN**
- Provides **model interpretability**, improving clinical trust
- Reduces computational overhead compared to multi-stage pipelines
- Suitable for deployment in **resource-constrained environments**

---


