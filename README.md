# YogeshProjectsASU

# Project - 1 - Demand Prediction using Time Series Analysis

## Project Overview
This project focuses on predicting the demand for a manufacturing industry using time series analysis. Our team, consisting of three members, employed various machine learning algorithms including ARIMA, SARIMA, LSTM, and FbProphet to develop predictive models.

## Description
The goal of this project was to analyze historical data to predict future demand in the manufacturing industry. We compared several models to identify which algorithm provides the most accurate forecast. The project involved data cleaning, exploratory data analysis, model building, and evaluation.

## Results

The performance of each time series model was evaluated based on the mean absolute error (MAE). Below are the results showing how each model performed in predicting the demand:

- **LSTM (Long Short-Term Memory):**
  - **MAE:** 0.1368
  - **Interpretation:** The LSTM model provided the most accurate predictions with the lowest error rate among the tested models.

- **Fb Prophet:**
  - **MAE:** 0.675
  - **Interpretation:** While more user-friendly and easier to implement, FbProphet showed moderate accuracy in this scenario.

- **ARIMA (AutoRegressive Integrated Moving Average) & SARIMA (Seasonal ARIMA):**
  - **MAE:** 0.793
  - **Interpretation:** ARIMA and SARIMA models, while traditional choices for time series forecasting, resulted in the highest error rates in this study.

Based on the mean absolute errors observed, the LSTM model outperformed the other techniques, making it the most suitable choice for future demand forecasting in this manufacturing industry context.


# Project - 2 - Absenteeism in the Workplace: A Database Management Approach

## Project Overview
This project aims to address employee absenteeism by examining past data to classify fundamental causes and predict future occurrences using machine learning. Our team analyzed various factors affecting absenteeism and developed a database to manage and visualize these factors effectively.

## Description
Employee absenteeism decreases productivity and disrupts operational effectiveness. By understanding the varied reasons behind absences, this project seeks to identify patterns and trends to manage absenteeism better. The ultimate goal is to enhance workforce management through strategic insights provided by a predictive model.

## ER/EER Design
The project includes an Entity-Relationship (ER) model that defines the following:
- Entities with their keys and attributes such as Employee, Absenteeism at Work, Education, Days of the Week, and Reason for Absence.
- Relationships such as Employee-Absenteeism (1:N), Employee-Education (1:N), and others.

## Use Cases

### Absenteeism Pattern Analysis
- **Objective:** Identify patterns and trends in absenteeism across different times of the year, days of the week, or among various reasons.
- **Details:** This analysis helps understand how absenteeism fluctuates over time and conditions, aiding in proactive management and planning.

### Employee Well-being Programs
- **Objective:** Examine the reasons for absence and related factors to tailor employee well-being and support programs.
- **Details:** By understanding specific causes and their impacts, targeted interventions can be developed to enhance employee health and reduce absenteeism.

### Impact of Education, Reason, and Workload on Absence Time
- **Objective:** Explore how an employee's educational background, reason for absenteeism, and average workload influence the duration of absences.
- **Details:** This use case assesses the correlation between education level, reasons for absences, and workload to better manage and possibly predict future absences based on these factors.


## Results & Findings

Through our analysis, we identified three distinct clusters of employees characterized by specific attributes and patterns of absenteeism:

### Cluster 0
- **Characteristics:** Young employees with less service time, high transportation expenses, and larger families.
- **Absenteeism Patterns:** Low absenteeism, mainly for routine and preventive care.

### Cluster 1
- **Characteristics:** Older employees with longer service time, moderate transportation expenses, and higher weights/BMI.
- **Absenteeism Patterns:** Intermediate level of absenteeism, many unrecorded reasons, routine care prevalent.

### Cluster 2
- **Characteristics:** Older employees with the highest BMI, low transportation expenses, likely living close to work.
- **Absenteeism Patterns:** Highest rate of absenteeism, not linked to personal life events, likely health-related.

These findings provide strategic insights into the diverse needs and circumstances of our workforce, enabling tailored strategies to mitigate absenteeism impacts effectively.





