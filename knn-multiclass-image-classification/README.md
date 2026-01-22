# 🔢 Multiclass Image Classification using K-Nearest Neighbors (KNN)

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-102230)
![Pattern Recognition](https://img.shields.io/badge/Pattern_Recognition-4CAF50)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![KNN](https://img.shields.io/badge/KNN-1565C0)

A pattern recognition project that applies the **K-Nearest Neighbors (KNN)** algorithm for **multiclass image classification**, focusing on distance-based learning and performance evaluation.

---

## 📌 Overview

This project demonstrates the use of the **K-Nearest Neighbors (KNN)** algorithm to solve a **multiclass classification problem**, a fundamental task in machine learning and pattern recognition.

The approach classifies samples based on **distance metrics (L1 and L2)** and majority voting among nearest neighbors, without any model training or parameter learning.

---

## 🎯 Objectives

- Implement a KNN-based classifier for multiclass classification  
- Compare distance metrics (L1 vs L2)  
- Analyze the effect of different values of *k*  
- Evaluate classification performance using cross-validation  

---

## 🧠 Model Description

The **K-Nearest Neighbors (KNN)** classifier:
- Stores all training samples
- Computes distances between test samples and training data
- Selects the *k* closest neighbors
- Predicts the class using majority voting  

> This method is **non-parametric** and does **not** involve neural networks or gradient-based training.

---

## 📂 Dataset

- Image dataset organized into multiple classes  
- Images are:
  - Converted to grayscale  
  - Resized to a fixed resolution  
  - Flattened into feature vectors  

The dataset is suitable for evaluating distance-based multiclass classification.

---

## ⚙️ Implementation Details

- **Language:** Python  
- **Algorithm:** K-Nearest Neighbors (KNN)  
- **Distance Metrics:** L1 (Manhattan), L2 (Euclidean)  
- **Environment:** Jupyter Notebook  

Evaluation setup includes:
- Manual KNN implementation  
- Cross-validation for performance estimation  
- Accuracy as the evaluation metric  

---

## 📈 Results

- The KNN classifier successfully performs multiclass image classification  
- Classification accuracy varies with the choice of *k* and distance metric  
- Demonstrates the strengths and limitations of distance-based classifiers  

---

## 🧪 Key Learnings

- How KNN performs classification using distance metrics  
- Impact of feature representation on KNN performance  
- Trade-offs between simplicity and scalability in KNN  

---

## 👤 Author

**Sajidur Rahman Sajid**  
Computer Science & Engineering (CSE)  
Aspiring **AI / Machine Learning Engineer**
