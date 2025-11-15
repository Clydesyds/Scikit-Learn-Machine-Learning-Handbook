# 🤖 The Ultimate Scikit-Learn Machine Learning Handbook

### 100% Runnable, Production-Ready Machine Learning Notebooks — No External Data Needed

---

## 🎯 Project Mission

This project is a **comprehensive, beginner-to-senior level Machine Learning guide** built entirely using **scikit-learn (sklearn)** — the most popular ML library in Python.

Every algorithm is implemented using **in-built sklearn datasets**, so you can run every notebook instantly — no external data downloads, no setup issues, just clean and working ML code.

Our goal:  
To take you from **basic ML concepts** to **production-ready engineering workflows** that reflect the real work of a **Senior Machine Learning Engineer**.

---

## ✅ Why This Project Exists

### 🚫 No More Data Setup Problems  
Every example runs instantly with sklearn’s built-in datasets like `load_iris`, `load_diabetes`, and `fetch_california_housing`.

### 🧩 Go Beyond `.fit()` and `.predict()`  
Each notebook explores **hyperparameters**, **regularization**, **bias-variance tradeoff**, and **model interpretability** — not just model training.

### 🔗 Learn Production-Ready Pipelines  
Every workflow includes `Pipeline` and `ColumnTransformer` to show how real-world ML systems prevent data leakage and ensure reproducibility.

---

## 👨‍💻 Who Should Use This Repository?

| **Audience Level** | **Learning Focus** | **Key Takeaway** |
|----------------------|--------------------|------------------|
| **Beginner / Intermediate** | Understanding ML basics, model training, evaluation metrics. | Focus on Sections 1 & 2 |
| **Advanced Learner** | Cross-validation, scaling, hyperparameter tuning, and ensemble methods. | Focus on Sections 3 & 4 |
| **Senior ML Engineer** | Model interpretability (SHAP/LIME), feature importance, and full ML pipelines. | Focus on Section 5 |

---

## 📘 Repository Overview

This repository contains **24 Jupyter Notebooks**, grouped into **6 learning modules**.  
Each notebook includes theory, implementation, evaluation, and interpretation.

---

### 📌 Module 01 — Regression Algorithms
| Notebook | Topic |
|---------|-------|
| 🔗 [`01_Linear_Regression.ipynb`](Module_01_Regression/01_Linear_Regression.ipynb) | Simple & Multiple Linear Regression |
| 🔗 [`02_Ridge_Lasso_ElasticNet.ipynb`](Module_01_Regression/02_Ridge_Lasso_ElasticNet.ipynb) | Regularization Techniques |
| 🔗 [`03_SVR_Support_Vector_Regression.ipynb`](Module_01_Regression/03_SVR_Support_Vector_Regression.ipynb) | Kernel SVR |
| 🔗 [`04_KNN_Regression.ipynb`](Module_01_Regression/04_KNN_Regression.ipynb) | K-Nearest Neighbor Regression |

---

### 📌 Module 02 — Classification Algorithms
| Notebook | Topic |
|---------|-------|
| 🔗 [`05_Logistic_Regression.ipynb`](Module_02_Classification/05_Logistic_Regression.ipynb) | Binary & Multi-class Classification |
| 🔗 [`06_Decision_Tree_Classifier.ipynb`](Module_02_Classification/06_Decision_Tree_Classifier.ipynb) | Tree Splits & Pruning |
| 🔗 [`07_KNN_Classifier.ipynb`](Module_02_Classification/07_KNN_Classifier.ipynb) | Distance-based Classification |
| 🔗 [`08_SVM_Classifier.ipynb`](Module_02_Classification/08_SVM_Classifier.ipynb) | Margin Optimization |
| 🔗 [`09_Naive_Bayes.ipynb`](Module_02_Classification/09_Naive_Bayes.ipynb) | Probabilistic Classifiers |

---

### 📌 Module 03 — Ensemble Techniques
| Notebook | Topic |
|---------|-------|
| 🔗 [`10_Random_Forest.ipynb`](Module_03_Ensemble/10_Random_Forest.ipynb) | Bagging & OOB Scoring |
| 🔗 [`11_AdaBoost.ipynb`](Module_03_Ensemble/11_AdaBoost.ipynb) | Adaptive Boosting |
| 🔗 [`12_Gradient_Boosting.ipynb`](Module_03_Ensemble/12_Gradient_Boosting.ipynb) | Residual Learning |
| 🔗 [`13_XGBoost_LightGBM.ipynb`](Module_03_Ensemble/13_XGBoost_LightGBM.ipynb) | Fast Gradient Boosting |
| 🔗 [`14_Stacking_Voting_Classifier.ipynb`](Module_03_Ensemble/14_Stacking_Voting_Classifier.ipynb) | Hybrid Model Stacking |

