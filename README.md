🫀 Risk Prediction Model for Major Adverse Cardiac Events (MACE)
📌 Synopsis

Not all patients with visible coronary plaques go on to develop major cardiac events. The risk of a Major Adverse Cardiac Event (MACE) depends on a combination of plaque morphology, vessel narrowing (stenosis), and patient-specific clinical factors (age, cholesterol levels, blood pressure, smoking history, etc.).

This project aims to develop a predictive model that integrates imaging-derived features and clinical data to stratify patient risk (Low, Moderate, High) for MACE. Accurate prediction can help in personalized treatment planning and preventive cardiology.

Key Objectives:

Extract plaque features (type, volume, stenosis).

Combine with clinical risk factors (age, BP, cholesterol, diabetes, etc.).

Train interpretable ML models (Logistic Regression, Random Forest, XGBoost).

Evaluate models using AUC-ROC and explain predictions using SHAP/LIME.

Deploy an interactive dashboard (Streamlit/Dash) for clinicians.

📂 Datasets
1. Primary Research Dataset

MESA (Multi-Ethnic Study of Atherosclerosis)

Source: BioLINCC – MESA

Multimodal: Clinical + Imaging (CT, MRI, plaque burden, calcium scoring, stenosis).

Outcome: Long-term MACE events.

Status: Restricted access (application in progress).

2. Baseline Clinical Datasets (for initial experiments)

Cleveland Heart Disease Dataset

Source: UCI / Kaggle

303 patients, 14 clinical features (age, cholesterol, BP, ECG, chest pain, etc.).

Outcome: Presence/absence of heart disease.

Heart Failure Clinical Records

Source: Kaggle

299 patients, 12 features (age, anaemia, diabetes, ejection fraction, etc.).

Outcome: Death event (yes/no).

Cardiovascular Disease Dataset (70k records)

Source: Kaggle

70,000 patients, 11 features (age, BP, cholesterol, glucose, smoking, etc.).

Outcome: Cardiovascular disease (yes/no).

🚀 Workflow Overview

Data Collection & Cleaning (clinical + imaging).

Feature Engineering (plaque scores, stenosis %, risk factors).

Model Training (XGBoost, Logistic Regression, Random Forest).

Evaluation (AUC-ROC, Confusion Matrix).

Explainable AI (SHAP, LIME).

Dashboard Deployment (Streamlit/Dash).

🎯 Expected Outcomes

A hybrid ML pipeline for MACE risk prediction.

Accurate patient stratification into Low / Moderate / High risk groups.

Explainable predictions for clinician trust.

Streamlit dashboard for visual analytics and decision support.
