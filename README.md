# house-price-prediction-eda-linear-regression


# 🏠 House Price Prediction using Linear Regression

## 📌 Project Overview
This project focuses on predicting house prices using **Exploratory Data Analysis (EDA)**,
**feature engineering**, and **Linear Regression**.  
The goal is to understand the dataset, visualize patterns, and build a regression model
to estimate house prices based on multiple features.

---

## 📊 Dataset
- Source: Kaggle Housing Dataset
- Target Variable: `price`
- Features include:
  - Numerical: area, bedrooms, bathrooms, stories, parking
  - Categorical: mainroad, guestroom, basement, airconditioning,
    hotwaterheating, prefarea, furnishingstatus

---

## 🔍 Exploratory Data Analysis (EDA)

### Univariate Analysis
- Histograms → distribution of numerical features
- Boxplots → outliers detection
- Countplots / Pie charts → categorical feature frequencies

### Bivariate Analysis
- Feature vs Price relationships
- Scatter plots and bar plots to understand impact on price

### Key Insights
- Price increases with area and number of rooms
- Some categorical features (airconditioning, prefarea)
  significantly affect house price
- Presence of skewness and outliers in price distribution

---

## 🛠 Feature Engineering
- Encoding categorical variables
- Handling skewness
- Feature scaling
- Train-test split

---

## 🤖 Machine Learning Model
- Algorithm: **Linear Regression**
- Library: Scikit-learn

### Model Evaluation
- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

## 📈 Results
The Linear Regression model was able to capture the relationship
between house features and price with reasonable accuracy.

*(Exact metrics can be updated here)*

---

## 🧰 Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🚀 Conclusion
This project demonstrates a complete **end-to-end machine learning workflow**:
from raw data to insights and predictive modeling.
It serves as a strong beginner-friendly ML project showcasing EDA and regression concepts.

---

## 📌 Future Improvements
- Try regularization (Ridge, Lasso)
- Apply tree-based models
- Perform residual analysis
- Hyperparameter tuning
