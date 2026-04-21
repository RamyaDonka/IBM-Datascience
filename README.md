# 🚀 SpaceX Falcon 9 First Stage Landing Prediction

## 📌 Overview
This project builds a machine learning pipeline to predict whether the **Falcon 9 first stage will successfully land**. SpaceX significantly reduces launch costs by reusing rocket boosters, making landing prediction critical for cost estimation and competitive bidding.

---

## 🎯 Problem Statement
SpaceX launches cost approximately **$62 million**, compared to competitors charging over **$165 million**. The cost advantage comes from **first stage reusability**.

👉 Objective:
- Predict if the first stage will land successfully  
- Help estimate launch costs  
- Support decision-making for competitive aerospace companies  

---

## 📊 Dataset
The dataset includes historical Falcon 9 launch data with features such as:
- Launch site  
- Payload mass  
- Orbit type  
- Booster version  
- Flight number  

---

## 🧠 Methodology

### 🔹 1. Data Preparation
- Cleaned dataset and handled missing values  
- Created a **binary classification column (Class)**:
  - `1` → Successful landing  
  - `0` → Unsuccessful landing  

---

### 🔹 2. Exploratory Data Analysis (EDA)
- Analyzed relationships between features and landing outcomes  
- Visualized trends across launch sites, payload mass, and orbit types  

---

### 🔹 3. Feature Engineering
- Encoded categorical variables  
- Standardized numerical features using scaling techniques  

---

### 🔹 4. Model Development
Implemented and trained the following classification models:
- Logistic Regression  
- Support Vector Machine (SVM)  
- Decision Tree Classifier  

---

### 🔹 5. Model Optimization
- Performed **hyperparameter tuning** using GridSearchCV  
- Optimized each model for best performance  

---

### 🔹 6. Model Evaluation
- Split data into **training and testing sets**  
- Evaluated models using:
  - Accuracy score  
  - Confusion matrix  

---

## 📈 Results
- Compared performance of all models on test data  
- Identified the best-performing model based on accuracy  

👉 (Add your final accuracy results here if available)

---

## 📊 Key Insights
- Launch site and payload mass significantly impact landing success  
- Certain orbits show higher success rates  
- Machine learning models can effectively predict landing outcomes  

---

## 🛠 Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---
