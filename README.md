<h1 align="center">🧠 Brain Tumor Detection using Deep Learning 🩺</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python" alt="Python Version">
  <img src="https://img.shields.io/badge/TensorFlow-Deep%20Learning-orange?logo=tensorflow">
  <img src="https://img.shields.io/badge/License-MIT-green?logo=open-source-initiative">
  <img src="https://img.shields.io/badge/Platform-Jupyter%20Notebook-lightgrey?logo=jupyter">
</p>

---

### 🌟 Overview

This project is a **deep learning-based medical image analysis system** that detects the presence of brain tumors from MRI scans using **Convolutional Neural Networks (CNNs)**.  
It showcases how **Artificial Intelligence** and **Computer Vision** can assist healthcare professionals by **automatically identifying abnormalities** in brain imaging data.

> 🧩 *The purpose of this project is to demonstrate how AI-driven image classification can be applied to medical imaging in a safe, educational, and transparent way.*

---

## 🚀 Features
✅ Automated tumor classification (Tumor / No Tumor)  
✅ End-to-end workflow: Preprocessing → Training → Evaluation → Visualization  
✅ Real-time prediction capability on unseen MRI scans  
✅ Visualization of **model accuracy**, **loss curves**, and **sample predictions**  
✅ Clean and modular **Jupyter Notebook** pipeline  

---

## 📂 Dataset
The dataset consists of **MRI Brain Scan Images**, divided into two classes:
- 🩸 **Tumor**
- 🧠 **No Tumor**

> Example source: [Kaggle – Brain MRI Images for Brain Tumor Detection](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)

---

## 🧠 Deep Learning Architecture

### 1️⃣ Preprocessing
- Image **resizing**, **normalization**, and **augmentation**
- Noise reduction and contrast adjustment using **OpenCV**
- Ensures balanced class representation

### 2️⃣ CNN Model Design
- Multiple **Convolutional + MaxPooling layers**
- **Dropout** layers to prevent overfitting  
- **Dense layers** for classification  
- **Softmax** output for multi-class probability distribution  

**Optimizer:** `Adam`  
**Loss Function:** `Categorical Crossentropy`  
**Evaluation Metric:** `Accuracy`

### 3️⃣ Model Training
- Epoch-wise training with **train-validation split**
- Live visualization of accuracy & loss
- Checkpoint saving for best-performing model

### 4️⃣ Evaluation
- Accuracy, Precision, Recall, and F1-Score  
- Confusion Matrix visualization  
- Prediction examples on test MRI scans  

---

## ⚙️ Installation & Setup

```bash
# Clone this repository
git clone https://github.com/your-username/brain-tumor-detection.git
cd brain-tumor-detection

# Install dependencies
pip install -r requirements.txt

# Run the project
jupyter notebook Brain_Tumor_Detection.ipynb
