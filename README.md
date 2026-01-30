# 📊 Statistical Learning: From Linear Models to Bias–Variance Tradeoff

![Python](https://img.shields.io/badge/Python-3.9-blue) ![Statsmodels](https://img.shields.io/badge/Library-Statsmodels-orange) ![Status](https://img.shields.io/badge/Status-Active-green)

This repository contains a **practical implementation and in-depth analysis** of the fundamental concepts of **Statistical Learning**.

The objective is not only to fit models, but to dissect the **statistical inference** underlying the predictions.

## 🧠 Key Concepts Implemented

### 1. Inference in Linear Regression
Exploration of the relationship between marketing budgets and sales.
- **Hypothesis Testing:** Use of *t-statistics* and *p-values* to assess statistical significance (TV & Radio vs. Newspaper).
- **Confidence Intervals:** Interpretation of uncertainty in the regression coefficients $\beta$.

### 2. Multiple Regression and Collinearity
Demonstration of how correlation between predictors can mislead a simple model.
- **Visualization:** Least squares hyperplane representation.
- **Residual Analysis:** Validation of linear regression assumptions.

### 3. The Bias–Variance Tradeoff
Numerical simulation to visualize error decomposition:
$$
E[(y - \hat{f}(x))^2] = Var(\hat{f}(x)) + [Bias(\hat{f}(x))]^2 + Var(\epsilon)
$$

## 🛠️ Technologies
- **Python**: NumPy, Pandas.
- **Statistical Analysis**: Statsmodels (detailed, R-style statistical reports).
- **Visualization**: Seaborn & Plotly (interactive visualizations).

## 🚀 How to Run
```bash
git clone https://github.com/your-username/statistical-learning-islr.git
pip install -r requirements.txt
jupyter notebook
