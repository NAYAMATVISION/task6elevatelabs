# 🌸 K-Nearest Neighbors (KNN) Classification – Iris Dataset

This project demonstrates a simple implementation of the **K-Nearest Neighbors (KNN)** classification algorithm using **scikit-learn** on the classic **Iris dataset**.

---

## 📌 Objective

- Understand how the KNN algorithm works.
- Implement classification using KNN.
- Evaluate and visualize model performance.
- Experiment with different K values.

---

## 📂 Dataset
Dataset: [Iris Dataset - Kaggle](https://www.kaggle.com/datasets/uciml/iris)  
- Dataset: **Iris Dataset** from `sklearn.datasets`
- 150 samples, 4 features:
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width
- 3 classes: Setosa (0), Versicolor (1), Virginica (2)

---


## ✅ Tools Used

- Python
- scikit-learn
- matplotlib, seaborn
- pandas, numpy

---

## 🧠 Steps Followed

1. Imported necessary libraries
2. Loaded and explored the dataset
3. Checked for null values — ✅ None found
4. Normalized the features using `StandardScaler`
5. Split the dataset into train/test (70/30)
6. Trained KNN model (`K=3` initially)
7. Evaluated model using:
   - Accuracy
   - Confusion Matrix
   - Classification Report
![image](https://github.com/user-attachments/assets/90eb6db6-e0a5-4139-9d78-e30f704bcd16)

8. Tried values of K from 1 to 10 and plotted accuracy
9. Observed **100% accuracy** at multiple values of K
![image](https://github.com/user-attachments/assets/431f3dc0-b7e5-426c-ba4f-318b048185a8)
![image](https://github.com/user-attachments/assets/4f57395d-028b-4cb7-bda6-0cbe84b5a340)

---

## 💬 Key Learnings

- KNN is a **distance-based**, **non-parametric**, and **lazy learner**.
- Normalization is crucial for fair distance calculation.
- Choosing the right value of `K` is essential for optimal performance.
