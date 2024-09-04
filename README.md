# Regression Analysis Project

- In this project I'm using Python's Statsmodels library to predict systolic blood pressure (SBP) based on various health indicators such as age, cholesterol levels, weight, and smoking habits.

- The analysis tries to identify the biggest factors affecting SBP and develop predictive models using both linear and logistic regression.

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
