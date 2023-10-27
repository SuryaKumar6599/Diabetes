Data Science Capstone Project: Healthcare Prediction
Project Description
Problem Statement
The National Institute of Diabetes and Digestive and Kidney Diseases (NIDDK) conducts research to advance our understanding of chronic and costly diseases. In this project, we are working with a dataset originally sourced from NIDDK. The goal is to build a predictive model that can accurately determine whether a patient has diabetes based on specific medical measurements included in the dataset.

Dataset Description
The dataset contains several medical predictor variables and one target variable (Outcome). These predictor variables include the number of pregnancies, plasma glucose concentration, diastolic blood pressure, triceps skinfold thickness, serum insulin level, body mass index (BMI), diabetes pedigree function, and age. The target variable, Outcome, is binary, with values 0 or 1, where 1 indicates the presence of diabetes in the patient.

Project Tasks
Week 1: Data Exploration

Perform descriptive analysis to understand the variables and their values. Identify missing values, particularly in columns where zero values don't make sense (e.g., Glucose, BloodPressure, SkinThickness, Insulin, BMI).

Visualize these variables using histograms, and address missing values appropriately.

Analyze the data types in the dataset, create a count (frequency) plot to show the distribution of data types, and count the variables for each type.

Week 2: Data Exploration

Check the balance of the data by plotting the count of outcomes (diabetic and non-diabetic) and describe your findings. Plan the next steps based on your observations.

Create scatter charts between pairs of variables to understand relationships within the data, and provide insights from your observations.

Perform correlation analysis, visually represented with a heatmap, to uncover relationships between variables.

Week 3: Data Modeling

Develop strategies for model building, including selecting the right validation framework. Explain your thought process in this regard.

Apply a suitable classification algorithm to build a predictive model. Compare the results with those from a k-Nearest Neighbors (KNN) algorithm.

Week 4: Data Modeling and Reporting

Create a classification report by analyzing sensitivity, specificity, AUC (ROC curve), and other relevant metrics. Provide detailed explanations of the values obtained for these parameters.

Use Tableau to create a dashboard with appropriate chart types and metrics that are useful for business insights. The dashboard should include:

A pie chart depicting the distribution of diabetic and non-diabetic populations.
Scatter charts to analyze relationships between relevant variables.
Histograms or frequency charts to visualize data distribution.
A heatmap displaying correlation analysis among relevant variables.
Create age bins (e.g., 20-25, 25-30, 30-35, etc.) and analyze different variables for these age brackets using a bubble chart.
