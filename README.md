# 🩺 Breast Cancer Diagnosis Prediction (Machine Learning Project)

A complete end-to-end machine learning pipeline for predicting **malignant vs. benign** breast tumors using the **Breast Cancer Wisconsin Dataset**.  
This project includes **EDA, preprocessing, model training, hyperparameter tuning, PCA analysis, and full evaluation** through metrics and visualizations.

---

## 📌 Project Overview
This project evaluates three supervised ML classifiers:

- **Logistic Regression**
- **Support Vector Machine (SVM) – Best Model**
- **Random Forest**

Each model is trained in three stages:

1. **Baseline Model**
2. **Hyperparameter-Tuned Model (Grid Search / Random Search)**
3. **PCA-Enhanced Model (Dimensionality Reduction)**

We compare all models across Accuracy, Precision, Recall, F1-score, and ROC AUC.

---

## 📊 Key Features
### ✔ Exploratory Data Analysis (EDA)
- Correlation heatmap  
- Distribution plots  
- Class balance analysis  

### ✔ Preprocessing
- Standardization with `StandardScaler`  
- Train-test split  
- Handling dimensionality with PCA  

### ✔ Model Training
Implemented and evaluated:
- Logistic Regression  
- SVM (RBF kernel)  
- Random Forest  

### ✔ Hyperparameter Tuning
- Logistic Regression → `GridSearchCV`  
- SVM → `GridSearchCV`  
- Random Forest → `RandomizedSearchCV`  

### ✔ PCA (Dimensionality Reduction)
- Retained **95% variance**
- Improved training speed
- Reduced noise while keeping performance stable

---

## 🏆 Results Summary
| Model | Best Version | Accuracy | ROC AUC | Notes |
|------|--------------|----------|---------|-------|
| **SVM** | Tuned | **98%** | **0.997** | ⭐ Best performer overall |
| Logistic Regression | Tuned | 97% | 0.997 | Improved with tuning |
| Random Forest | Baseline | 96% | 0.993 | Tuning did not improve |

### 📌 Final Winner → **SVM (RBF Kernel)**  
Highest and most stable metrics across all evaluations.

---

## 📈 Visualizations Included
- ROC Curves  
- Confusion Matrices  
- PCA Explained Variance Plot  
- Before/After Tuning Comparison Bars  
- Heatmaps  

---

## 🧠 Project Workflow
1. Load dataset  
2. Preprocess (scaling, splitting)  
3. Train baseline models  
4. Perform hyperparameter tuning  
5. Apply PCA (95% variance retained)  
6. Train PCA-based models  
7. Compare all results  
8. Visualize and conclude  

---

## 📚 Technologies Used
- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 📝 Conclusion
This project demonstrates how **hyperparameter optimization** and **dimensionality reduction** improve model efficiency and reliability in medical prediction tasks.  
The SVM classifier produced the strongest results, achieving **98% accuracy** and **a nearly perfect AUC score**, making it a robust tool for breast cancer diagnosis prediction.

---

## 👩‍💻 Authors
- **Maya Halabi**   

---

## 📦 Project Files
- `FinalProject.ipynb` – Full notebook  
- `Final Report.docx` – Complete written report  
- `README.md` – This file  

---

If you like this project, ⭐ **star the repository** on GitHub!
