# 🌱 Crop Yield Prediction Model

## Description of the Project
The **Crop Yield Prediction Model** is a machine learning-based data science solution designed to forecast agricultural crop output based on environmental, geographical, and temporal features. By leveraging regression algorithms, this project bridges the gap between historical agricultural data and predictive analytics, helping stakeholders understand productivity patterns across different regions and seasons.

---

## Problem Statement
Accurate forecasting of agricultural yield is critical for food security, supply chain logistics, and economic planning. Farmers and agricultural planners often face uncertainties due to fluctuating weather conditions, seasonal variations, and varying land sizes. The core problem addressed by this project is how to utilize historical agricultural records (such as crop type, season, area, and year) to reliably predict crop yield, thereby assisting in smarter resource allocation, risk mitigation, and post-harvest management.

---

## The Tools Used
The project is built using a robust Python data science and machine learning stack:
* **Programming Language:** Python
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning & Modeling:** Scikit-Learn (including regression models and evaluation metrics)
* **Development Environment:** Jupyter Notebook (`.ipynb`)

---

## The Methodology
The machine learning pipeline follows a structured end-to-end data science workflow:
1. **Data Loading & Inspection:** Importing the raw agricultural dataset and inspecting data types, missing values, and summary statistics.
2. **Exploratory Data Analysis (EDA):** Visualizing distributions, correlations between features (such as area size, seasonal variations), and target yield metrics using Matplotlib and Seaborn.
3. **Data Preprocessing & Cleaning:** Handling missing data, encoding categorical variables (e.g., crop types and seasons), and scaling numerical features where necessary.
4. **Feature Engineering:** Selecting relevant predictors and preparing feature matrices (`X`) and target vectors (`y`).
5. **Model Training & Evaluation:** Splitting the data into training and testing sets, training regression estimators, and evaluating performance using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared ($R^2$).

---

## The Results
* Successfully established a functional pipeline that maps agricultural input variables to reliable yield estimates.
* Validated model performance through comparative metrics on test data, ensuring low generalization error.
* Delivered clean, reproducible Jupyter Notebook code that serves as an extensible baseline for agricultural forecasting and decision support systems.

---

## 🚀 Getting Started

To run this notebook locally:
```bash
# Clone the repository
git clone [https://github.com/Placidus-Ali/Crop_yield_prediction.git](https://github.com/Placidus-Ali/Crop_yield_prediction.git)

# Navigate to the project directory
cd Crop_yield_prediction

# Install required dependencies
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## Here is the App
https://cropyieldpredictionmodel.streamlit.app/
