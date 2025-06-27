# 🧠 Logistic Regression Binary Classification

This project is part of the AI & ML Internship program (Task 4) and focuses on building a binary classification model using **Logistic Regression** with the **Breast Cancer Wisconsin Dataset**.

---

## 📌 Objective

- Train a **Logistic Regression** model to classify tumors as **Benign (0)** or **Malignant (1)**.
- Evaluate the model using standard binary classification metrics.
- Understand the role of the **Sigmoid function**, **Threshold tuning**, and **ROC-AUC**.

---

## 🛠 Tools & Libraries

- Python 🐍
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 📁 Dataset

- [Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

---

## 🧪 Steps Performed

1. ✅ Loaded and explored the dataset  
2. ✅ Cleaned data (removed nulls and unnecessary columns)  
3. ✅ Mapped target labels (`M` → 1, `B` → 0)  
4. ✅ Split into train/test sets and standardized features  
5. ✅ Trained a Logistic Regression model  
6. ✅ Evaluated with:
   - Confusion Matrix
   - Precision, Recall
   - ROC-AUC Score
   - Threshold Tuning
7. ✅ Visualized:
   - Sigmoid Function
   - ROC Curve

---

## 📊 Evaluation Metrics

| Metric            | Score        |
|-------------------|--------------|
| Accuracy          | *~95%*       |
| Precision         | *~96%*       |
| Recall            | *~93%*       |
| ROC-AUC Score     | *~0.98*      |

*(Exact values may vary depending on split/random seed)*

---

## 📈 Sample Plots

### ➤ Sigmoid Function
![sigmoid](images/sigmoid_plot.png)

### ➤ ROC Curve
![roc](images/roc_curve.png)

---

## 💡 Key Concepts

- **Logistic Regression**: A linear model used for binary classification.
- **Sigmoid Function**: Converts linear output into probability (0 to 1).
- **Confusion Matrix**: Evaluates performance across TP, FP, FN, TN.
- **Precision vs Recall**: Tradeoff between false positives and false negatives.
- **ROC Curve & AUC**: Performance across thresholds.

---

