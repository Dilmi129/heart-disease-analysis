# Heart Disease Analysis & Visualization

## Project Overview

This project focuses on exploring and analysing the Heart Disease Prediction Dataset to identify patterns, relationships, and trends associated with heart disease.

The project uses Python for data cleaning, preprocessing, exploratory data analysis (EDA), and feature engineering, alongside Tableau for developing an interactive dashboard to communicate meaningful insights through data visualization.

The main objective is to transform raw healthcare data into meaningful insights that can help understand the relationship between patient characteristics, clinical measurements, and heart disease status.

## Project Objectives

- Explore and understand the structure and characteristics of the dataset.
- Clean and preprocess the data to improve its quality and consistency.
- Identify missing values, duplicate records, and potential data quality issues.
- Perform exploratory data analysis to identify patterns and relationships.
- Examine the relationship between patient characteristics and heart disease.
- Develop meaningful visualizations using Python and Tableau.
- Present findings through an interactive data visualization dashboard.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data cleaning and analysis |
| Pandas | Data manipulation and preprocessing |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Analysis environment |
| Tableau | Interactive dashboard development |
| Git & GitHub | Version control and project documentation |

## Dataset Description

Dataset: Heart Disease Prediction Dataset

The dataset contains patient health information and clinical measurements used to explore patterns associated with heart disease.

Dataset Information:
- Original records: 303
- Original variables: 14
- Final cleaned records: 302
- Target variable: Heart Disease Status (`target`)

### Key Variables

| Variable | Description |
|---|---|
| age | Age of the patient |
| sex | Gender of the patient |
| cp | Chest pain type |
| trestbps | Resting blood pressure |
| chol | Serum cholesterol level |
| fbs | Fasting blood sugar |
| restecg | Resting electrocardiographic results |
| thalach | Maximum heart rate achieved |
| exang | Exercise-induced angina |
| oldpeak | ST depression induced by exercise |
| slope | Slope of the peak exercise ST segment |
| ca | Number of major vessels |
| thal | Thalassemia |
| target | Heart disease status |

## Data Cleaning & Preprocessing

Python and Pandas were used to inspect and prepare the dataset before conducting the analysis.

The preprocessing stage included:

1. Importing and examining the dataset.
2. Checking dataset dimensions and data types.
3. Identifying missing values.
4. Identifying and removing duplicate records.
5. Examining numerical variables and potential inconsistencies.
6. Creating an additional feature called `high_bp` to identify patients with resting blood pressure equal to or above 140 mmHg.

After preprocessing, the final dataset contained **302 records**.

## Exploratory Data Analysis (EDA)

Exploratory Data Analysis was conducted to understand the distribution of variables and investigate relationships between different patient characteristics.

The analysis focused on:

- Distribution of patient ages.
- Gender-based comparisons.
- Chest pain types and heart disease status.
- Resting blood pressure and cholesterol levels.
- Maximum heart rate achieved.
- Exercise-induced angina.
- Relationships between numerical variables and heart disease.

## Key Findings

The analysis identified several interesting patterns:

1. Maximum Heart Rate and Gender

The average maximum heart rate differed slightly between genders:
- Female: 151.125
- Male: 148.585

2. Chest Pain Type

Chest pain type 2 showed a notably higher number of heart disease cases compared with other chest pain categories.

3. Age and Maximum Heart Rate

A negative relationship was observed between age and maximum heart rate, indicating that maximum heart rate generally decreased as age increased.

4. Exercise-Induced Angina

Maximum heart rate was also examined in relation to exercise-induced angina status to explore differences between patient groups.

5. Heart Disease and Clinical Indicators

The analysis explored relationships between heart disease status and clinical measurements, including maximum heart rate and ST depression (`oldpeak`).

Note: These are exploratory observations from this dataset and should not be interpreted as proof of causation or as a clinical diagnostic model.

## Tableau Dashboard

An interactive Tableau dashboard was developed to present the findings in a clear and accessible format.

The dashboard includes visualizations covering:

- Average maximum heart rate by gender.
- Average maximum heart rate by exercise-induced angina status.
- Heart disease distribution by chest pain type.
- Age and maximum heart rate relationships.
- Additional comparisons of patient characteristics and clinical measurements.

The dashboard supports interactive exploration of the dataset and helps communicate important patterns through visual storytelling.

## Project Methodology

The project followed these main stages:

1. Data Collection: Obtaining the Heart Disease Prediction Dataset.
2. Data Understanding: Examining the structure, variables, and characteristics of the dataset.
3. Data Cleaning: Identifying and addressing data quality issues.
4. Feature Engineering: Creating additional variables for further analysis.
5. Exploratory Data Analysis: Investigating distributions, patterns, and relationships.
6. Data Visualization: Developing charts and visual representations using Python.
7. Dashboard Development: Building an interactive Tableau dashboard.
8. Data Storytelling: Communicating the findings through meaningful visual insights.

## Conclusion

This project demonstrates how data cleaning, exploratory data analysis, feature engineering, and visualization can be combined to extract meaningful insights from healthcare data.

By using Python and Tableau, the project transformed raw patient information into an interactive visual data story, highlighting patterns and relationships associated with heart disease.

The project also provided practical experience in data preprocessing, analytical thinking, statistical exploration, and data storytelling.

## Author

Ishaka Dewmini

Aspiring Data Analyst

Technologies: Python | Pandas | NumPy | Matplotlib | Seaborn | Tableau | SQL
