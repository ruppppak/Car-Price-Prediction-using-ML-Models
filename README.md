# Car Price Prediction using ML Models 🚗💰

## 📌 Project Overview
This project aims to predict the **price of cars** based on various features such as engine specifications, mileage, brand, and more.  

We compare the performance of three different Machine Learning models:
- **Linear Regression**
- **Lasso Regression**
- **XGBoost Regressor**

Our goal is to evaluate which model best captures the relationship between car features and their prices.

---

## 🛠️ Tech Stack
- **Python** 🐍  
- **Libraries:**
  - `pandas`, `numpy` → Data handling  
  - `matplotlib`, `seaborn` → Visualization  
  - `scikit-learn` → Linear Regression, Lasso, metrics  
  - `xgboost` → XGBoost Regressor  

---

## 📂 Dataset
The dataset contains car details like:
- **Name**
- **Year**
- **Selling Price**
- **Kilometers Driven**
- **Fuel Type**
- **Transmission**
- **Owner**

### 🔧 Preprocessing Steps
- Handling missing values  
- Encoding categorical variables  
- Feature scaling  

---

## 📊 Model Training & Evaluation

### 1️⃣ Linear Regression
- Baseline model to capture linear relationships.  
- Simple but may underfit due to complexity of data.  

### 2️⃣ Lasso Regression
- Adds **L1 regularization** to reduce overfitting.  
- Helps in **feature selection** by shrinking less important feature weights.  

### 3️⃣ XGBoost Regressor
- **Gradient Boosting algorithm**.  
- Handles **non-linear relationships** and usually provides the **best accuracy** on tabular data.  


## 📈 Results

| Model              | Train R² | Test R² |
|---------------------|----------|---------|
| Linear Regression   | 0.8799   | 0.8366  |
| Lasso Regression    | 0.8428   | 0.8709  |
| XGBoost Regressor   | 0.9999   | 0.9807  |
