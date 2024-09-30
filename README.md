# Heart Disease Risk Factor Analysis Using SQL

## Objective
The primary objective of this project is to analyze heart disease risk factors using SQL queries on the Heart Disease Cleveland dataset. By exploring various patient demographics and health metrics, this analysis aims to identify key indicators associated with heart disease, providing insights that can assist healthcare professionals in making informed decisions.

## Dataset Description
- **Source:** [Heart Disease Cleveland Dataset](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci)
- **Features:**
  - **Demographics:** Age, Sex
  - **Health Metrics:** Cholesterol, Resting Blood Pressure, Max Heart Rate, ST Depression, Chest Pain Type, etc.
- **Outcome:** Heart Disease Condition (0 = No, 1 = Yes)

## Methodology Overview

### Data Exploration
- Conducted exploratory data analysis to understand the structure of the dataset and the distribution of various health metrics.

### SQL Queries
- Implemented multiple SQL queries to analyze:
  - Patient distribution with and without heart disease.
  - Key health metrics averaged by heart disease condition.
  - The impact of chest pain type on heart disease prevalence.
  - Risk factor rankings to identify high-risk patients.

## Results
The analysis produced the following key insights:
1. Distribution of patients with and without heart disease.
2. Average health metrics for patients segmented by heart disease status.
3. Breakdown of chest pain types in relation to heart disease.
4. Ranking of patients based on their health metrics.

## Business Impact
The insights generated from this analysis can provide valuable information for healthcare providers to:
- Identify high-risk patients and target them for preventive care.
- Allocate resources effectively based on patient risk profiles.
- Enhance patient outcomes through informed clinical decisions.

## Future Work Recommendations
- Incorporate additional features such as comorbidities to improve the predictive power of the analysis.
- Perform scenario analysis to evaluate resource allocation during high-demand situations (e.g., flu season).
- Integrate real-time data from Electronic Health Records (EHR) for dynamic risk assessments.

## Ethical Considerations
- Ensure compliance with healthcare regulations to protect patient data.
- Address potential biases in predictions to ensure equitable treatment for all patients.
