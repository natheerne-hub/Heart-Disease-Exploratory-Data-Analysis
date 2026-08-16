<p align="center"><img src="assets/heart-disease-banner.svg" alt="Heart Disease Analytics — Dr. Natheer Soliman" width="100%"></p>

# 🫀 Heart Disease — Exploratory Data Analysis & Risk Modeling

### CardioRisk-AI | Healthcare Data Analysis with Python

A healthcare data science project exploring clinical characteristics associated with heart disease and preparing patient data for predictive modeling.

## 🎯 Project Objective

Move from structured clinical data to clear, reproducible healthcare insights by combining exploratory analysis, preprocessing, visualization, clinical interpretation, and predictive-modeling concepts.

## 🔎 Analysis Pipeline

1. **Data exploration** — inspect structure, variables, distributions, and data quality.
2. **Data preprocessing** — prepare clinical variables for analysis and modeling.
3. **Exploratory data analysis** — investigate relationships between patient characteristics and heart disease.
4. **Clinical interpretation** — translate statistical patterns into understandable healthcare insights.
5. **Predictive modeling** — compare baseline classification approaches for cardiovascular risk prediction.
6. **Model evaluation** — assess classification performance with accuracy, precision, recall, F1, ROC-AUC, confusion matrices, and stratified cross-validation.

## 📈 Visual Analysis

The notebook generates portfolio-ready analytical visuals directly from the project data, including:

- Heart-disease outcome distribution
- Age, resting blood pressure, cholesterol, maximum heart rate, and Oldpeak distributions by outcome
- Correlation matrix and target correlations
- Confusion matrices for Logistic Regression and Random Forest
- Hold-out ROC curves

> The visual results are generated from the reproducible notebook rather than manually invented or copied figures. Selected exported charts will be added here as repository assets after notebook execution.

## 📊 Dataset Features

The processed dataset includes variables such as:

- Age
- Resting blood pressure
- Cholesterol
- Fasting blood sugar
- Maximum heart rate
- ST depression (`Oldpeak`)
- Chest pain type
- Resting ECG
- Exercise-induced angina
- ST slope
- Heart disease outcome

## 🧰 Tech Stack

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Scikit-learn` · `Jupyter / Google Colab`

## 📁 Repository Contents

- [`heart_disease_analysis.ipynb`](./heart_disease_analysis.ipynb) — reproducible EDA and baseline modeling notebook
- [`heart_processed.csv`](./heart_processed.csv) — processed clinical dataset
- [`assets/`](./assets) — visual assets for the project presentation

## 🩺 Clinical Perspective

The project emphasizes interpretation of risk-associated patterns rather than treating model output as a diagnosis. Any predictive model derived from this dataset requires external validation, calibration assessment, and clinical oversight before real-world use.

## ⚠️ Important Note

This project is for **educational and portfolio purposes**. Results should not be interpreted as individual medical advice or used as a substitute for professional clinical judgment.

## 👨‍⚕️ Author

**Dr. Natheer Soliman, MD**  
Healthcare Data Analyst | Clinical Data & AI
