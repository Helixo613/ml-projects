#  Supermart Sales Prediction

This project focuses on predicting sales and profit performance in a retail dataset. It uses exploratory data analysis, feature selection, and machine learning models to understand the relationship between features like product category, discount, and regional performance.

---

## Problem Statement

Given a dataset from a fictional superstore, the goal is to predict:
- Sales (`Sales`)
- Profit (`Profit`)

using other categorical and numerical features in the dataset.

---

##  Dataset

The dataset used is `SampleSuperstore.csv`, which contains fields like:
- `Category`, `Sub-Category`
- `Region`, `State`
- `Discount`, `Quantity`, `Sales`, `Profit`, etc.

 If not included, download it from [SampleSuperstore Dataset on Kaggle](https://www.kaggle.com/datasets/jessemostipak/superstore)

---

##  Features & Workflow

- Data Cleaning & Null Check
- Feature Selection
- Correlation Analysis
- Normalization using `MinMaxScaler`
- Visualizations using `Seaborn` and `Matplotlib`

---

##  Models Used

- Regression techniques for Sales and Profit prediction
- Feature importance analysis

---

##  Evaluation Metrics

- RMSE (Root Mean Squared Error)
- R² Score

---

## 
How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

