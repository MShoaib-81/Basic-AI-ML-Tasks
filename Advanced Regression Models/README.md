# 🏠 Advanced Regression Models for Housing Price Prediction

This project explores multiple **regression techniques** for predicting house prices using the **Housing dataset**.  
The models compared include **Linear Regression, Ridge Regression, Lasso Regression, and Polynomial Regression (degree=2)**.

---

## 🚀 Project Overview
The objective is to benchmark different regression models and evaluate their ability to predict housing prices.  
The models are compared using the following metrics:
- **R² Score**
- **MAE (Mean Absolute Error)**
- **MSE (Mean Squared Error)**

---

## 📂 Dataset
Dataset: **Housing.csv**  
Features include:
- Area, Bedrooms, Bathrooms, Stories  
- Main road access, Guestroom, Basement, Hot water heating, Air conditioning  
- Parking, Preferred area, Furnishing status  

Target: **Price**

---

## ⚙️ Models Implemented
1. **Linear Regression (Baseline)**
2. **Lasso Regression (L1 Regularization)**
3. **Ridge Regression (L2 Regularization)**
4. **Polynomial Regression (degree = 2)**

---

## 📊 Results

| Model                       | R² Score | MAE           | MSE               |
|-----------------------------|----------|---------------|-------------------|
| **Linear Regression**       | 0.6494   | 979,679.69    | 1.7718e+12        |
| **Lasso Regression (L1)**   | 0.6494   | 979,680.73    | 1.7718e+12        |
| **Ridge Regression (L2)**   | 0.6490   | 980,105.64    | 1.7742e+12        |
| **Polynomial Regression**   | 0.6499   | 1,006,766.48  | 1.7697e+12        |

> ✅ Polynomial regression gave the **highest R² Score (0.6499)** but also showed larger MAE.  
> ✅ Lasso and Ridge performed very similarly to Linear Regression.  

---

## 📈 Visualizations
The notebook generates:
- **Actual vs Predicted scatter plots** for each model  
- **Combined comparison plot** for all models  

Example:  
- Lasso Regression (green)  
- Ridge Regression (blue)  
- Polynomial Regression (purple)  
- Red dashed line = Perfect prediction line  

---

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/advanced-regression-models.git
   cd advanced-regression-models

