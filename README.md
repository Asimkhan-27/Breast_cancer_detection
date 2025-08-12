# Breast Cancer Detection

This repository contains two Jupyter Notebooks demonstrating breast cancer detection using logistic regression:

- **manual_train.ipynb**: Implements logistic regression from scratch (manual gradient descent, cost function, etc.) with PCA visualization.
- **breast_cancer_prediction.ipynb**: Uses scikit-learn for preprocessing, model training, and evaluation.

---

## 📁 Contents

- `notebooks/manual_train.ipynb` — Manual implementation of logistic regression, including:
  - Data preprocessing and feature scaling
  - PCA for visualization
  - Manual gradient descent and cost calculation
  - Visualization of loss curve and decision boundary
  - Confusion matrix and accuracy evaluation

- `notebooks/breast_cancer_prediction.ipynb` — Scikit-learn pipeline, including:
  - Data preprocessing and feature scaling
  - Logistic regression with scikit-learn
  - Confusion matrix and accuracy evaluation

---

## 🚀 How to Run

1. Clone this repository:
    ```bash
    git clone https://github.com/Asimkhan-27/breast_cancer_detection.git
    cd breast_cancer_detection/notebooks
    ```

2. Make sure you have the required libraries:
    ```bash
    pip install numpy pandas matplotlib seaborn scikit-learn
    ```

3. Open the notebooks in Jupyter or VS Code and run the cells.

---

## 📊 Dataset

The dataset used is [Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29), included as `data/data.csv`.

---

## ✨ Results

- Both approaches achieve high accuracy in classifying malignant and benign tumors.
- The manual notebook provides insight into the math behind logistic regression.
- The scikit-learn notebook demonstrates rapid prototyping and evaluation.

---

## 📷 Visualizations

- Loss curve (cost function convergence)
- PCA scatter plot of data
- Decision boundary in PCA space
- Confusion matrix heatmap

---


---

**Feel free to fork, use, and contribute!**
