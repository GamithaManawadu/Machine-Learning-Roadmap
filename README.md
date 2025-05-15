# 📌 Machine Learning Fundamentals

A complete ML learning journey from fundamentals to deep learning, with **interactive HTML guides** that explain every notebook in plain language with school-friendly analogies.

> **💡 Click the "View Explanation" links below to see beautiful, interactive HTML pages that break down each notebook concept by concept.**

---

## 📚 Overview

| #   | Notebook                       | Topics                                                                                      | Explanation                                                                                                                                                       |
| --- | ------------------------------ | ------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | `machine-learning-part1.ipynb` | Supervised/Unsupervised/RL, California Housing, K-Means, Q-Learning, ML Pipeline            | [🔗 View Explanation](https://htmlpreview.github.io/?https://github.com/GamithaManawadu/Machine-Learning-Projects/blob/main/Explanations/ml-part1-explained.html) |
| 2   | `machine-learning-part2.ipynb` | Linear/Polynomial Regression, MSE/RMSE/R², Cross-Validation, Bias-Variance, Ridge/Lasso     | [🔗 View Explanation](https://htmlpreview.github.io/?https://github.com/GamithaManawadu/Machine-Learning-Projects/blob/main/Explanations/ml-part2-explained.html) |
| 3   | `machine-learning-part3.ipynb` | Logistic Regression, Decision Trees, SVM, Ensembles (RF, XGBoost), ROC/AUC, Class Imbalance | [🔗 View Explanation](https://htmlpreview.github.io/?https://github.com/GamithaManawadu/Machine-Learning-Projects/blob/main/Explanations/ml-part3-explained.html) |
| 4   | `machine-learning-part4.ipynb` | Perceptrons, Backpropagation, Activation Functions, Keras/TF, CNNs, RNNs, Optimizers        | [🔗 View Explanation](https://htmlpreview.github.io/?https://github.com/GamithaManawadu/Machine-Learning-Projects/blob/main/Explanations/ml-part4-explained.html) |

---

## 📖 What's Inside Each Explanation

Every HTML page features:

- **Expandable accordion sections** — click to explore each topic
- **School-friendly analogies** — every concept explained with everyday comparisons
- **Color-coded callouts** — key points, warnings, analogies, and info boxes
- **Comparison tables** — side-by-side model/technique breakdowns
- **Actual results** — real accuracy numbers and metrics from the notebooks

---

## 📌 What's Covered

### Part 1 — ML Fundamentals & Core Concepts

- **Linear Regression** on California Housing dataset (EDA, correlation heatmap, train/test split, evaluation metrics, residual analysis, learning curves)
- **Unsupervised Learning**: K-Means customer segmentation on synthetic data (elbow method, cluster visualization)
- **Reinforcement Learning**: Q-Learning grid world navigation (reward curves, policy visualization, state visits, animated trajectories)
- **Features & Labels** with Wine classification using Random Forest (100% test accuracy)
- **Complete ML Pipeline**: Data loading → EDA → splitting → scaling → training → evaluation
- **Underfitting vs Overfitting**: Polynomial degree comparison (degree 1, 5, 15) on synthetic sine data
- **Data Handling**: Loading, EDA, and preprocessing on synthetic customer data (missing value imputation, outlier removal via IQR, feature scaling, categorical encoding)

### Part 2 — Regression, Classification & Regularization

- **Simple Linear Regression** — CO2 emissions from engine size (R² = 0.76)
- **Multivariable Linear Regression** — CO2 from 6 vehicle features (R² = 0.90)
- **Linear Regression Assumptions** — visual examples of linearity, homoscedasticity, normality (good vs violated)
- **Comprehensive CO2 Analysis** — EDA, VIF multicollinearity check, OLS vs Ridge vs Lasso vs ElasticNet comparison, feature importance, residual diagnostics
- **Polynomial Regression** — capturing non-linear relationships, degree comparison (underfitting → good fit → overfitting)
- **Evaluation Metrics Deep Dive** — MSE, RMSE, MAE, R², Adjusted R² across normal, outlier, and heteroscedastic datasets
- **Company Profit Prediction** — linear vs polynomial regression on 1000 Companies dataset (R² = 0.98)
- **Logistic Regression** — sigmoid function, binary classification on Iris, multi-class decision boundaries
- **Decision Trees** — Iris classification with decision boundary visualization
- **Wine Quality Classification** — multi-class on UCI Red Wine dataset with detailed classification reports
- **Bias-Variance Tradeoff** — training on 50 random datasets to decompose bias², variance, and irreducible error
- **Regularization** — Ridge (L2), Lasso (L1), ElasticNet with alpha tuning via GridSearchCV
- **Model Saving/Loading** with `joblib`

## 🗺️ Learning Path

```
Part 1: ML Fundamentals ──→ Part 2: Regression ──→ Part 3: Classification
                                                            │
Part 4: Deep Learning (Neural Networks, CNNs, RNNs) ◄──────┘

```

## ⚙️ Setup

```bash
# Clone the repo
git clone https://github.com/GamithaManawadu/Machine-Learning-Projects.git
cd Machine-Learning-Projects

# Create virtual environment
python -m venv .venv
source .venv/bin/activate        # Linux/Mac
.venv\Scripts\activate           # Windows

# Install dependencies
pip install -r requirements.txt
```
