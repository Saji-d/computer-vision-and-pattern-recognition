<div align="center">
  <img src="assets/banner.svg" alt="computer-vision-and-pattern-recognition banner" width="100%">
  <p><code>Five coursework notebooks covering KNN, MLP, MNIST, LBPH and EfficientNet transfer learning</code></p>

  ![Status](https://img.shields.io/badge/status-academic-22d3ee?style=flat-square&labelColor=0B0E1A)
  ![Licence](https://img.shields.io/badge/licence-MIT-8b7cf6?style=flat-square&labelColor=0B0E1A)
  ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=c084fc&labelColor=0B0E1A)
  ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=c084fc&labelColor=0B0E1A)
  ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=c084fc&labelColor=0B0E1A)
  ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=c084fc&labelColor=0B0E1A)
  ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=c084fc&labelColor=0B0E1A)

  <a href="#-overview">Overview</a> · <a href="#-projects">Projects</a> · <a href="#-preview">Preview</a> · <a href="#-tech-stack">Tech Stack</a> · <a href="#-getting-started">Getting Started</a> · <a href="#-project-structure">Structure</a> · <a href="#-author">Author</a>
</div>

<img src="assets/divider.svg" alt="" width="100%">

## ◈ Overview

An index of computer vision and pattern recognition notebooks written for coursework. They run from distance-based learning and hand-built neural networks to a classical face recognizer and a transfer learning model.

Each sub-project is one notebook with its own README. They are learning projects on small datasets, not production systems.

<img src="assets/divider.svg" alt="" width="100%">

## ◈ Projects

<table>
<tr>
<td width="50%" valign="top">

**KNN Image Classification**

Manual K-Nearest Neighbors with L1 and L2 distance and cross-validation on grayscale, flattened images.

Recorded result: L1 best at k=1 with 33.33% accuracy, L2 best at k=9 with 41.00%.

[Folder](knn-multiclass-image-classification) · [Notebook](knn-multiclass-image-classification/knn_multiclass_image_classification.ipynb)

</td>
<td width="50%" valign="top">

**MLP Pattern Recognition**

A multilayer perceptron trained with backpropagation on numerical data, with decision boundary plots.

Recorded result: 0.99 test accuracy on 200 samples across 5 classes.

[Folder](mlp-pattern-recognition) · [Notebook](mlp-pattern-recognition/mlp_pattern_recognition.ipynb)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**MNIST Digit Recognition**

A fully connected Keras network (no convolutions) on flattened 28x28 digits.

Recorded result: 97.66% test accuracy after 5 epochs.

[Folder](neural-network-mnist-digit-recognition) · [Notebook](neural-network-mnist-digit-recognition/neural_network_mnist_digit_recognition.ipynb)

</td>
<td width="50%" valign="top">

**LBPH Face Recognition**

Classical OpenCV pipeline: Haar cascade face detection and an LBPH recognizer trained per identity.

Not deep learning. Datasets are not included.

[Folder](lbph-face-recognition) · [Notebook](lbph-face-recognition/lbph_face_recognition.ipynb)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

**EfficientNet Face Recognition**

Transfer learning with a frozen EfficientNetB0 base, augmentation and a small dense head, plus a webcam loop that marks low-confidence faces as Unknown. It was trained on a very small private set (66 face crops), so its validation score says little about real-world accuracy. Datasets are not included.

[Folder](efficientnet-face-recognition) · [Notebook](efficientnet-face-recognition/efficientnet_face_recognition.ipynb)

</td>
</tr>
</table>

<img src="assets/divider.svg" alt="" width="100%">

## ◈ Preview

<div align="center">
  <img src="docs/preview.webp" alt="Preview cover for the face recognition projects" width="80%">
</div>

<img src="assets/divider.svg" alt="" width="100%">

## ◈ Tech Stack

| Layer | Technologies | Purpose |
|---|---|---|
| Language | Python | Notebook code |
| Vision | OpenCV, Pillow | Face detection, LBPH and image loading |
| Deep learning | TensorFlow, Keras | MNIST network and EfficientNetB0 transfer learning |
| Classical ML | NumPy, scikit-learn | KNN, MLP and evaluation reports |
| Environment | Jupyter, Google Colab | Running the notebooks |

<img src="assets/divider.svg" alt="" width="100%">

## ◈ Getting Started

```bash
git clone https://github.com/Saji-d/computer-vision-and-pattern-recognition.git
cd computer-vision-and-pattern-recognition
pip install jupyter numpy matplotlib opencv-contrib-python scikit-learn tensorflow pandas pillow tqdm
jupyter notebook
```

The face recognition notebooks read a local folder of images arranged as one sub-folder per person. The paths in them point to the author's machine, so edit `dataset_path` before running. Face datasets are private and are not included. The webcam cells need a connected camera and LBPH needs `opencv-contrib-python` for `cv2.face`.

<img src="assets/divider.svg" alt="" width="100%">

## ◈ Project Structure

Five notebook folders, each with its own README, plus `assets/` and `docs/` for the banner and preview.

```text
computer-vision-and-pattern-recognition/
├── efficientnet-face-recognition/
├── knn-multiclass-image-classification/
├── lbph-face-recognition/
├── mlp-pattern-recognition/
├── neural-network-mnist-digit-recognition/
│   (each folder holds one notebook and a README)
├── assets/      banner and divider
├── docs/        preview image
└── LICENSE
```

<img src="assets/divider.svg" alt="" width="100%">

## ◈ Author

**Sajidur Rahman Sajid**: Full-Stack Developer and AI engineer from Dhaka.<br>
BSc in CSE at American International University-Bangladesh (AIUB).

<p>
  <a href="https://www.sajidur.me"><img src="https://img.shields.io/badge/Portfolio-0B0E1A?style=flat-square&logo=googlechrome&logoColor=9B8CFA" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/sajidur-rahman-sajid/"><img src="https://img.shields.io/badge/LinkedIn-0B0E1A?style=flat-square&logo=linkedin&logoColor=8B7CF6" alt="LinkedIn"></a>
  <a href="https://github.com/Saji-d"><img src="https://img.shields.io/badge/GitHub-0B0E1A?style=flat-square&logo=github&logoColor=EEF0FA" alt="GitHub"></a>
  <a href="mailto:sajidsajidurrahman99@gmail.com"><img src="https://img.shields.io/badge/Email-0B0E1A?style=flat-square&logo=gmail&logoColor=9B8CFA" alt="Email"></a>
</p>

<sub>Released under the MIT licence.</sub>
