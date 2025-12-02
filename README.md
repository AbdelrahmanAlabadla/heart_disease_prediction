# ❤️ Heart Disease Prediction Using Decision Tree

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-0.25-orange?logo=scikit-learn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green)

**End-to-end ML project** | Decision Tree with hyperparameter tuning + pruning + interactive prediction  
Built by **Abdelrahman Alabadla** • Dec 2025

---

## 🚀 Project Overview
Predicts **heart disease** using patient medical records with a **Decision Tree Classifier**. Includes everything a real ML role expects:

- Data cleaning & preprocessing  
- One-hot encoding of categorical features  
- Hyperparameter tuning (`GridSearchCV`)  
- Cost-complexity pruning (`ccp_alpha`) to prevent overfitting  
- Full evaluation + visualizations  
- Interactive prediction widget (just enter patient data → get result!)

---

## 📁 Dataset – `heart[1].csv`
Classic UCI Heart Disease dataset (918 rows)

| Feature            | Description                                    |
|--------------------|------------------------------------------------|
| Age                | Age in years                                   |
| Sex                | M / F                                          |
| ChestPainType      | ATA, NAP, ASY, TA                              |
| RestingBP          | Resting blood pressure                         |
| Cholesterol        | Serum cholesterol (mg/dl)                      |
| FastingBS          | 1 if fasting blood sugar > 120 mg/dl           |
| RestingECG         | Normal, ST, LVH                                |
| MaxHR              | Maximum heart rate achieved                    |
| ExerciseAngina     | Y / N                                          |
| Oldpeak            | ST depression induced by exercise              |
| ST_Slope           | Up, Flat, Down                                 |
| **HeartDisease**   | **1 = Disease, 0 = Normal** ← Target          |

---

## 📊 Best Model Performance (after tuning + pruning)
```text
Accuracy: 85.0%

Confusion Matrix:
[[40  5]
 [ 6 39]]

Classification Report:
              precision    recall  f1-score   support
           0       0.87      0.89      0.88        45
           1       0.89      0.87      0.88        45           
