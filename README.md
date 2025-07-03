# ad_report_regression
# 📈 Advertising and Sales Analysis with Linear Regression

This project explores the impact of advertising budgets (TV, Radio, Newspaper) on product sales using **Simple Linear Regression** and **Multiple Linear Regression** techniques.

## 🧠 Objective
To understand how advertising spending across different media influences product sales, and to build predictive models using linear regression.

## 📂 Dataset
The dataset contains the following columns:
- `TV`: Advertising budget for TV (in thousands of dollars)
- `Radio`: Advertising budget for Radio (in thousands of dollars)
- `Newspaper`: Advertising budget for Newspaper (in thousands of dollars)
- `Sales`: Units sold (in thousands)

The dataset is commonly known as the **Advertising dataset** and is publicly available from ISLR (Introduction to Statistical Learning).

## 📊 Models Used

### ✅ Simple Linear Regression
Built separate models using each feature (`TV`, `Radio`, `Newspaper`) to predict `Sales`.

### ✅ Multiple Linear Regression
Built a combined model using all three features to predict `Sales`.

## 🔍 Key Findings
- **TV** and **Radio** ads have a strong positive correlation with Sales.
- **Newspaper** ads show little to no significant impact on Sales.
- The **Multiple Linear Regression** model performs best with the highest R² score (~0.90).

## 📎 Requirements
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- scikit-learn

Install the dependencies:

```bash
pip install -r requirements.txt
