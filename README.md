# 👁 MediVision – Eye Vision Risk Prediction System

MediVision Eye Risk Predictor is a Machine Learning based health screening module designed to analyze digital eye strain risk using user input data.

This module predicts whether a user has:

- Normal Vision
- Mild Vision Risk
- High Vision Risk

---

## 📌 Problem Statement

With increasing screen time due to mobile phones, laptops, and digital devices, many individuals experience digital eye strain. Early detection of eye risk levels can help users take preventive measures and improve eye health habits.

This system provides a simple screening tool to classify eye vision risk based on behavioral and test-based inputs.

---

## 📊 Input Features

The model uses the following features:

1. Minimum Font Size Read  
2. Error Count in Letter Test  
3. Daily Screen Time (hours/day)  
4. Eye Strain (Yes/No)  
5. Headache After Screen Use (Yes/No)  
6. Viewing Distance (cm)  

These inputs are collected through a Flutter-based user interface.

---

## 🎯 Output Classes

The model predicts one of the following risk levels:

- 0 → Normal Vision  
- 1 → Mild Vision Risk  
- 2 → High Vision Risk  

The result is returned through a Flask REST API.

---

## 🧠 Machine Learning Workflow

1. Synthetic dataset generation (health-pattern based rules)
2. Data preprocessing
3. Missing value handling
4. Feature selection
5. Dataset balancing (to avoid class bias)
6. Train-test split (80% training, 20% testing)
7. Algorithm comparison (Decision Tree, Random Forest, etc.)
8. Final model selection based on accuracy
9. Model export using Joblib (.pkl)
10. Backend deployment

---

## 📈 Model Evaluation

- Accuracy Score used for performance evaluation
- Confusion Matrix for classification analysis
- Balanced dataset used to improve model fairness

The final deployed model was selected based on best performance after algorithm comparison.

---

## 🏗 System Architecture

- Frontend: Flutter (Web + Android)
- Backend: Flask (Python)
- ML Library: Scikit-learn
- Model Storage: Joblib (.pkl file)
- Deployment: Render (Backend API)

---

## 🔧 How to Run Backend Locally

```bash
pip install -r requirements.txt
python app.py
