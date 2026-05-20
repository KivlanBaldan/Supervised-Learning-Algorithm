# A comprehensive collection of classic Supervised Learning algorithms implemented from scratch and using Scikit-Learn, featuring data preprocessing, model evaluation, and performance visualization.


Welcome to my Supervised Learning repository! This project serves as a comprehensive sandbox and portfolio demonstrating the core mathematical concepts, practical implementations, and performance evaluations of foundational supervised machine learning algorithms.

The goal is to bridge the gap between theoretical machine learning math and production-ready code by building models both **from scratch** (to master the underlying optimization math) and using optimized industry libraries like **Scikit-Learn**.

---

## 🚀 Key Features
- **Dual Implementations:** Selected algorithms are coded from scratch using raw NumPy/Pandas alongside their optimized Scikit-Learn counterparts.
- **Comprehensive Pipelines:** Every model implementation includes data preprocessing (scaling, encoding, train-test splits) and exploratory data analysis (EDA).
- **Evaluation Frameworks:** Built-in scripts to calculate and visualize metrics like Accuracy, Precision, Recall, F1-Score, ROC-AUC, MSE, and $R^2$ scores.

---

## 🛠️ Algorithms Implemented

### 📈 Regression (Continuous Outputs)
- **Linear Regression:** Implementation of Ordinary Least Squares (OLS) and Gradient Descent optimization.
- **Polynomial & Ridge/Lasso Regression:** Regularization techniques to handle overfitting and multicollinearity.

### 📊 Classification (Discrete Outputs)
- **Logistic Regression:** Binary and multiclass (One-vs-Rest) classification using the sigmoid/softmax activation functions.
- **Decision Trees & Random Forests:** Tree-splitting mechanics based on Gini Impurity and Information Gain (Entropy), extended to ensemble bagging.
- **Support Vector Machines (SVM):** Maximum-margin classification with linear and RBF kernel implementations.
- **K-Nearest Neighbors (KNN):** Distance-based instance learning utilizing Euclidean and Manhattan metrics.

---

## 📁 Repository Structure
```text
├── data/                  # Sample datasets (e.g., Iris, Housing, Titanic)
├── notebooks/             # Jupyter Notebooks for EDA and step-by-step math walk-throughs
├── src/                   # Production-ready Python scripts
│   ├── models/            # Custom algorithm implementations from scratch
│   └── utils/             # Data preprocessing and evaluation metric helpers
├── requirements.txt       # Project dependencies
└── README.md              # Project documentation
