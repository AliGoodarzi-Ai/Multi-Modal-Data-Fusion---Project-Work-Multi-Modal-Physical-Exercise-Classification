# 🧠 Multi-Modal Physical Exercise Classification

> 🔬 Master's Course Project — **Multi-Modal Data Fusion**  
> 📍 University of Oulu

---

## 🏋️‍♂️ Overview

This project explores the use of **multi-modal sensor data** for recognizing physical exercises. It combines **wearable accelerometer data** and **depth camera recordings** to classify different body movements.

The primary goal is to develop a **user-independent machine learning model** that can recognize exercises performed by individuals, even if the model has not seen data from those individuals before.

---

## 📦 Dataset

We use the publicly available [**MEx Dataset**](https://archive.ics.uci.edu/dataset/500/mex), which contains sensor readings from **30 participants** performing a variety of physical exercises. For this project, a **subset of 10 participants** is used.

### 🔍 Modalities:
- **Accelerometer** data (placed on the thigh)
- **Depth camera** data (for capturing skeletal/body movement)

### ⚙️ Key Features:
- Multi-modal time-series data
- Designed for **user-independent classification**
- Lying-down exercise context (on a mat)

---

## 🧠 Methods & Techniques

- 📊 **Data Preprocessing**
  - Normalization, synchronization, and filtering
  - Handling missing data from depth sensors

- 🧱 **Feature Engineering**
  - Temporal and frequency domain features
  - Joint movement and acceleration patterns

- 🧪 **Modeling**
  - Classical ML: Random Forests, SVM, k-NN
  - Deep Learning: LSTM / CNN for sequence modeling
  - Fusion strategies: Early fusion, late fusion, hybrid

- 📈 **Evaluation**
  - Train-test split across users (user-independent)
  - Accuracy, precision, recall, F1-score

---

