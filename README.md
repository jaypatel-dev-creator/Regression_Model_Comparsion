#  Regression Analysis: Linear Regression vs XGBoost

This project demonstrates a complete **end-to-end regression workflow** using the **California Housing Dataset**, comparing the performance of **Linear Regression** and **XGBoost Regressor**.

The objective is to understand model behavior, evaluate performance using standard metrics, and visualize prediction quality.

---

## Project Overview

This project includes:
- Data loading and preprocessing  
- Training and evaluating two regression models  
- Comparing model performance using evaluation metrics  
- Visualizing prediction accuracy  

---

## Dataset Information

- **Dataset:** California Housing Dataset  
- **Target Variable:** `MedHouseValue`  
- **Features Used:**
  - MedInc  
  - HouseAge  
  - AveRooms  
  - AveBedrms  
  - Population  
  - AveOccup  
  - Latitude  
  - Longitude  

---

## Workflow Summary

### 1️⃣ Data Preparation
- Loaded dataset using `sklearn.datasets`
- Converted to pandas DataFrame
- Separated features and target variable
- Performed train–test split

---

### 2️⃣ Model Training

Two regression models were trained:

#### 🔹 Linear Regression
A baseline model used to understand linear relationships in the data.

#### 🔹 XGBoost Regressor
A powerful ensemble model capable of capturing non-linear patterns and feature interactions.

---

### 3️⃣ Model Evaluation Metrics

Both models were evaluated using:

- **MAE (Mean Absolute Error)**  
  Measures average prediction error.

- **RMSE (Root Mean Squared Error)**  
  Penalizes larger errors more heavily.

- **R² Score**  
  Indicates how well the model explains the variance in the target variable.

---

## 📊 Model Performance Comparison

| Model | MAE | RMSE | R² |
|------|-----|------|----|
| **Linear Regression** | ~0.53 | ~0.72 | ~0.58 |
| **XGBoost Regressor** | ~0.33 | ~0.49 | ~0.81 |

---

## 📈 Visualization Insights

- **Actual vs Predicted plots** were used to visually assess performance.
- Linear Regression shows wider scatter around the diagonal line.
- XGBoost predictions are more tightly aligned with the ideal prediction line.
- This indicates better generalization and lower prediction error for XGBoost.

---

##  Key Observations

- Linear Regression serves as a good baseline but struggles with non-linear relationships.
- XGBoost significantly improves accuracy and model robustness.
- Evaluation metrics and visual analysis together provide stronger insights than metrics alone.

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib  

---

##  Conclusion

This project demonstrates a complete regression workflow—from data preprocessing to model evaluation—highlighting the strengths of ensemble models over traditional linear approaches.  
XGBoost proves to be a more reliable and accurate model for this dataset.

---

✅ **This project structure and analysis are suitable for GitHub portfolios and ML interviews.**
