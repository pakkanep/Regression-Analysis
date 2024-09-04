# Regression Analysis Project

- In this project I'm using Python's Statsmodels library to predict systolic blood pressure (SBP) using Linear regression.

- Im also predicting the propability of high blood pressure and if patients are showing symptoms of coronary heart disease. For these two I'm using logistic regression.

- The analysis tries to identify the biggest factors affecting SBP and develop predictive models using both linear and logistic regression.

## Notebook Sections

- **Data Loading and Preprocessing**: Loads the dataset, rescaling the data (centering and normalizing), and prepares it for analysis.
- **Exploratory Data Analysis (EDA)**: Creates visualizations to explore data patterns and relationships between the dependent and independent variables.
- **Linear Regression**: Builds models to predict systolic blood pressure (SBP) and interprets the results.
- **Logistic Regression**: Builds models to estimate the risk of high blood pressure or showing symptoms of Coronary heart disease.
- **Model Evaluation**: Measures model performance using different metrics to see how well they predict outcomes.
- **Conclusions**: Summarizes the main findings and what the models reveal about the data.



## Data

The dataset (`fram.txt`) I use contains the following columns:

| Column Name | Description                                     |
|-------------|-------------------------------------------------|
| `ID`        | Id for each participant                         |
| `SEX`       | Gender                                          |
| `AGE`       | Age of the participant at the start of the study|
| `FRW`       | Weight in relation to the group's median        |
| `SBP`       | Systolic Blood Pressure                         |
| `DBP`       | Diastolic Blood Pressure                        |
| `CHOL`      | Cholesterol level                               |
| `CIG`       | Smoking (number of cigarettes per day)          |
| `CHD`       | Coronary heart disease status 0-10 severity (?) |
| `YRS_CHD`   | Years to onset of coronary heart disease        |
| `DEATH`     | Death status (binary)                           |
| `YRS_DTH`   | Years to death                                  |
| `CAUSE`     | Cause of death                                  |
