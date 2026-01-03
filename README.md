# 🚗 Car Price Prediction – Machine Learning Assignment

## 📌 Project Overview
A Chinese automobile company plans to enter the US market and wants to understand the key factors affecting car prices.
This project builds multiple machine learning regression models to predict car prices and identify the most important variables influencing pricing.

The insights from this model help management make informed decisions about car design, features, and pricing strategy.

---

## 🎯 Business Objectives
- Identify significant variables affecting car prices
- Evaluate how well these variables explain price variation
- Build and compare multiple regression models
- Select the best-performing model
- Perform feature importance analysis
- Improve performance using hyperparameter tuning

---

## 📂 Dataset
- File: `CarPrice_Assignment.csv`
- Contains car specifications such as engine size, horsepower, curb weight, fuel type, body type, and price.

---

## 🛠️ Technologies & Libraries Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📁 Project Structure
```
Car-Price-Prediction-ML/
│
├── Car_Price_Prediction_ML_Assignment.ipynb
├── CarPrice_Assignment.csv
├── README.md
```

---

## 🔄 Project Workflow

### 1️⃣ Data Loading & Preprocessing
- Loaded dataset using Pandas
- Dropped unnecessary column (`CarName`)
- Converted categorical variables using one-hot encoding
- Split data into training and testing sets
- Applied feature scaling where required

### 2️⃣ Models Implemented
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Support Vector Regressor (SVR)

### 3️⃣ Model Evaluation
Models were evaluated using:
- R-squared (R²)
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)

### 4️⃣ Feature Importance Analysis
- Random Forest was used to identify key variables
- Major factors include engine size, horsepower, curb weight, and car width

### 5️⃣ Hyperparameter Tuning
- GridSearchCV applied on Random Forest
- Performance improved after tuning

---

## 🏆 Best Model
✅ Random Forest Regressor (after hyperparameter tuning)

---

## 📊 Key Insights
- Engine and size-related features strongly influence car prices
- Ensemble models outperform linear models
- Hyperparameter tuning improves prediction accuracy

---

## ▶️ How to Run
1. Clone the repository
2. Place `CarPrice_Assignment.csv` in the same folder
3. Open the notebook
4. Run all cells

---

## 📌 Conclusion
This project demonstrates how machine learning can be used to analyze car pricing dynamics and support business decision-making.
