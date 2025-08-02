# ❤️ Heart Disease Prediction

This project focuses on building a machine learning model to **predict the presence of heart disease** in patients based on various health metrics. The goal is to assist healthcare professionals in **early detection** and risk assessment using data-driven techniques.

---

## 📌 Problem Statement

Heart disease is a leading cause of death worldwide. Early diagnosis can significantly improve treatment outcomes. This project uses patient data to predict the likelihood of heart disease using classification algorithms.

---

## 📂 Dataset Overview

- **Type:** Tabular, supervised classification dataset  
- **Target Variable:** `HeartDisease` (1 = presence, 0 = absence)  
- **Source:** Public health datasets / UCI repository / Kaggle (depending on your source)

### 🔑 Key Features

| Feature         | Description                                     |
|------------------|-------------------------------------------------|
| `Age`           | Age of the patient                              |
| `Sex`           | Gender (1 = male, 0 = female)                   |
| `ChestPainType` | Type of chest pain                              |
| `RestingBP`     | Resting blood pressure                          |
| `Cholesterol`   | Serum cholesterol (mg/dl)                       |
| `FastingBS`     | Fasting blood sugar > 120 mg/dl (1 = true)      |
| `MaxHR`         | Maximum heart rate achieved                     |
| `ExerciseAngina`| Exercise-induced angina (Y/N)                   |
| `Oldpeak`       | ST depression induced by exercise               |
| `ST_Slope`      | Slope of the peak exercise ST segment           |

---

## 🧠 Project Objectives

- Perform EDA to understand data trends and relationships.
- Preprocess and clean the data (handle missing values, encode categories, scale features).
- Train classification models to predict heart disease.
- Evaluate model performance using metrics like Accuracy, Precision, Recall, and F1-score.
- Visualize model predictions and important features.

---

## 🛠️ Tools & Technologies Used

- Python (pandas, numpy, matplotlib, seaborn)
- Scikit-learn (model training and evaluation)
- Jupyter Notebook
- Streamlit (optional for web app interface)
