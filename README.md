# Heart Disease Prediction using Machine Learning

A Machine Learning project that predicts whether a patient is likely to have heart disease based on various clinical parameters. In this project, multiple machine learning algorithms were trained, evaluated, and compared to identify the best-performing model. The final model was selected based on evaluation metrics such as Accuracy, Precision, Recall, F1-Score, ROC-AUC Score, and Cross Validation.

---

# 📌 Problem Statement

Heart disease is one of the leading causes of death worldwide. Early prediction of heart disease can help doctors provide timely treatment and improve patient outcomes.

The objective of this project is to build an intelligent machine learning model that predicts the presence of heart disease using patient medical information.

---

# 📂 Dataset Information

- **Dataset Name:** Heart Disease Dataset
- **Total Records:** 1025
- **Features:** 14
- **Target Variable:** target

### Target Values

- **0** → No Heart Disease
- **1** → Heart Disease

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Joblib
- Streamlit

---

# 📊 Exploratory Data Analysis (EDA)

The following data analysis was performed before model building:

- Missing Value Analysis
- Duplicate Removal
- Outlier Detection
- Univariate Analysis
- Bivariate Analysis
- Correlation Analysis
- Feature Importance Analysis

---

# ⚙️ Data Preprocessing

The following preprocessing steps were applied:

- Removed duplicate records
- Checked missing values
- Performed outlier analysis
- Train-Test Split
- Feature Scaling (Experimented)
- Model Evaluation Preparation

---

# 🤖 Machine Learning Models Used

The following classification algorithms were trained and evaluated:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. XGBoost Classifier

---

# 📈 Model Evaluation Metrics

The following evaluation metrics were used:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score
- Cross Validation
- Hyperparameter Tuning (GridSearchCV)

---

# 🏆 Model Comparison

| Model | Accuracy | ROC-AUC |
|--------|----------|----------|
| Logistic Regression | **80.33%** | **0.860** |
| Decision Tree | 72.13% | 0.801 |
| Random Forest | 77.05% | 0.857 |
| XGBoost | 72.13% | 0.834 |

---
