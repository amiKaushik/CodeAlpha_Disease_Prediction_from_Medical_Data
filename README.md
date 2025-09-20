# 🏥 Disease Prediction from Medical Data

## 📌 Project Overview

This project focuses on predicting diseases using multiple **UCI medical datasets**. The aim is to classify whether a patient is likely to have a disease such as **Heart Disease, Breast Cancer, or Diabetes** based on clinical and demographic features.

The workflow includes preprocessing, training, evaluation, and visualization using a variety of machine learning algorithms.

---

## 🎯 Objectives

* Preprocess and clean medical datasets (handle missing values, scaling, encoding).
* Train multiple classifiers: **Logistic Regression, SVM, Random Forest, XGBoost**.
* Evaluate models using accuracy, precision, recall, F1-score, and ROC-AUC.
* Visualize **ROC curves** for performance comparison.
* Save trained models and generate a summary of results.

---

## 📊 Datasets

1. **Heart Disease (Cleveland Dataset)**

   * Features: Age, sex, chest pain type, resting blood pressure, cholesterol, etc.
   * Target: Presence (1) or absence (0) of heart disease.

2. **Breast Cancer Wisconsin (Diagnostic Dataset)**

   * Features: Cell nucleus measurements from digitized images.
   * Target: Benign (0) or Malignant (1).

3. **Pima Indians Diabetes Dataset**

   * Features: Glucose, blood pressure, BMI, insulin, etc.
   * Target: Diabetic (1) or Non-diabetic (0).

---

## ⚙️ Approach

1. **Data Preprocessing**

   * Handle missing values (median or most frequent imputation).
   * Replace medically invalid zero values with `NaN` and impute.
   * Standardize features using `StandardScaler`.

2. **Model Training**

   * Logistic Regression (with class balancing where needed).
   * Random Forest Classifier.
   * XGBoost Classifier.
   * Support Vector Machine (RBF kernel).
   * Ensemble Voting Classifier (for Diabetes dataset).

3. **Evaluation Metrics**

   * Confusion Matrix.
   * Classification Report (Precision, Recall, F1-Score).
   * ROC-AUC Score.
   * ROC Curve visualization.

---

## 📈 Results

* **Heart Disease:** Random Forest and XGBoost showed strong predictive power.
* **Breast Cancer:** Logistic Regression achieved high performance due to linearly separable data.
* **Diabetes:** Ensemble Voting improved robustness and balanced performance.

---

## 🔧 Tech Stack

* **Programming Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, ucimlrepo
* **ML Models:** Logistic Regression, Random Forest, XGBoost, SVM, Ensemble Voting

---

## 📂 Repository Structure

```
├── Disease_Prediction_from_Medical_Data.ipynb
├── requirements.txt
├── README.md
```

---

## 🚀 How to Run

1. Clone this repo:

   ```bash
   git clone https://github.com/amiKaushik/CodeAlpha_Disease_Prediction_from_Medical_Data.git
   cd CodeAlpha_Disease_Prediction_from_Medical_Data
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook:

   ```bash
   jupyter notebook Disease_Prediction_from_Medical_Data.ipynb
   ```

---

## 📌 Future Improvements

* Hyperparameter tuning for all classifiers.
* Apply advanced models like LightGBM or CatBoost.
* Use feature selection and dimensionality reduction (PCA).
* Deploy as a **web application** for real-time disease prediction.

---

## 📬 Contact

👤 **Kaushik**
🔗 [LinkedIn](https://www.linkedin.com/in/kaushik-das-919928317) | [GitHub](https://github.com/amiKaushik)
