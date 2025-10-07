# 🚦 Traffic Sign Recognition System

A deep learning project that classifies traffic signs using a Convolutional Neural Network (CNN) trained on the **GTSRB (German Traffic Sign Recognition Benchmark)** dataset.  
This project demonstrates the use of image preprocessing, CNN architecture, and model evaluation for real-world computer vision applications.

---

## 📁 Project Overview

### 🔍 Objective
To build an image classification model that accurately recognizes traffic signs from images using CNNs.

### 🧠 Skills Gained
- Deep learning (Convolutional Neural Networks)
- Image preprocessing & normalization
- Model training, evaluation, and visualization
- Handling multi-class image data

### 💼 Industry Relevance
Applicable in:
- **Autonomous vehicles**
- **Robotics**
- **Smart city systems**
- **Driver assistance technologies**

---

## 🧩 Dataset

**Dataset Name:** [Traffic Signs Preprocessed (GTSRB)](https://www.kaggle.com/datasets/valentynsichkar/traffic-signs-preprocessed)  
The dataset contains preprocessed traffic sign images divided into training, validation, and testing sets, with 43 different classes.

---

## 🧱 Project Workflow

### 🔹 1. Data Loading
- Loaded preprocessed `.pickle` files from Kaggle.
- Combined training, validation, and testing sets.

### 🔹 2. Data Preprocessing
- Normalized image pixel values.
- Visualized random samples for verification.

### 🔹 3. Model Building
- Constructed a **CNN** with multiple Conv2D and MaxPooling layers.
- Used **ReLU** activations and **softmax** for final classification.

### 🔹 4. Model Training
- Optimized with **Adam optimizer** and **categorical cross-entropy loss**.
- Trained for multiple epochs with early stopping.

### 🔹 5. Evaluation
- Evaluated accuracy on validation and test sets.
- Visualized predictions for sample test images.

---

## 📊 Results

| Metric | Score |
|--------|-------|
| **Training Accuracy** | ~99% |
| **Validation Accuracy** | ~98% |
| **Test Accuracy** | ~97% |

---

## 🖼️ Sample Predictions
The model successfully predicts real traffic signs with high accuracy.



### ⚙️ Tech Stack

Python 🐍

TensorFlow / Keras 🤖

NumPy · Matplotlib

Kaggle / Colab (for training)

### 🔗 Resources

#### 📚 Dataset: [Traffic Signs Preprocessed (Kaggle)](https://www.kaggle.com/datasets/valentynsichkar/traffic-signs-preprocessed)

#### 💻 GitHub Repository: [My Repo Link](https://github.com/The-Coder-786/Machine-Learning-Internship-Tasks)

### ✨ Acknowledgment

Dataset provided by Valentyn Sichkar on Kaggle.
Inspired by research in autonomous driving and intelligent traffic systems.

## 🏁 Summary

This project builds a complete CNN-based traffic sign classifier — a critical component in modern intelligent transport and self-driving systems.
