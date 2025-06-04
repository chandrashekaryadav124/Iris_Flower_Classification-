#  ==== Iris Flower Classification Project ( Machine Learning with Scikit-learn) ====

## 📌 Overview

This project uses the classic **Iris flower dataset** to build, evaluate, and deploy machine learning models to classify iris flowers into three species:

- **Setosa**
- **Versicolor**
- **Virginica**


## 🚀 Features

### ✅ Basic Machine Learning
- Load and preprocess Iris dataset using `pandas` and `scikit-learn`
- Train-test split with `train_test_split()`
- Model training with:
  - Random Forest
  - Logistic Regression
  - SVM
  - K-Nearest Neighbors

### 📊 Visualizations (EDA)
- `seaborn` pairplot to visualize class separation
- Feature correlation heatmap

### 🔍 Evaluation
- Accuracy, precision, recall, F1-score
- Confusion matrix (raw and percentage)


### 🧠 Advanced Concepts
- KMeans clustering (unsupervised learning)

### 🧪 Experiment Tracking
- Comparison of multiple models
- Benchmarking accuracy and F1-score across classifiers

---

## 🧪 Sample Prediction

```python
model.predict([[5.1, 3.5, 1.4, 0.2]])
# Output: ['setosa']
