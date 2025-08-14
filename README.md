# DDoS Detection Using Machine Learning

## 📌 Overview
This project focuses on detecting **Distributed Denial of Service (DDoS)** attacks using a **machine learning-based approach**.  
By leveraging advanced **Python data analysis** and **feature engineering**, the model processes large-scale network traffic data to identify malicious patterns with high accuracy.  

The system was built to **improve detection strategies** through effective preprocessing, data balancing, and model optimization.

---

## 🔍 Key Features
- Processed **over 100,000 network records** for analysis and model training  
- Implemented **advanced data cleaning** techniques to handle missing values and outliers  
- Engineered custom features:
  - `Total Backward Packets`
  - `Fwd/Bwd Ratio`  
- Resolved **class imbalance** using **SMOTE (Synthetic Minority Over-sampling Technique)**  
- Trained a **Random Forest Classifier** with:
  - **100 estimators**
  - Achieved **80% accuracy** in cross-validation  

---

## 🛠 Tech Stack
- **Language:** Python  
- **Libraries:** pandas, NumPy, scikit-learn, imbalanced-learn  
- **Model:** Random Forest Classifier  
- **Data Handling:** Feature engineering, SMOTE balancing, normalization  

---

## 📊 Workflow
1. **Data Preprocessing**
   - Cleaned and formatted over 100,000 records of network traffic  
   - Removed noise and irrelevant fields  
2. **Feature Engineering**
   - Created `Total Backward Packets` and `Fwd/Bwd Ratio` to capture attack characteristics  
3. **Data Balancing**
   - Applied **SMOTE** to handle class imbalance and improve detection sensitivity  
4. **Model Training**
   - Used **Random Forest Classifier** with 100 estimators  
   - Evaluated using **cross-validation**  
5. **Evaluation**
   - Achieved **80% accuracy** in detecting DDoS attacks  

---

## 📈 Results
- Successfully built a machine learning pipeline for **network traffic-based DDoS detection**  
- Improved attack detection capability through targeted feature engineering  
- Addressed data imbalance, leading to more robust model performance  

---
