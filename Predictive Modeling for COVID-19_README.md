*Predictive Modeling for COVID-19 Patient Outcomes*

*Simple Overview*

This project focuses on using machine learning models to predict COVID-19 patient outcomes based on clinical and demographic data. It aims to assist healthcare professionals in early identification of high-risk patients and optimize resource allocation to reduce mortality rates and healthcare system burdens.

*Overview*

The COVID-19 pandemic has presented unprecedented challenges for global healthcare systems. This project addresses the need for accurate predictive tools by analyzing anonymized patient data to forecast severe outcomes such as hospitalization and mortality. The dataset comprises over one million records with features like demographics, pre-existing conditions, and clinical indicators. Multiple machine learning models, including Random Forest and XGBoost, were developed to predict patient outcomes, achieving high accuracy and robust classification performance. This project provides actionable insights for clinicians and policymakers to enhance patient care and public health strategies.

*Data Description*

*Dataset*
Size: Over 1 million unique patient records with 21 features.
Key Variables:
Demographics: Gender, age, and patient type.
Clinical Indicators: Presence of pre-existing conditions (e.g., diabetes, hypertension).
Outcomes: Mortality, ICU admission, and recovery status.

*Preprocessing Steps*
Replaced special codes (97, 99) with missing data placeholders (NaN).
Created new features, such as age groups and categorized conditions.
Addressed data imbalance with SMOTE and undersampling.
Normalized numerical variables and encoded categorical variables (e.g., one-hot encoding).

*Exploratory Data Analysis*
Visualized demographic distributions (e.g., age, gender).
Analyzed relationships between pre-existing conditions and outcomes.
Generated a correlation matrix to identify key predictors of severe outcomes.

*Modeling*
Evaluated models: Logistic Regression, Random Forest, XGBoost, SVM, and others.
Best Model: Random Forest with 91.5% accuracy and an AUC of 0.95.
Performance metrics: Accuracy, precision, recall, F1 score, and ROC curves.

*Use Cases*
Healthcare Resource Allocation: Predict patient load and prioritize resources like ventilators and ICU beds.
Targeted Interventions: Early identification of high-risk groups for personalized treatment.
Policy Making: Support public health strategies by identifying vulnerable populations.