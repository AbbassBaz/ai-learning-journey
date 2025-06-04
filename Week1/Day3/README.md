# Day 3 – Logistic Regression vs Decision Tree (Iris Dataset)

## 📌 Objective:
To compare two popular classification algorithms — Logistic Regression and Decision Tree — on the Iris dataset using scikit-learn.

---

## ⚙️ Models Used:
- Logistic Regression (`sklearn.linear_model`)
- Decision Tree Classifier (`sklearn.tree`)
- Evaluation using `accuracy_score`

---

## 🧪 Experiments:
- Tried different `test_size` values: 0.2, 0.3, 0.4
- Changed `random_state` and noticed variation in results
- Compared model performance on same data splits
- Adjusted `max_depth` for tree to observe generalization
- Visualized data using `ConfusionMatrixDisplay`

---

## 📊 Results:
| Test Size | Random State | Logistic Accuracy | Tree Accuracy |
|-----------|--------------|-------------------|----------------|
| 0.2       | 42           | 1.0               | 1.0            |
| 0.3       | 1            | 0.91              | 0.89           |
| 0.4       | 12           | 0.90              | 0.85           |

---

## 🧠 Key Learnings:
- Accuracy is sensitive to data split (`random_state`)
- Decision Trees can overfit small datasets
- Changing `max_depth` helps control overfitting
- Accuracy alone isn't always a reliable metric (set up for Day 4!)

---
