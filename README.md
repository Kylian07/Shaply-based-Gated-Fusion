# A Shapley Value-based Gated Feature Fusion of Multi-branch Deep Learning Framework for Breast Cancer Screening of Thermal Images

[![Conference](https://img.shields.io/badge/Conference-AIIIMA%202025-blue.svg)](https://doi.org/10.1007/978-3-032-10990-3_3)  
📄 Accepted at the **4th International Conference on Artificial Intelligence over Infrared Images for Medical Applications (AIIIMA 2025)**

---

## 📝 Overview
This repository contains the official implementation of our paper:  
**"A Shapley Value-based Gated Feature Fusion of Multi-branch Deep Learning Framework for Breast Cancer Screening of Thermal Images"**  

We propose a **multi-branch hybrid deep learning framework** that simultaneously processes:
- Spatial-domain thermograms  
- Frequency-domain Power Spectral Density (PSD) representations  

A novel **Shapley Value-based Gated Fusion mechanism** adaptively integrates these features using a lightweight **MobileNetV3Small** backbone, achieving **state-of-the-art performance** on the **DMR-IR dataset**.

---

## 🚀 Key Features
- Multi-branch CNN framework for **joint spatial-frequency feature learning**  
- **Shapley Value-based Gated Fusion** for adaptive feature integration  
- Lightweight backbone (**MobileNetV3Small**) for efficiency in resource-constrained settings  
- Achieved **100% accuracy, precision, recall, and F1-score** on the **DMR-IR dataset**  

---

## 📊 Visualizations
### Model Architecture
<p align="center">
  <img src="assets/modelaimma2.png" alt="Model Architecture" width="600"/>
</p>

### Grad-CAM Interpretability
<p align="center">
  <img src="assets/aiimaagradcam.png" alt="GradCAM Results" width="600"/>
</p>

---

## 📂 Dataset
We use the **DMR-IR dataset** (Database for Mastology Research with Infrared Images):  
- Collected at the University Hospital of the Federal University of Fluminense, Brazil  
- Includes **640×480** thermal breast images from **32 patients**  
- Categories:
  - **Saudáveis (Healthy)**  
  - **Doentes (Pathological/Malignant)**  
- Data was split into **80% training** and **20% testing** with stratification  

---

## 📈 Results
| Method                  | Accuracy | Precision | Recall | F1-score |
|--------------------------|----------|-----------|--------|----------|
| Dharani et al. (2024)    | 0.9680   | -         | -      | -        |
| Nogales et al. (2024)    | 0.9385   | 0.9666    | -      | -        |
| Alshehri et al. (2023)   | 0.9980   | 0.9976    | 0.9985 | 0.9980   |
| Gupta et al. (2024)      | 0.9573   | -         | -      | -        |
| Khodadadi et al. (2025)  | 0.9865   | 0.9878    | 0.9979 | -        |
| Shojaedini et al. (2024) | 0.9230   | 0.9300    | -      | -        |
| Tang et al. (2025)       | 0.9860   | 0.9737    | 0.9867 | 0.9802   |
| Jayagayathri et al. (2025)| 0.9773  | 1.0000    | 0.9835 | 0.9787   |
| Lescarbeault et al. (2025)| 0.9620  | 0.9940    | 0.9500 | 0.9710   |
| Tsietso et al. (2023)    | 0.9048   | 0.9333    | -      | -        |
| **Proposed Model (2025)**| **1.0000** | **1.0000** | **1.0000** | **1.0000** |

---

## ✍️ Authors
- **Jotiraditya Banerjee** – Department of Power Engineering, Jadavpur University, India  
- **Rajdeep Pal** – Department of Artificial Intelligence and Machine Learning, St. Thomas College of Engineering and Technology, India  
- **Ram Sarkar** – Department of Computer Science and Engineering, Jadavpur University, India  

---

## ⚠️ Disclaimer
This repository is released for **academic research purposes only**.  
- The proposed model is **not intended for clinical or diagnostic use**.  
- Results are based on the **DMR-IR dataset** and may not generalize to other datasets or real-world scenarios without further validation.  
- Any use of this work in healthcare applications requires **proper regulatory approval and medical validation**.  
