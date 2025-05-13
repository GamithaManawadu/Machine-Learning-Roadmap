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

- **Expandable accordion sections** - click to explore each topic
- **School-friendly analogies** - every concept explained with everyday comparisons
- **Color-coded callouts** - key points, warnings, analogies, and info boxes
- **Comparison tables** - side-by-side model/technique breakdowns
- **Actual results** - real accuracy numbers and metrics from the notebooks

---

## 📌 What's Covered

### Part 1 - ML Fundamentals & Core Concepts

- **Linear Regression** on California Housing dataset (EDA, correlation heatmap, train/test split, evaluation metrics, residual analysis, learning curves)
- **Unsupervised Learning**: K-Means customer segmentation on synthetic data (elbow method, cluster visualization)
- **Reinforcement Learning**: Q-Learning grid world navigation (reward curves, policy visualization, state visits, animated trajectories)
- **Features & Labels** with Wine classification using Random Forest (100% test accuracy)
- **Complete ML Pipeline**: Data loading → EDA → splitting → scaling → training → evaluation
- **Underfitting vs Overfitting**: Polynomial degree comparison (degree 1, 5, 15) on synthetic sine data
- **Data Handling**: Loading, EDA, and preprocessing on synthetic customer data (missing value imputation, outlier removal via IQR, feature scaling, categorical encoding)

### Part 2 - Regression, Classification & Regularization

- **Simple Linear Regression** - CO2 emissions from engine size (R² = 0.76)
- **Multivariable Linear Regression** - CO2 from 6 vehicle features (R² = 0.90)
- **Linear Regression Assumptions** - visual examples of linearity, homoscedasticity, normality (good vs violated)
- **Comprehensive CO2 Analysis** - EDA, VIF multicollinearity check, OLS vs Ridge vs Lasso vs ElasticNet comparison, feature importance, residual diagnostics
- **Polynomial Regression** - capturing non-linear relationships, degree comparison (underfitting → good fit → overfitting)
- **Evaluation Metrics Deep Dive** - MSE, RMSE, MAE, R², Adjusted R² across normal, outlier, and heteroscedastic datasets
- **Company Profit Prediction** - linear vs polynomial regression on 1000 Companies dataset (R² = 0.98)
- **Logistic Regression** - sigmoid function, binary classification on Iris, multi-class decision boundaries
- **Decision Trees** - Iris classification with decision boundary visualization
- **Wine Quality Classification** - multi-class on UCI Red Wine dataset with detailed classification reports
- **Bias-Variance Tradeoff** - training on 50 random datasets to decompose bias², variance, and irreducible error
- **Regularization** - Ridge (L2), Lasso (L1), ElasticNet with alpha tuning via GridSearchCV
- **Model Saving/Loading** with `joblib`

### Part 3 - Classification Algorithms & Ensemble Methods

- **Logistic Regression** - binary (Breast Cancer 94.7%), multiclass (Wine 94.4%, Iris 97.4%, Digits 96.0%), sigmoid function, multinomial extension
- **Titanic Survival Prediction** - full project: missing data handling, feature encoding, StandardScaler, stratified split, ~80% accuracy (sex as strongest predictor)
- **Decision Trees** — entropy vs Gini impurity, information gain, pruning strategies (max_depth, min_samples_split/leaf), feature importance, decision path tracing
- **Support Vector Machines** - maximum margin, support vectors, C parameter (regularization), gamma parameter, kernel trick (linear, RBF, polynomial), GridSearchCV hyperparameter tuning, scaling sensitivity
- **Random Forest** - bagging, bootstrap sampling, out-of-bag (OOB) score, max_features impact on diversity, feature importance
- **AdaBoost** - sequential boosting, sample weight evolution, estimator weights, margin analysis, staged predictions
- **Gradient Boosting** - residual fitting, learning rate vs n_estimators tradeoff, partial dependence plots, stochastic gradient boosting
- **XGBoost** - L1/L2 regularization, column subsampling, early stopping, evaluation history, feature importance by gain
- **Performance Evaluation** - confusion matrix (TP/TN/FP/FN), precision, recall, F1-score, ROC curves, AUC scores, precision-recall curves, threshold analysis
- **Class Imbalance Handling** - class weights, SMOTE (synthetic minority oversampling), Balanced Random Forest - all methods boosting minority recall from ~0% to 95–100%
- **German Credit Risk Project** - real-world dataset (1,000 customers), ColumnTransformer pipeline, 4-model comparison (Logistic Regression, Decision Tree, SVM, Random Forest)

### Part 4 - Neural Networks & Deep Learning

- **Perceptron** - linear separability, perceptron learning rule, XOR problem (perceptron fails at 50%)
- **Multi-Layer Perceptron (MLP)** - hidden layers solve XOR (100% accuracy), Universal Approximation Theorem, from-scratch NumPy implementation
- **Backpropagation** - forward pass, backward pass, chain rule, gradient computation, DetailedNN class with [2,8,4,1] architecture, gradient magnitude visualization, activation distributions
- **Activation Functions** - Sigmoid, Tanh, ReLU, Leaky ReLU, Swish, GELU - properties comparison, vanishing gradient problem, dead neuron problem in ReLU
- **Keras/TensorFlow** - Sequential API, Digits classification (128→64→32 MLP), Dropout, EarlyStopping, ReduceLROnPlateau, softmax output, classification reports
- **Convolutional Neural Networks (CNNs)** - MNIST handwriting (28×28), Conv2D → BatchNorm → MaxPooling → Dropout architecture, data augmentation (ImageDataGenerator), feature map visualization, CNN vs MLP comparison
- **Recurrent Neural Networks (RNNs)** - synthetic time series prediction, 5 architectures compared: SimpleRNN, LSTM, GRU, Bidirectional LSTM, Stacked LSTM - performance vs complexity analysis
- **Optimizer Comparison** - SGD, SGD+Momentum, RMSprop, Adam, AdamW on California Housing regression - convergence speed and final performance
- **Regularization Techniques** - Baseline vs L2 vs Dropout vs BatchNormalization vs Combined - overfitting gap analysis, training stability, L2 strength sweep (0 → 1.0)

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
