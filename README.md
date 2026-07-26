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

## Google Colab Submission Guide

1. **Upload Notebook**: Go to [Google Colab](https://colab.research.google.com/), click **File** -> **Upload notebook**, and upload `sales_forecasting_case_study.ipynb`.
2. **Run Notebook**: Click **Runtime** -> **Run all** (`Ctrl + F9`).
3. **Share Link**: Click **Share** (top right), change setting to **"Anyone with the link can view"**, and copy the link.
