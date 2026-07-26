# Module 26 – Sales Forecasting Case Study (Simplified Solution)

## Project Overview
This repository contains a simplified, beginner-friendly solution for **Module 26: Sales Forecasting Case Study**. It applies linear regression and random forest regression techniques to analyze, preprocess, and predict sales.

---

## Files Included
- `sales_forecasting_case_study.ipynb`: Clean, step-by-step Jupyter Notebook.
- `README.md`: Project summary and Google Colab submission guide.

---

## Simplified 7-Step Workflow

1. **Import & Load Data**: Import libraries (`pandas`, `numpy`, `matplotlib`, `scikit-learn`) and load sales dataset.
2. **Exploratory Data Analysis (EDA)**: Inspect shape, missing values, and plot raw daily sales.
3. **Data Preprocessing**:
   - Fill missing values with forward fill (`ffill`).
   - Convert `Date` column to `datetime`.
   - Extract features: `Year`, `Month`, `Day`, `DayOfWeek`, `Is_Weekend`.
4. **Train-Test Split**: 80/20 chronological split to avoid data leakage.
5. **Model Building**: Train **Linear Regression** and **Random Forest Regressor**.
6. **Model Evaluation**: Calculate **RMSE**, **MAE**, and **R² Score**, and plot **Actual vs Predicted Sales**.
7. **Observations**: Clear bullet-point summary of key findings.

---



GOOGLE COLLAB
https://colab.research.google.com/drive/18As9cbD6PHXjso4Iga-1dCrTkbWKC4wK?usp=sharing
