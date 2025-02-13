# Lung Cancer Detection Using Images

## 📌 Overview
This project leverages **Deep Learning** techniques to detect lung cancer using medical images (CT scans or X-rays). The model is trained using **Convolutional Neural Networks (CNNs)** and **Vision Transformers** to achieve high accuracy in classifying cancerous and non-cancerous lung scans.

## 🚀 Features
- **Deep Learning Model:** Utilizes CNNs and Vision Transformers for image classification.
- **High Accuracy:** Optimized model achieving state-of-the-art performance.
- **Efficient Preprocessing:** Data augmentation and normalization for better generalization.
- **Scalable Implementation:** Can be deployed in real-time medical diagnostic systems.

## 🏗️ Tech Stack
- **Python**
- **TensorFlow / PyTorch**
- **OpenCV**
- **Scikit-learn**
- **Matplotlib / Seaborn**
- **Google Cloud Platform (GCP)**
- **Jupyter Notebook**

## 📂 About the Dataset
This project uses the **LC25000** dataset, which consists of **25,000 histopathological images** of lung and colon tissue. The images were generated from HIPAA-compliant and validated sources and were augmented using the **Augmentor** package.

Dataset link: https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images

### 📊 Dataset Summary:
- **Total Images:** 25,000
- **Resolution:** 768 × 768 pixels (JPEG format)
- **Classes (5,000 images per class):**
  1. **Lung benign tissue**
  2. **Lung adenocarcinoma**
  3. **Lung squamous cell carcinoma**
  4. **Colon adenocarcinoma**
  5. **Colon benign tissue**

### 📌 Citation
If you use this dataset in your research, please credit the original authors:

**Original Article:**  
Borkowski AA, Bui MM, Thomas LB, Wilson CP, DeLand LA, Mastorides SM.  
**Lung and Colon Cancer Histopathological Image Dataset (LC25000).**  
[arXiv:1912.12142v1 [eess.IV], 2019](https://arxiv.org/abs/1912.12142v1)

### 📜 BibTeX Reference
```bibtex
@article{,
title= {LC25000 Lung and colon histopathological image dataset},
keywords= {cancer,histopathology},
author= {Andrew A. Borkowski, Marilyn M. Bui, L. Brannon Thomas, Catherine P. Wilson, Lauren A. DeLand, Stephen M. Mastorides},
url= {https://github.com/tampapath/lung_colon_image_set}
}
```

## 📊 Results & Performance
Achieved high accuracy (~95%) on the test set.
Improved model efficiency by reducing data size by 40% while maintaining performance.
Robust to variations in lung scans with enhanced generalization.

## 🔥 Future Improvements
Hyperparameter tuning to further improve accuracy.
Integration with cloud services (GCP/AWS) for real-time deployment.
Deployment as a web app for user-friendly access.
