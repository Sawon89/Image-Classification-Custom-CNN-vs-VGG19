# Image Classification: Custom CNN vs. VGG19 (Cat and Dog Classification)

This repository contains a comprehensive academic lab assignment focused on image classification, comparing a **Custom Convolutional Neural Network (CNN)** built from scratch against a pre-trained **VGG19** model utilizing Transfer Learning. The project aims to distinguish between images of cats and dogs using deep learning techniques in Python.

---

## 📌 Project Overview
* **Objective:** Build, train, evaluate, and compare a Custom CNN model with a VGG19 Transfer Learning model for binary image classification (Cat vs. Dog).
* **Context:** Developed as part of an undergraduate computer science academic curriculum/lab assignment at Dhaka International University.
* **Platform:** Google Colab (Python, TensorFlow/Keras, Scikit-learn, Matplotlib).

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Deep Learning Framework:** TensorFlow & Keras
* **Data Manipulation & Metrics:** NumPy, Pandas, Scikit-learn
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Google Colab

---

## 📊 Methodology & Pipeline
1. **Data Preprocessing & Augmentation:** Loading dataset, resizing images, normalization, and splitting into training, validation, and test sets.
2. **Custom CNN Model:** Architecture built with multiple Convolutional layers, MaxPooling, Dropout, and Dense layers to extract features from scratch.
3. **VGG19 Transfer Learning:** Utilizing pre-trained weights from ImageNet on the VGG19 backbone, freezing initial layers, and fine-tuning custom top layers for the cat-dog classification task.
4. **Model Evaluation & Comparison:** 
   * Performance metrics (Accuracy, Precision, Recall, F1-Score).
   * Confusion matrix generation.
   * Side-by-side visual comparison of predictions vs. true labels.

---

## 🚀 How to Run the Code
1. Open the `.ipynb` notebook file in **Google Colab**.
2. Run the cells sequentially from top to bottom.
3. Ensure GPU runtime is enabled in Colab for faster model training (Runtime > Change runtime type > T4 GPU).

---

## 👤 Author
* **Md Saifullah Islam Sawon**
* Department of Computer Science & Engineering (CSE)
* Dhaka International University
