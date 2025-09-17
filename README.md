# Breast Cancer MRI Classification 🎗️

This repository contains my **Graduation Project II** for the Faculty of Artificial Intelligence at Al-Balqa Applied University.  
The project applies **state-of-the-art deep learning models** to classify **MRI breast scans** as benign or malignant, supporting early detection of breast cancer.

---

## 📌 Project Overview
Breast cancer remains one of the leading causes of death worldwide.  
Traditional diagnostic methods (mammography, ultrasound, biopsy) suffer from limitations such as false positives/negatives and invasive procedures.  
This project explores modern **AI and deep learning models** to improve diagnostic accuracy and interpretability using **MRI imaging**.

---

## 🧠 Models Implemented
- **Convolutional Neural Networks (CNNs)**
- **Vision Transformer (ViT)**
- **ViT + Kolmogorov–Arnold Networks (KAN)**
- **ResNet-50 v2 + KAN**

---

## 📊 Dataset
We used the **Breast MRI Images for Breast Cancer Detection dataset** from Kaggle:  
🔗 [Breast MRI Images Dataset on Kaggle](https://www.kaggle.com/datasets/pritishsaha/breast-mri-images-for-breast-cancer-detection)  

**Description:**  
- Contains MRI images of breast scans.  
- Labeled into two categories: **Benign** and **Malignant**.  
- Images were resized to **224 × 224 pixels** and normalized.  
- Data augmentation was applied (rotation, flipping, zooming) to improve generalization.  

---

## ⚙️ Tools & Frameworks
- **Python 3.11**
- **PyTorch 2.2+**
- TorchVision (pretrained ViT-B/16, ResNet-50 v2)
- **PyKAN** (Kolmogorov–Arnold Networks)
- Albumentations (data augmentation)
- scikit-learn (metrics, confusion matrix)
- Matplotlib & Seaborn (visualization)

---

## 📈 Results (Highlights)
| Model          | Validation Accuracy | Test Accuracy |
|----------------|---------------------|---------------|
| ViT-only       | 85.36%              | 87.75%        |
| ViT + KAN      | 91.43%              | 93.10%        |
| ResNet + KAN   | 81.30%              | 68.00%        |

✅ The **ViT + KAN hybrid** achieved the best performance with **93.10% test accuracy**.  


🎗️ *This project aims to contribute to the fight against breast cancer by delivering AI-powered, explainable, and efficient diagnostic tools.*
