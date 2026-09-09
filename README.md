# Multiple Disease Prediction System

### A Machine Learning–Based Clinical Decision Support Framework

## 📌 Research Context

This repository presents a **Machine Learning–based Multiple Disease Prediction System** developed as part of a broader research direction in **AI-driven medical diagnosis and clinical decision support systems**.

The system serves as a **foundational framework** for investigating how machine learning models can support **early disease prediction**, with a planned extension toward **fuzzy logic–based reasoning and deep learning** for uncertainty-aware and interpretable clinical decision support.

---

## 🩺 Diseases Covered

The framework currently supports prediction for four major diseases using validated medical datasets:

* **Diabetes Mellitus**
* **Heart Disease**
* **Parkinson’s Disease**
* **Breast Cancer**

Each disease module is developed and evaluated independently, allowing comparative analysis across different machine learning techniques.

---

## 🧠 System Overview

The web-based application enables users to:

1. Select a disease prediction module
2. Input clinically relevant features
3. Obtain real-time prediction results

The architecture is modular and extensible, supporting future integration of:

* Fuzzy inference systems for risk stratification
* Deep learning models for enhanced predictive performance
* Hybrid ML–DL–Fuzzy decision pipelines

---

## 🧩 Research-Oriented Architecture

```
Patient Clinical Data
        ↓
Data Preprocessing & Feature Engineering
        ↓
Machine Learning Models
        ↓
Probability-Based Predictions
        ↓
(Planned Extension)
Fuzzy Logic–Based Clinical Risk Interpretation
```

---

## 📊 Datasets

Publicly available benchmark datasets were used to ensure reproducibility and comparability.

| Disease             | Samples | Features |
| ------------------- | ------- | -------- |
| Diabetes            | 768     | 8        |
| Heart Disease       | 1025    | 14       |
| Parkinson’s Disease | 195     | 22       |
| Breast Cancer       | 569     | 30       |

Each dataset includes clinically significant attributes such as physiological measurements, biomedical signals, and diagnostic indicators.

---

## ⚙️ Technologies Used

* **Programming Language:** Python
* **Web Framework:** Streamlit
* **Machine Learning:** Scikit-learn, XGBoost
* **Data Analysis:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn

---

## 🔬 Model Development Methodology

The model development process follows a **research-driven pipeline**:

1. Exploratory Data Analysis (EDA)
2. Data preprocessing

   * Missing value handling
   * Outlier treatment
   * Feature scaling and encoding
3. Feature selection using **Recursive Feature Elimination (RFE)**
4. Training multiple classifiers per disease
5. Hyperparameter optimization using **GridSearchCV**
6. Model evaluation using classification metrics

This systematic approach enables transparent performance comparison and reproducibility.

---
## 🧪 Reproducible Experimental Pipeline

The project follows a disease-specific, reproducible machine learning workflow:

**EDA → Preprocessing → Feature Selection → Classifier Benchmarking → Hyperparameter Tuning → Evaluation**

* **EDA:** Examined dataset distributions and feature characteristics before model development.
* **Preprocessing:** Applied disease-specific preprocessing, including scaling and data preparation where required.
* **Feature Selection:** Used **Recursive Feature Elimination (RFE)** to identify informative feature subsets.
* **Classifier Benchmarking:** Compared multiple classification algorithms for each disease prediction task.
* **Hyperparameter Tuning:** Applied **GridSearchCV** to optimize selected models.
* **Evaluation:** Compared models using classification performance metrics and selected disease-specific baseline models.

This pipeline provides a reproducible baseline for subsequent investigation of uncertainty-aware and hybrid intelligent decision-support approaches.


## 🤖 Machine Learning Models Implemented

### Diabetes Prediction

* Support Vector Classifier (SVC)
* Logistic Regression
* Random Forest Classifier

### Heart Disease Prediction

* XGBoost
* Random Forest Classifier
* Logistic Regression

### Parkinson’s Disease Prediction

* K-Nearest Neighbour (KNN)
* XGBoost
* Random Forest Classifier

### Breast Cancer Prediction

* Logistic Regression
* XGBoost
* K-Nearest Neighbour (KNN)

---

## 📈 Benchmark Evaluation Results

### Diabetes Prediction

* SVC – **69.48%**
* Logistic Regression – **70.13%**
* Random Forest – **92.32%**

### Heart Disease Prediction

* XGBoost – **100%**
* Random Forest – **100%**
* Logistic Regression – **88.31%**

### Parkinson’s Disease Prediction

* KNN – **100%**
* Random Forest – **94.87%**
* XGBoost – **92.31%**

### Breast Cancer Prediction

* Logistic Regression – **97.37%**
* XGBoost – **97.37%**
* KNN – **96.49%**

> **Note:** These results serve as baseline benchmarks for future hybrid AI model comparisons.

---

## 🚀 Deployment

The system is deployed on **Streamlit Cloud** for demonstration and accessibility:

🔗 [https://ml-multiple-diseases-predictions-shashank.streamlit.app/](https://ml-multiple-diseases-predictions-shashank.streamlit.app/)

---

## 🎯 Research Contributions

* Development of a **multi-disease ML-based clinical decision support framework**
* Comparative evaluation of classical ML models across multiple medical datasets
* Establishment of a **baseline system** for future:

  * Fuzzy logic–based diagnostic reasoning
  * Deep learning–based medical prediction
  * Hybrid intelligent healthcare systems

---

## 🤝 Contributing

Contributions related to:

* Intelligent healthcare systems
* Fuzzy inference models
* Deep learning extensions
  are welcome.

---

## 📬 Contact

**Author:** Shashank Shatraboina
📧 Email: [shashankshatraboina@gmail.com](mailto:shashankshatraboina@gmail.com)

--