---

### 📌 Module 04 — Clustering (Unsupervised ML)
| Notebook | Topic |
|---------|-------|
| 🔗 [`15_KMeans_Clustering.ipynb`](Module_04_Clustering/15_KMeans_Clustering.ipynb) | Cluster Partitioning |
| 🔗 [`16_Hierarchical_Clustering.ipynb`](Module_04_Clustering/16_Hierarchical_Clustering.ipynb) | Dendrograms |
| 🔗 [`17_DBSCAN.ipynb`](Module_04_Clustering/17_DBSCAN.ipynb) | Density-Based Clustering |
| 🔗 [`18_Gaussian_Mixture_Models.ipynb`](Module_04_Clustering/18_Gaussian_Mixture_Models.ipynb) | Soft Clustering |

---

### 📌 Module 05 — Dimensionality Reduction
| Notebook | Topic |
|---------|-------|
| 🔗 [`19_PCA.ipynb`](Module_05_Dimensionality_Reduction/19_PCA.ipynb) | Principal Component Analysis |
| 🔗 [`20_ICA.ipynb`](Module_05_Dimensionality_Reduction/20_ICA.ipynb) | Independent Component Analysis |
| 🔗 [`21_tSNE_and_UMAP.ipynb`](Module_05_Dimensionality_Reduction/21_tSNE_and_UMAP.ipynb) | Non-linear Visualization |

---

### 📌 Module 06 — Machine Learning Engineering
| Notebook | Topic |
|---------|-------|
| 🔗 [`22_Feature_Engineering_and_Preprocessing.ipynb`](Module_06_Engineering_Best_Practices/22_Feature_Engineering_and_Preprocessing.ipynb) | Encoding, Scaling & Transformers |
| 🔗 [`23_Pipelines_and_ColumnTransformer.ipynb`](Module_06_Engineering_Best_Practices/23_Pipelines_and_ColumnTransformer.ipynb) | Data Leakage Prevention |
| 🔗 [`24_Model_Selection_and_Tuning.ipynb`](Module_06_Engineering_Best_Practices/24_Model_Selection_and_Tuning.ipynb) | Grid Search + CV |

---

## 🔬 Notebook Format (Consistent Across All Notebooks)

Each notebook follows a **standardized 5-section structure**:

| **Section** | **Focus** | **Skill Level** |
|--------------|------------|----------------|
| **1. Theoretical Foundation** | Intuition, math formula, cost function, optimization concept. | Beginner |
| **2. Setup & Dataset** | Import libraries, load sklearn datasets, and train-test split. | All |
| **3. Preprocessing & Modeling** | Feature scaling, encoding, and model training. | Intermediate |
| **4. Evaluation & Metrics** | Metrics like MSE, R², ROC-AUC, F1, confusion matrix, ROC curve. | Advanced |
| **5. Interpretation & Next Steps** | SHAP/LIME analysis, regularization, bias-variance, feature importance. | Senior |

---

## 🚀 Getting Started

### Step 1: Clone the Repository
```bash
git clone https://github.com/rohanmistry231/Scikit-Learn-Machine-Learning-Handbook.git
cd Scikit-Learn-Machine-Learning-Handbook
```

### Step 2: Launch Jupyter Notebook

```bash
jupyter notebook
```

Then open any notebook (e.g., [`Module_01_Regression/01_Linear_Regression.ipynb`](Module_01_Regression/01_Linear_Regression.ipynb)).

---

## 🤝 Contributing

We welcome contributions from the ML community!
If you’d like to add new algorithms, improve explanations, or enhance interpretability sections:

* Follow the **5-section notebook structure**
* Use **only scikit-learn datasets**
* Write **clear, documented, and reproducible code**

---

## 🌟 Vision

> “To build the most practical, instantly runnable, and production-focused
> Machine Learning resource for Python and scikit-learn.”

---

**Author:** Rohan Mistry
**License:** MIT
**Framework:** Scikit-learn, Python 3.9+