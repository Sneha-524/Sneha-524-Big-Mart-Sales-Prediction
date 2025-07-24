# 🛒 BigMart Sales Prediction

This project predicts sales for retail products at various BigMart outlets using machine learning. The goal is to estimate `Item_Outlet_Sales` based on product and outlet characteristics using a regression model.

---

## 📌 Project Objective

To build a predictive model using machine learning that accurately estimates the sales of items at BigMart stores, helping the business make informed decisions about inventory and pricing.

---

## 🧠 Model Used

We have used **XGBoost Regressor**, an optimized gradient boosting algorithm, known for its performance and speed on structured/tabular data.

### ✅ Why XGBoost?
- Handles missing values internally
- Works well with a mix of numerical and categorical variables
- Provides feature importance
- Efficient and scalable for large datasets

---

## 🧾 Dataset Features

The dataset includes both item-level and outlet-level attributes. Some key columns:
- `Item_Identifier`
- `Item_Weight`
- `Item_Fat_Content`
- `Item_Visibility`
- `Item_Type`
- `Item_MRP`
- `Outlet_Identifier`
- `Outlet_Establishment_Year`
- `Outlet_Size`
- `Outlet_Location_Type`
- `Outlet_Type`
- `Item_Outlet_Sales` (Target)

---

## 📊 Model Evaluation

The dataset was split into training and testing sets. The model performance was evaluated using **R² Score**.

| Dataset | R² Score |
|---------|----------|
| Train   | 0.6364   |
| Test    | 0.5868   |

The model explains approximately **63.6%** of the variance in the training set and **58.7%** in the test set.

---

## 🚀 Future Scope

- Hyperparameter tuning with GridSearchCV or RandomizedSearchCV
- Advanced feature engineering
- Compare with other regression models (e.g., Random Forest, LightGBM)
- Deploy the model using Streamlit or Flask

---

## 🛠 Tech Stack

- Python
- pandas, numpy
- scikit-learn
- XGBoost
- matplotlib, seaborn

---

