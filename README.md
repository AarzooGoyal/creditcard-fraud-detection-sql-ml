# creditcard-fraud-detection-sql-ml
End-to-end fraud detection using SQL &amp; Python — logistic regression + unsupervised anomaly scoring

# 💳 Credit Card Fraud Detection (SQL + Python)

This project demonstrates a complete **fraud detection pipeline** built from scratch using Python and SQL logic.  
It applies both **supervised learning (Logistic Regression)** and **unsupervised anomaly detection (Mahalanobis distance)** on the Kaggle Credit Card Fraud dataset.

### 🔍 Highlights
- Handles **highly imbalanced data (0.17% fraud)** without external libraries.
- Implements Logistic Regression and Mahalanobis scoring **purely in NumPy** (no scikit-learn).
- Performs **SQL-style EDA** and threshold tuning for business-relevant precision-recall trade-offs.
- Fully runnable on Kaggle, lightweight, and dependency-free.

### 📊 Key Techniques
`NumPy` · `Pandas` · `Matplotlib` · `SQLite` · Logistic Regression · Anomaly Detection

---

### 📈 Example Results
| Model | Precision | Recall | F1 | ROC-AUC |
|--------|------------|--------|----|---------|
| Logistic Regression | 0.92 | 0.88 | 0.90 | 0.98 |
| Mahalanobis (unsupervised) | 0.65 | 0.95 | 0.77 | 0.91 |

*(values illustrative)*

---

### 📁 Folder Structure

