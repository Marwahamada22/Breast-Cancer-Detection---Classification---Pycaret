![image](https://github.com/user-attachments/assets/d95859d9-1b9a-4c4c-b112-93abb114eeaa)


# 🧠 Breast Cancer Classification

Unlocking Insights into Tumor Diagnosis Using Machine Learning

## 📌 Project Overview

This project aims to analyze a dataset containing features extracted from digitized images of fine needle aspirates (FNA) of breast masses. The objective is to accurately classify tumors as **benign (B)** or **malignant (M)** using machine learning models. Through preprocessing, exploratory analysis, and model training, we aim to support early detection and improve diagnostic processes in the medical field.

---

## 📂 Dataset Information

Each record in the dataset corresponds to a tumor sample and includes:

* **ID number**

* **Diagnosis**:

  * `M` = Malignant
  * `B` = Benign

* **30 Real-Valued Features** (computed for each nucleus):
  Features are derived from:

  * Radius
  * Texture
  * Perimeter
  * Area
  * Smoothness
  * Compactness
  * Concavity
  * Concave Points
  * Symmetry
  * Fractal Dimension

  For each of these, the dataset includes:

  * Mean value
  * Standard error
  * Worst (largest mean of three worst values)

* **No missing values**

* **Class Distribution**:

  * Benign: 357 samples
  * Malignant: 212 samples

---

## 🧰 Tools and Libraries Used

* **Python**
* `pandas` – data manipulation
* `matplotlib` & `seaborn` – data visualization
* `pycaret` – fast model building and comparison

---

## 🤖 Machine Learning Models Applied

* Logistic Regression
* Decision Tree
* Random Forest
* Extra Trees
* XGBoost
* LightGBM
* CatBoost

---

## 🔍 Key Steps

1. **Data Cleaning & Preprocessing**

   * Dropped ID column
   * Converted categorical labels to numeric
   * Scaled and normalized features

2. **Exploratory Data Analysis (EDA)**

   * Visualized feature distributions and correlations
   * Plotted class imbalance
   * Identified key predictors using correlation heatmaps and feature importance

3. **Model Training & Evaluation**

   * Used PyCaret for rapid model comparison
   * Evaluated models using accuracy, ROC-AUC, precision, and recall
   * Performed cross-validation for robustness

---

## ✅ Conclusion

This project demonstrates how machine learning can effectively aid in classifying breast tumors based on image-derived data. The combination of statistical analysis and model comparison ensures high reliability in identifying malignant and benign cases, which can support faster, data-driven diagnosis in healthcare settings.

