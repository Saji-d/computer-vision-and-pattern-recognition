# 🙂 Face Recognition using LBPH (OpenCV)

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Face Recognition](https://img.shields.io/badge/Face%20Recognition-4CAF50)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)

A classical computer vision project that implements face recognition using OpenCV’s Local Binary Patterns Histogram (LBPH) algorithm, emphasizing traditional feature-based recognition techniques.

---

## 📌 Overview

This project implements a **classical face recognition system** using the **Local Binary Patterns Histogram (LBPH)** algorithm provided by OpenCV.

The focus is on **feature-based face representation**, identity prediction and robustness to lighting variations, highlighting traditional computer vision techniques as an alternative to deep learning-based approaches.

---

## 🎯 Objectives

- Detect faces from images using OpenCV  
- Extract facial features using **Local Binary Patterns (LBP)**  
- Train an LBPH-based face recognizer  
- Predict and recognize known faces from test images  

---

## 🧠 Algorithm Used: LBPH

**Local Binary Patterns Histogram (LBPH)** works by:
- Converting pixel neighborhoods into binary patterns  
- Encoding local texture information  
- Building histograms to represent facial features  
- Comparing histograms for face recognition  

Key advantages:
- Works well under varying lighting conditions  
- Simple and interpretable  
- Computationally efficient  

---

## 📂 Dataset

- Face images organized by individual identities  
- Images are preprocessed through:
  - Grayscale conversion  
  - Face detection  
  - Resizing and normalization  

Each identity is learned during training and later recognized during testing.

---

## ⚙️ Implementation Details

- **Language:** Python  
- **Library:** OpenCV  
- **Environment:** Jupyter Notebook  

Core components include:
- Face detection using OpenCV classifiers  
- Feature extraction using LBP  
- Classification using LBPH face recognizer  

---

## 📈 Results

- Successfully recognizes known faces from test images  
- Performs reliably under moderate lighting changes  
- Demonstrates effectiveness of classical vision methods  

---

## 🧪 Key Learnings

- Understanding texture-based feature extraction  
- Difference between classical and deep learning approaches  
- Role of preprocessing in face recognition accuracy  

---

## 👤 Author

**Sajidur Rahman Sajid**: Full-Stack Developer and AI engineer from Dhaka.<br>
BSc in CSE at American International University-Bangladesh (AIUB).

<p>
  <a href="https://www.sajidur.me"><img src="https://img.shields.io/badge/Portfolio-0B0E1A?style=flat-square&logo=googlechrome&logoColor=9B8CFA" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/sajidur-rahman-sajid/"><img src="https://img.shields.io/badge/LinkedIn-0B0E1A?style=flat-square&logo=linkedin&logoColor=8B7CF6" alt="LinkedIn"></a>
  <a href="https://github.com/Saji-d"><img src="https://img.shields.io/badge/GitHub-0B0E1A?style=flat-square&logo=github&logoColor=EEF0FA" alt="GitHub"></a>
  <a href="mailto:sajidsajidurrahman99@gmail.com"><img src="https://img.shields.io/badge/Email-0B0E1A?style=flat-square&logo=gmail&logoColor=9B8CFA" alt="Email"></a>
</p>
