# 🔢 Handwritten Digit Recognition using a Neural Network

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-FF6F00)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-4CAF50)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

A deep learning–based project that applies a **neural network** to recognize handwritten digits from image data, demonstrating core concepts of image classification using dense layers.

---

## 📌 Overview

This project focuses on designing and training a **neural network** for handwritten digit recognition, a classic task in machine learning and pattern recognition.

The model operates on **flattened grayscale images** and classifies digits into **10 classes (0–9)**. The emphasis is on **neural network training, evaluation, and performance analysis**, rather than convolution-based feature extraction.

---

## 🎯 Objectives

- Build a neural network for handwritten digit classification  
- Train and evaluate the model on digit image data  
- Understand the impact of hidden layers and activations  
- Analyze model performance and classification accuracy  

---

## 🧠 Model Architecture

The neural network consists of:
- An input layer using flattened image features  
- Multiple fully connected (dense) hidden layers  
- ReLU activation functions  
- A softmax output layer for multi-class classification  

> This project uses a **fully connected neural network** and does **not** include convolutional or pooling layers.

---

## 📂 Dataset

- **Dataset:** MNIST handwritten digit dataset  
- **Image Type:** Grayscale  
- **Classes:** Digits from `0` to `9`  
- **Input Shape:** 28×28 pixels (flattened to 784 features)

The dataset is preprocessed using:
- Normalization  
- Flattening of image data  
- Train-test splitting  

---

## ⚙️ Training Setup

- **Language:** Python  
- **Framework:** TensorFlow / Keras  
- **Environment:** Jupyter Notebook  

Training configuration includes:
- Loss Function: Categorical Cross-Entropy  
- Optimizer: Adam  
- Evaluation Metric: Accuracy  

---

## 📈 Results

- The neural network achieves **good classification accuracy** on unseen test data  
- Demonstrates that simple neural networks can perform effectively on digit recognition tasks  
- Serves as a solid baseline before exploring more advanced architectures  

---

## 🧪 Key Learnings

- How neural networks learn from flattened image data  
- Role of dense layers and activation functions  
- Importance of data preprocessing and normalization  

---

## 👤 Author

**Sajidur Rahman Sajid**  
Computer Science & Engineering (CSE)  
Aspiring **AI / Machine Learning Engineer**
