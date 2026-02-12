# Perceptron for Binary Classification – Iris Dataset

## Project Overview
perceptron-binary-classification-iris/
│
├── README.md
├── perceptron_iris_binary.ipynb
└── results/
      ├── confusion_matrix.png
      └── decision_boundary.png


## 📌 Overview

This project demonstrates the implementation of the Perceptron algorithm for binary classification using the Iris dataset. The objective is to classify Setosa vs Versicolor using linear decision boundaries.

## 🧠 Model Used

* Algorithm: Perceptron (Linear Classifier)
* Library: scikit-learn
* Optimization: Stochastic Gradient Descent
* Activation: Step Function

## 📊 Dataset

* Source: UCI Machine Learning Repository (Iris Dataset)
* Classes Used: Setosa (0) and Versicolor (1)
* Features: Sepal Length, Sepal Width, Petal Length, Petal Width

## 🔍 Steps Performed

1. Data Loading & Exploration
2. Feature Scaling (StandardScaler)
3. Train-Test Split (80-20)
4. Model Training
5. Evaluation (Accuracy, Classification Report, Confusion Matrix)
6. Decision Boundary Visualization

## 📈 Results

* Accuracy: (Add your actual accuracy here)
* Model successfully separates linearly separable classes.
* Visualized decision boundary confirms linear classification.

## 📦 Requirements

```bash
pip install pandas numpy matplotlib seaborn scikit-learn ucimlrepo
```

## 🚀 How to Run

Open the notebook:

```
jupyter notebook perceptron_iris_binary.ipynb
```

## 📌 Key Learnings

* Perceptron works only for linearly separable data
* Feature scaling significantly impacts convergence
* Visualization helps interpret linear decision boundaries

---

Author: Aryan Singh Sisodia

