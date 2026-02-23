# 🧠 MediVision – AI-Based Health Risk Prediction System

MediVision is a Machine Learning powered health screening application designed to predict early health risks using user inputs. The system integrates multiple ML models with a Flutter frontend and a Flask backend.

---

## 🚀 Project Overview

MediVision focuses on early risk detection in three major areas:

1. 👁 Eye Vision Risk Prediction  
2. 🩸 Diabetes Risk Prediction  
3. 🧘 Mental Wellness Risk Assessment  

The system allows users to input health-related data and receive a risk classification in real time.

---

## 🏗 System Architecture

- **Frontend:** Flutter (Web + Android)
- **Backend:** Python Flask API
- **Machine Learning:** Scikit-learn
- **Deployment:** Render (Backend), Web Hosting for Flutter
- **Model Storage:** Joblib (.pkl files)

---

## 👁 Eye Vision Risk Predictor

### 📌 Problem
Excessive screen time and poor digital habits increase the risk of eye strain and vision issues.

### 📊 Input Features
- Minimum font size readable
- Error count in letter test
- Daily screen time (hours)
- Eye strain (Yes/No)
- Headache (Yes/No)
- Viewing distance (cm)

### 🎯 Output Classes
- Normal Vision
- Mild Vision Risk
- High Vision Risk

### 🔍 Model Details
- Multiple algorithms tested (Decision Tree, Random Forest, etc.)
- Dataset balancing performed using oversampling
- Final model selected based on accuracy comparison

---

## 🩸 Diabetes Risk Prediction

### 📌 Problem
Early detection of diabetes risk using basic health parameters.

### 📊 Input Features
- Age
- BMI
- Blood Pressure
- Glucose Level

### 🎯 Output
- Low Risk
- High Risk

---

## 🧘 Mental Wellness Assessment

### 📌 Problem
Mental health conditions such as stress, anxiety, and depression often go undetected.

### 📊 Input
- 42-question structured questionnaire

### 🎯 Output Classes
- Normal
- Stress Risk
- Anxiety Risk
- Depression Risk

---

## 🧠 Machine Learning Workflow

1. Data Collection / Synthetic Dataset Creation
2. Data Cleaning
3. Missing Value Handling
4. Feature Selection
5. Dataset Balancing
6. Train-Test Split (80/20)
7. Algorithm Comparison
8. Model Selection
9. Model Export (.pkl using joblib)
10. Backend Deployment

---

## 📈 Model Evaluation

- Accuracy Score
- Confusion Matrix
- Algorithm Comparison
- Balanced vs Unbalanced Dataset Analysis

The final deployed models were selected based on highest accuracy and generalization performance.



## 🌐 Live Web App

Frontend:
https://medivision-ai-a30fb.web.app/
In the model The first request take one minute !
