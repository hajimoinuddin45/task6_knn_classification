# 🌼 KNN Classification – Iris Dataset

This repository contains my solution for **Task 6: K-Nearest Neighbors (KNN)** using the famous Iris flower dataset.

---

## 🎯 Objective

- Implement the KNN algorithm.
- Evaluate accuracy for different values of K.
- Visualize how the K value affects the model performance.
- Plot decision boundaries (for 2D case).

---

## 🛠 Tools Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## ✅ What I Did

1. Loaded the **Iris dataset** from sklearn.
2. Normalized the features using `StandardScaler`.
3. Split data into training and testing sets.
4. Trained the `KNeighborsClassifier` with values of K from 1 to 20.
5. Plotted K vs Accuracy to select the best K.
6. Evaluated model using accuracy, confusion matrix, classification report.
7. Visualized decision boundaries in 2D using first two features.

---

## 📊 Results

- Best value of K (from testing): **k = [your result]**
- Accuracy: **[your accuracy]**
- Visualization shows how well KNN separates different classes.

---

## 🧠 What I Learned

- KNN is a **distance-based algorithm**.
- **Normalization** is crucial as KNN relies on distance.
- Proper selection of **K** is important to avoid underfitting/overfitting.
- Simple to implement but **computationally expensive** for large datasets.

---

## 📁 Files

- `task6_knn_classification.ipynb`
- `README.md`

---

## 🔗 Dataset Source

- Built-in Iris dataset from Scikit-learn

---

Feel free to run the notebook, change the K value, and try with other datasets!
