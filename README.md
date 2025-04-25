# CAPSTONE-PROJECT-HEALTHCARE
insightDx
# Capstone Project: Healthcare (Diabetes Prediction)

This project explores a healthcare dataset with the goal of predicting diabetes using various machine learning models. It involves thorough data cleaning, exploratory data analysis, and model evaluation using key performance metrics.

## 📊 Dataset Overview

- **Rows:** 768
- **Columns:** 9 (Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age, Outcome)

## 🧹 Data Preprocessing

- Replaced invalid zero values in Glucose, BloodPressure, SkinThickness, Insulin, and BMI with column means.
- Verified and corrected data types.
- Visualized distributions using histograms.

## 📈 Exploratory Data Analysis

- Count plots and scatter plots for relationship analysis.
- Heatmap for correlation analysis.
- Key observations:
  - Moderate correlation between `Pregnancies & Age`, `BMI & SkinThickness`, `Outcome & Glucose`.

## 🤖 Models Applied

1. **K-Nearest Neighbors (KNN)**
   - Accuracy: 79.87%
   - AUC: 80.14%

2. **Logistic Regression**
   - Accuracy: 75.97%
   - AUC: 78.18%

3. **Decision Tree**
   - Accuracy: 76.62%
   - AUC: 79.12%

4. **Random Forest**
   - Accuracy: 77.27%
   - AUC: 82.04%

> 📌 **Best AUC:** Random Forest  
> 📌 **Best Accuracy:** KNN

## 📁 Final Output

- Cleaned and processed data saved to `HealthCare.xlsx` for use in Tableau.

## 📌 Tools & Libraries Used

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook
- Tableau (for visualization)
