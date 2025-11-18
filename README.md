
# 🧠 Logistic Regression — Breast Cancer Classification

This project builds a **binary classifier** using **Logistic Regression** on the **Breast Cancer Wisconsin Dataset**.
The objective is to predict whether a tumor is **Benign (0)** or **Malignant (1)** based on multiple diagnostic features.

---

## 🔧 What I Did

### **1️⃣ Data Loading & Cleaning**

* Loaded the dataset from a local CSV file.
* Removed unnecessary columns (e.g., `id` and missing-value columns).
* Converted the diagnosis column into binary labels (**M → 1**, **B → 0**).

### **2️⃣ Train/Test Split & Preprocessing**

* Split the dataset into training and testing sets.
* Standardized all numerical features using `StandardScaler` to improve model performance.

### **3️⃣ Model Training**

* Trained a **Logistic Regression** model using scikit-learn.
* Used the scaled training data for learning.

### **4️⃣ Model Evaluation**

Evaluated the model using multiple metrics:

* **Confusion Matrix**
* **Precision, Recall, F1-score**
* **ROC Curve**
* **ROC-AUC score**

These metrics helped assess how well the model distinguishes between malignant and benign tumors.

### **5️⃣ Threshold Tuning**

* Tested different classification thresholds (0.3, 0.5, 0.7).
* Observed how threshold changes affect false positives, false negatives, and overall model behavior.

### **6️⃣ Sigmoid Function Visualization**

* Plotted the **sigmoid function**, which is the core of logistic regression.
* Explained how it converts linear outputs into probabilities (0–1).

---

## 🎯 Final Result

The logistic regression model demonstrated strong performance in classifying tumors, showing its effectiveness in medical diagnostic tasks.

---

If you want, I can also create:
✅ A full README.md
✅ A project structure
✅ A short summary for GitHub description
Just tell me!
