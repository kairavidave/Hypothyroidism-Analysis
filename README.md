# Hypothyroidism-Analysis
![TSH1](https://github.com/user-attachments/assets/afead813-50bb-4b6a-b609-535a06620a41)

## Overview
This project involves analyzing hypothyroidism cases using data-driven techniques. The study aims to identify patterns and key factors influencing hypothyroidism and provide insights for better understanding the condition.

## Objectives
Hypothyroidism is a condition where the thyroid gland underperforms, leading to hormonal imbalances. It is particularly common among females and can cause symptoms such as:

- Fatigue
- Weight gain
- Hair thinning
- Depression
- Sensitivity to cold
  
## Motivation:
Being a 23-year-old female with hypothyroidism that was diagnosed late, I was motivated to study and analyze patterns associated with this condition. This project stems from a personal curiosity to understand the demographic and clinical factors that might contribute to better diagnosis and management.

The key goals are:

- Perform exploratory data analysis (EDA) to understand the dataset’s distribution and insights.
- Identify the most affected demographics (age, gender) for hypothyroidism.
  
## Dataset
- Source: Kaggle - Thyroid Disease Detection
- Classes: Hypothyroid and Non-Hypothyroid
- Features: Age, gender, medical history, thyroid test results

## Tools Used
- Python: Data cleaning, manipulation, and visualizations
- SQL: Querying and aggregating data for insights

## Data Cleaning & Preparation
- Missing Values: Handled using imputation techniques
- Data Verification: Ensured consistency for categorical and numerical features
### Feature Engineering
- Created meaningful categories for age groups
- Binarized specific features like pregnancy status and medical conditions

## Exploratory Data Analysis (EDA)
### 1. Distribution of Hypothyroid Cases
![Hypovsnon](https://github.com/user-attachments/assets/01c77446-ec20-4347-bdb5-5d936a347432)

### 2. Gender-Wise Distribution
![Genderwise](https://github.com/user-attachments/assets/9b3c37e7-39db-43a3-9dd4-06646da07eee)

### 3. Age Group Analysis
The highest number of cases were observed in the 61-80 years age group.
![Agewise](https://github.com/user-attachments/assets/3b8371de-a30c-4654-bff4-0764120ea722)

### 4. Top 10 Feature Importances
TSH (Thyroid Stimulating Hormone) is the most significant predictor of hypothyroidism.
![Top10](https://github.com/user-attachments/assets/658d7b0a-8fd0-423b-93e8-e551452e96de)

### 5. Lab Results Analysis
#### TSH Distribution by Diagnosis: 
![tt](https://github.com/user-attachments/assets/4ad57a9d-188d-4782-a6b5-922eb94230e5)

#### TT4 Distribution by Diagnosis:
![tt4](https://github.com/user-attachments/assets/140d820b-9ac4-4d70-8432-8505939be93a)


## Implications
- Early Screening: For high-risk groups like females and older adults.
- Targeted Interventions: Lifestyle modifications and regular screenings can help mitigate risks.
- Improved Diagnosis: Leveraging key lab results (TSH, TT4) can aid early detection.

## Conclusion
This study highlights the importance of demographic factors and lab results in understanding hypothyroidism. By focusing on high-risk groups and significant features, we can improve outcomes and management for individuals suffering from hypothyroidism.

Early screening for high-risk groups can improve outcomes.

Targeted interventions and lifestyle modifications can help mitigate risks.
