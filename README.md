# Breast Cancer MRI Classification Project 🎗️

This repository contains my **Graduation Project II** for the Faculty of Artificial Intelligence at Al-Balqa Applied University.  
The project applies **state-of-the-art deep learning models** to classify **MRI breast scans** as **benign or malignant**, supporting early detection of breast cancer.

## 📌 Project Overview
Breast cancer remains one of the most common and dangerous diseases worldwide.  
Early detection significantly improves survival rates, but conventional methods (mammography, ultrasound, biopsy) suffer from high false positives/negatives and limited interpretability.

This project explores modern AI techniques to enhance diagnostic accuracy and reliability using **MRI images**.

## 🧠 Models Implemented
- **Vision Transformer (ViT)**
- **ViT + Kolmogorov–Arnold Networks (KAN)**
- **ResNet-50 v2 + KAN**

## ⚙️ Tools & Frameworks
- Python 3.11
- PyTorch 2.2+
- TorchVision (pretrained ViT-B/16, ResNet-50 v2)
- PyKAN (for symbolic Kolmogorov–Arnold Networks)
- Albumentations (data augmentation)
- scikit-learn (metrics, confusion matrix)
- Matplotlib & Seaborn (visualization)

## 📊 Results (Highlights)
| Model          | Validation Accuracy | Test Accuracy |
|----------------|---------------------|---------------|
| ViT-only       | 85.36%              | 87.75%        |
| ViT + KAN      | 91.43%              | 93.10%        |
| ResNet + KAN   | 81.30%              | 68.00%        |

✅ The **ViT + KAN hybrid** delivered the **best performance**, achieving **93.10% accuracy** on the test set.  
✅ KAN layers improved interpretability, allowing symbolic representations of decision-making.  


## 📂 Repository Structure
- `ResNet_KAN.ipynb` → Hybrid ResNet + KAN pipeline
- `VIT_KAN.ipynb` → Hybrid Vision Transformer + KAN pipeline
- `VIT_only.ipynb` → Vision Transformer baseline
- `FINAL.docx` → Complete project report
- `README.md` → Project description (this file)

## 🚀 Future Work
- Hyperparameter tuning of KAN layers
- Fusion of multi-modal MRI data (T1, T2, FLAIR)
- Explainable AI integration (Grad-CAM, SHAP)
- Clinical validation on hospital datasets
- Edge deployment with model quantization

---

🎗️ *This project aims to contribute to the fight against breast cancer by delivering AI-powered, explainable, and efficient diagnostic tools.*
