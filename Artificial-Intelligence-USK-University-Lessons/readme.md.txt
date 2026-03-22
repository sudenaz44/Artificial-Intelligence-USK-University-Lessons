# Artificial Intelligence Course Projects

This repository contains weekly projects developed as part of our Artificial Intelligence course. The projects focus on machine learning, data analysis, and advanced modeling techniques.

## 👥 Team Members
- Sudenaz Kılıç (220201054)
- Muhammed Kallo (220201916)
- Gülbahar Yalçındağ (220201001)
- Nisa Sert (220201029)

---

## 📌 Project: Mine Landslide Risk Prediction

### 🔹 Overview
This project focuses on predicting landslide risk in mining areas using both traditional machine learning and advanced approaches such as Knowledge Graphs and feature interactions.

---

## 🧠 Model 1: Baseline (Logistic Regression)

- Uses only original features
- No feature interaction
- Acts as a reference model

**Accuracy:** 73.3%

---

## 🚀 Model 2: Improved Model (GBDT + Feature Interaction)

- Gradient Boosting Decision Tree (GBDT)
- Polynomial feature expansion (feature interaction)
- Captures relationships between features

**Accuracy:** 75.2%

---

## 🔗 Knowledge Graph Approach

- Slopes represented as nodes
- Similarity relationships as edges
- Translation-based embeddings used
- Risk calculated using:

LMR = (Ls + Sd) / (2 × NS)

---

## 📊 Key Features

- Slope Angle
- Soil Type
- Rainfall
- Feature Interactions (Crossed Features)

---

## 📈 Results

| Metric | Baseline | Improved | Difference |
|--------|----------|----------|------------|
| Accuracy | 0.733 | 0.752 | +0.019 |
| Recall | 0.81 | 0.84 | +0.03 |
| Precision | 0.50 | 0.53 | +0.03 |

---

## 📂 Dataset
https://www.kaggle.com/datasets/rajumavinmar/landslide-dataset

---

## 📄 Reference Paper
https://ieeexplore.ieee.org/document/9546689

---

## ⚙️ Technologies Used
- Python
- Scikit-learn
- Pandas
- NumPy

---

## 📌 Notes
This repository will be updated weekly with new AI projects and experiments.