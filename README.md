# 🏦 Bank Personal Loan Modeling

## 📌 Project Overview
This project aims to predict the likelihood of a liability customer purchasing a **personal loan** from Thera Bank. Using customer demographics, banking relationships, and past campaign responses, we build **classification models** to enhance targeted marketing and improve conversion rates.

## 📊 Dataset Description
The dataset contains **5,000 customer records** with **demographic, financial, and banking details**. The target variable is **"Personal Loan"**, indicating whether the customer accepted the loan offer.

### 🏦 **Dataset Features**
- **Customer Information**: ID, Age, Experience, Income, Family Size, ZIP Code
- **Banking Relationships**: Mortgage, Securities Account, CD Account, Online Banking, Credit Card Usage
- **Spending Habits**: Average Monthly Credit Card Spending (CCAvg)
- **Education Levels**: 
  - `1`: Undergraduate  
  - `2`: Graduate  
  - `3`: Advanced/Professional  
- **Target Variable**:  
  - `0` = Did not accept the loan  
  - `1` = Accepted the loan  

## 🎯 **Objective**
To develop a **classification model** that accurately predicts whether a liability customer will buy a **personal loan**.

## 🚀 **Project Workflow**
### **Step 1: Data Exploration**
✔ Understanding feature distributions  
✔ Checking missing values and outliers  
✔ Analyzing target class imbalance  

### **Step 2: Data Preprocessing**
✔ Feature encoding  
✔ Train-test split (70% training, 30% testing)  
✔ Normalization (if needed)  

### **Step 3: Model Training**
✔ **Classification Models**:  
   - ✅ Logistic Regression  
   - ✅ k-Nearest Neighbors (KNN)  
   - ✅ Naïve Bayes  

### **Step 4: Model Evaluation**
✔ Confusion Matrix  
✔ Accuracy, Precision, Recall, F1-score  
✔ ROC-AUC Curve  

### **Step 5: Best Model Selection**
✔ Compare model performance  
✔ Choose the best model based on evaluation metrics  
