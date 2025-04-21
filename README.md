# WiDS Datathon 2025: Unraveling the Mysteries of the Female Brain: Sex Patterns in ADHD

---

### **👥 Team Members**
 
 | Name | GitHub Handle | Contribution |
 | ----- | ----- | ----- |
 | Mereum Fernando | @MereumF | Built Naive Bayes, SVM, KNN models |
 | Tumi Fadare | @TumiFadare | Built Random Forest and Decision Tree models |
 | Olive Arderius | @freshPressedOlive | Built GNN model |
 | Neha Konduru | @nehark04 | Build LightGBM model |

---

## **🎯 Project Highlights**

*Developed and trained multiple machine learning models (Random Forest, Decision Tree, Naive Bayes, GNN, LightGBM) to predict an individual’s sex and ADHD diagnosis based on brain scans.

* Achieved an F1 score of 0.73645 and ranked 8th place on the Kaggle Leaderboard.


* Utilized SHAP (SHapley Additive Explanations) and LIME (Local Interpretable Model-Agnostic Explanations) for model interpretability.


* Applied feature engineering techniques such as PCA (Principal Component Analysis) and feature selection to optimize model performance.


* Implemented data preprocessing including normalization, handling missing values, and balancing classes using SMOTE (Synthetic Minority Over-sampling Technique).



🔗 [WiDS Datathon 2025 | Kaggle Competition Page](https://www.kaggle.com/competitions/widsdatathon2025/overview)

---

## **👩🏽‍💻 Setup & Execution**

**Provide step-by-step instructions so someone else can run your code and reproduce your results. Depending on your setup, include:**

* To Reproduce Our Results:
Clone the Repository:

 git clone https://github.com/[YourRepo]/WiDS-2025-ADHD.git
cd WiDS-2025-ADHD


Install Dependencies:

 pip install -r requirements.txt


Set Up the Environment:


Ensure you have Python 3.8+


Use Jupyter Notebook or VS Code for running experiments


Access the Dataset:


Download dataset from Kaggle and place it in the data/ directory.


Run the Notebooks or Scripts:

 python train_models.py

---

## **🏗️ Project Overview**

This project was a submission to the WiDS Datathon 2025. The Break Through Tech AI Program, a program sponsored by Cornell Tech, entered its participants into this Kaggle competition as part of its curriculum with the goal of improving machine learning skills and helping with the challenge itself. The objective of the challenge was to use machine learning to predict an individual’s sex and ADHD diagnosis. As girls with ADHD are more likely to go undiagnosed, an ML model that can predict both sex and ADHD based on brain scans could be extremely helpful in piecing together the factors that lead to ADHD and how they relate to an individual’s gender. Early diagnoses can make a huge difference in treatment, and being able to accurately predict ADHD could help girls get the diagnoses they need when doctors may otherwise wave their symptoms away.

---

📊 Data Exploration
Dataset Details:
Source: Kaggle competition dataset (brain scan data)


Features: Neuroimaging biomarkers, cognitive test scores, demographic information


Target Variables: Sex (Male/Female), ADHD Diagnosis (Yes/No)


Data Preprocessing:
Handled missing values with mean/mode imputation.


Applied feature scaling (StandardScaler/MinMaxScaler) for numerical variables.


Converted categorical data using one-hot encoding.


Balanced the dataset using SMOTE.


Visualizations:
Correlation heatmap to identify relationships between features.


Histogram distributions for numerical variables.


T-SNE/PCA visualizations to analyze separability in high-dimensional data.



🧠 Model Development
Models Implemented:
Random Forest & Decision Tree: Built for explainability and feature importance analysis.


Naive Bayes: A simple probabilistic model for baseline comparison.


Graph Neural Network (GNN): Used to capture relational structures in brain networks.


LightGBM: Optimized for performance with hyperparameter tuning.


Feature Selection & Tuning:
Used Recursive Feature Elimination (RFE) and SHAP values to select key predictors.


Tuned hyperparameters with GridSearchCV and Optuna.


Split data into 80% training / 20% validation.

---


📈 Results & Key Findings
Performance Metrics:
Model
F1 Score
Random Forest 0.69903
Decision Tree TBD
Naive Bayes TBD
GNN TBD
LightGBM TBD

Insights:
LightGBM outperformed other models in both accuracy and F1 score.


The GNN model provided unique insights by leveraging brain connectivity data.


Feature importance analysis revealed that specific brain regions played a critical role in ADHD prediction.


Visualizations:
Confusion Matrix


Precision-Recall Curve


SHAP Summary Plot

## **🚀 Next Steps & Future Improvements**

Enhance Data Augmentation: Apply synthetic data techniques to improve model robustness.


Ensemble Models: Combine multiple models to boost accuracy.


Fine-tune Deep Learning Approaches: Experiment with transformers for medical data.


Ethical Considerations: Conduct fairness audits to ensure unbiased predictions.

---

## **📄 References & Additional Resources**

ADHD and Neuroimaging Studies: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6981111/


SHAP for Explainability: https://shap.readthedocs.io/en/latest/


LIME for Model Interpretability: https://github.com/marcotcr/lime







This document outlines our WiDS Datathon 2025 submission and serves as a comprehensive guide for reproducing and understanding our approach to ADHD prediction through machine learning.


---
