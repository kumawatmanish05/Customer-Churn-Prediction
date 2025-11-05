# 🧠 Customer Churn Prediction using ANN

Predicting **Customer Churn** using an **Artificial Neural Network (ANN)** to help businesses retain valuable customers and make data-driven decisions 💡  

This project uses **Python + TensorFlow/Keras** to classify whether a customer will leave the service based on demographic, banking & activity features.

---

## 🎯 Project Objective

✔️ Predict customers likely to churn  
✔️ Improve retention with proactive insights  
✔️ Use ANN & feature engineering for high accuracy  

---

## 📦 Dataset Overview

Dataset: `Churn_Modelling.csv`

| Feature Type | Examples |
|-------------|--------|
👤 Customer Info | Gender, Age, Geography  
🏦 Banking Details | Balance, CreditScore, Tenure  
💳 Product Usage | NumOfProducts, HasCrCard, IsActiveMember  
🎯 Target | `Exited` (1 = churn, 0 = stay)  

---

## 🔧 Tech & Tools Used

| Category | Tools |
|--------|------|
Language | Python 🐍  
ML/DL | TensorFlow, Keras, Scikit-Learn  
Data | Pandas, NumPy  
Visualization | Matplotlib  
Deployment | Streamlit  
Tracking | TensorBoard 📊  

---

## ⚙️ Model Workflow

1️⃣ Load & clean data  
2️⃣ Handle categorical features (Label + One-Hot Encoding)  
3️⃣ Scale numeric values  
4️⃣ Build ANN  
5️⃣ Train with early stopping  
6️⃣ Evaluate & save model  

---

## 🏗️ ANN Architecture

| Layer | Details |
|------|---------|
Input Layer | Scaled features  
Hidden Layer 1 | 64 neurons, ReLU  
Hidden Layer 2 | 32 neurons, ReLU  
Output Layer | Sigmoid — Binary classification (Churn / No Churn)  
Optimizer | Adam ⚡  
Loss | Binary Cross-Entropy  

---

## 📊 Model Performance

| Metric | Score |
|-------|------|
Training Accuracy | ~87% ✅  
Validation Accuracy | ~86.5% ✅  

> **Achieved stable performance with Early Stopping & TensorBoard monitoring.**

---

## 🚀 Deployment Ready Assets

✅ `model.h5` – Trained ANN model  
✅ `scaler.pkl` – StandardScaler  
✅ `label_encoder_gender.pkl`  
✅ `onehot_encoder_geo.pkl`  
✅ Streamlit front-end  

Easily plug into real-world applications 🏢📎  

---

## 🎨 Visualizations Included

📈 Training & Validation Loss  
📊 Churn Distribution  
📊 Feature Importance Insights  
📂 TensorBoard Learning Curves  

---

## 🎥 Project Demo

> Watch the demo video below 👇

https://github.com/user-attachments/assets/fd5b0eed-47a3-4e8b-8646-b2e2876911b5




--- 

## ▶️ How to Run Locally

```bash
git clone https://github.com/kumawatmanish05/customer-churn-ann.git
cd customer-churn-ann
pip install -r requirements.txt
streamlit run app.py
