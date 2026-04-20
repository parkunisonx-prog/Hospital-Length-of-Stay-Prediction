## Summary

This project focuses on analyzing **hospital Length of Stay (LOS) data** to identify factors associated with extended patient stays and develop a predictive model for hospital admissions.

In this project, we will:

- Analyze hospital patient admission and diagnosis data
- Create a target variable to classify **extended length of stay (LOS ≥ 7 days)**
- Clean and preprocess the dataset by handling missing values, correcting data types, and removing unnecessary variables
- Use Python to explore relationships between patient characteristics and LOS
- Build and evaluate machine learning models to predict extended hospital stays
- Create data visualizations to highlight important trends and predictors

## Objectives

The objectives are to:

- Import and clean hospital LOS data using **Python and pandas**
- Perform **data preprocessing and feature engineering**
- Transform the LOS variable into a binary classification target
- Conduct **exploratory data analysis (EDA)** using visualizations
- Develop predictive models using **machine learning techniques**
- Evaluate model performance using relevant classification metrics
- Interpret results and prepare a write-up describing the key drivers of extended hospital stays and the model’s effectiveness

  ## Data

The dataset used in this project is the **Microsoft Hospital Length of Stay dataset**, sourced from Microsoft’s public GitHub repository. It contains **100,000 hospital admission records** with **27 clinical and demographic features**.

Each row in the dataset represents a single patient hospital encounter and includes information related to demographics, comorbidities, laboratory values, vital signs, prior readmissions, and facility identifiers.

### Key Variables

**Demographics**
- Body Mass Index (**BMI**)

**Clinical Conditions / Comorbidities**
- Asthma
- Dialysis renal end stage
- Iron deficiency
- Pneumonia
- Substance dependency
- Depression
- Major psychological disorder
- Blood disorder
- Malnutrition
- Fibrosis

**Laboratory Values**
- Hematocrit
- Neutrophils
- Sodium
- Glucose
- Blood urea nitrogen
- Creatinine

**Vitals**
- Pulse
- Respiration

**Administrative Variables**
- Number of readmissions within the last 180 days
- Facility ID

### Target Variable

The primary outcome variable is **extended hospital length of stay (LOS)**.

LOS was transformed into a binary classification target:

- **0 = Non-extended stay (< 7 days)**
- **1 = Extended stay (≥ 7 days)**

This transformation allowed the problem to be approached as a **machine learning classification task**.

### Dataset Notes

- Total observations: **100,000**
- Total features: **27**
- Missing values: **None**
- Train-test split: **80/20**
