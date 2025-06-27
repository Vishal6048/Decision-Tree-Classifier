# CodTech Internship - Task 1: Decision Tree Classification

This repository contains the implementation of **Task 1** for the CodTech Machine Learning Internship. The project builds and evaluates a Decision Tree Classifier using the Iris dataset, following a full machine learning pipeline.

## 🎯 Task Objective
Build and visualize a **Decision Tree model** to classify/predict outcomes on a chosen dataset. Perform preprocessing, exploratory data analysis, model training, evaluation, and visualization.

## 📦 Dataset
The dataset used is the **Iris dataset**, which is available by default in `scikit-learn`.

- 150 samples
- 4 features: sepal length, sepal width, petal length, petal width
- 3 target classes: Iris-setosa, Iris-versicolor, Iris-virginica

No external file is required.

## 📊 Workflow Overview

### 1. 🧪 **Exploratory Data Analysis**
- Summary statistics using `.describe()`
- Correlation heatmap
- Pairplots with target hue

### 2. 🧹 **Preprocessing**
- No null values or categorical encoding needed
- Features and labels split into `X` and `y`
- Train-test split (80-20)

### 3. 🌳 **Modeling**
- Algorithm: `DecisionTreeClassifier`
- Criterion: `entropy`
- Max depth: 3
- Trained on training data

### 4. 📈 **Evaluation**
- Accuracy score
- Confusion matrix
- Classification report

### 5. 🌿 **Visualization**
- Visualized the trained tree using `plot_tree()` from scikit-learn

## 📁 Files Included
- `Task_1_Decision_Tree_Classification.ipynb`: Complete Jupyter Notebook with all steps and outputs.

## 🛠️ Tools Used
- Python
- scikit-learn
- matplotlib
- seaborn
- pandas

---

