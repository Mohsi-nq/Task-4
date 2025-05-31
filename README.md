# Task 4 - Logistic Regression on Breast Cancer Wisconsin Dataset

This task demonstrates binary classification using **Logistic Regression** on the **Breast Cancer Wisconsin** dataset. The goal is to predict whether a tumor is **malignant (1)** or **benign (0)**.

---

## Objective

1. Choose a binary classification dataset.
2. Train/test split and standardize features.
3. Fit a Logistic Regression model.
4. Evaluate with confusion matrix, precision, recall, ROC-AUC.
5. Tune threshold and explain sigmoid function.

---

## Dataset

- **Source**: `/kaggle/input/breast-cancer-wisconsin-data/data.csv`
- **Target column**: `diagnosis` (converted to 0 = Benign, 1 = Malignant)

---

## Tools & Libraries Used

- Python
- Pandas, NumPy
- scikit-learn (LogisticRegression, metrics, train_test_split)
- matplotlib & seaborn for visualizations

---
## Steps Performed

### Step 1: Load and explore dataset
- Checked for NaN values
- Converted diagnosis to numerical
- Dropped unnecessary columns (e.g., ID)

### Step 2: Preprocessing
- Split data into train and test sets
- Standardized features

### Step 3: Train Logistic Regression model
- Used `LogisticRegression()` from scikit-learn

### Step 4: Evaluation
- Used confusion matrix, classification report
- Plotted ROC curve
- Calculated ROC-AUC score

### Step 5: Threshold tuning
- Adjusted classification threshold to improve recall
- Explained how sigmoid affects predictions

