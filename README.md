# 🧠 PyTorch Binary & Multiclass Classification

This repository demonstrates how to build, train, and evaluate neural network models for both **binary** and **multiclass classification tasks** using **PyTorch**. It's designed as a beginner-to-intermediate level project for those exploring deep learning workflows end to end.

---

## 📂 Project Structure


---

## 🎯 Objectives

- Build a PyTorch-based neural network for:
  - **Binary classification** (e.g., spam detection, disease presence)
  - **Multiclass classification** (e.g., digit recognition, sentiment analysis)
- Preprocess data using `scikit-learn`
- Apply training, validation, and test splits
- Track metrics: **Accuracy**, **Precision**, **Recall**, **F1 Score**
- Visualize training performance

---

## 📊 Datasets

> ⚠️ The notebooks assume input datasets are either loaded from files or embedded. You can adapt the `pd.read_csv()` calls to your own dataset.

- Features are normalized using `StandardScaler`
- Labels are encoded and (in multiclass) one-hot encoded

---

## 🏗️ Model Architecture

- Fully connected feed-forward neural networks
- Activation: ReLU for hidden layers, Sigmoid (binary) or Softmax (multiclass) for output
- Loss:
  - **Binary**: `BCELoss` (Binary Cross-Entropy)
  - **Multiclass**: `CrossEntropyLoss`
- Optimizer: `Adam`
- Epoch loop with loss tracking and metric logging

---

## 🧪 Evaluation Metrics

Each model is evaluated on:
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**

Additionally, the training and validation loss are plotted per epoch.

---

## 🛠️ Setup

### Requirements

```bash
pip install numpy pandas scikit-learn matplotlib torch joblib


Developed by John Ktenidis
