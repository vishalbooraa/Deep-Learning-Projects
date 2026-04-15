# 🧠 Image Classification using CNN (CIFAR-10)

## 📌 Overview

This project implements a **Convolutional Neural Network (CNN)** using **PyTorch** to classify images from the **CIFAR-10 dataset** into 10 different categories.

The model is trained on **RGB images (32×32)** and achieves an accuracy of **~75.37%** on the test dataset.

---

## 🎯 Objectives

* Build a deep learning model for **image classification**
* Understand **CNN architecture** *(Conv → ReLU → Pooling → Fully Connected)*
* Train and evaluate model performance on a **real-world dataset**

---

## 📂 Dataset

* **Dataset:** CIFAR-10
* **Classes:**

  * Airplane
  * Automobile
  * Bird
  * Cat
  * Deer
  * Dog
  * Frog
  * Horse
  * Ship
  * Truck
* **Image Size:** 32 × 32 (RGB)

---

## 🏗️ Model Architecture

### 🔹 Convolutional Layers

* Conv2D *(3 → 32)* + ReLU + MaxPooling
* Conv2D *(32 → 64)* + ReLU + MaxPooling
* Conv2D *(64 → 128)* + ReLU + MaxPooling

### 🔹 Fully Connected Layers

* Linear *(128 × 4 × 4 → 256)* + ReLU
* Linear *(256 → 10 output classes)*

---

## ⚙️ Technologies Used

* Python
* PyTorch
* NumPy
* Matplotlib

---

## 🚀 Training Details

* **Loss Function:** CrossEntropyLoss
* **Optimizer:** Adam
* **Batch Size:** 64
* **Epochs:** 10
* **Normalization:** Images scaled to range [-1, 1]

---

## 📊 Results

* **Test Accuracy:** 75.37%
* The model successfully learns meaningful features and generalizes well on unseen data.

---
