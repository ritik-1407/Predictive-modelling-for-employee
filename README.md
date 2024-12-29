
Project Title: Employee Performance Prediction Model

Description:
This project aims to develop and evaluate a machine learning model that predicts employee performance based on data from two talent assessments: a new assessment (3 sections) and an old assessment (4 sections). The model will be trained and validated using historical candidate and employee performance data.

Key Objectives:

Build a predictive model for employee performance.
Determine the relative effectiveness of the new and old assessments in predicting employee success.
Datasets:

Candidate Data (candidate_data.csv):

Candidate ID (unique identifier for each candidate)
Associate ID (unique identifier for the hired employee, if applicable)
Assessment Date (date the candidate completed the assessments)
Old Assessment Scores (scores for each of the 4 sections)
New Assessment Scores (scores for each of the 3 sections)
Time Taken for Old Assessment (time spent completing the old assessment)
Time Taken for New Assessment (time spent completing the new assessment)
[Optional] Additional candidate data points (e.g., demographics, experience)
Employee Data (employee_data.csv):

Associate ID (unique identifier for the hired employee)
Hire Date (date the employee was hired)
Termination Date (date of termination, if applicable)
Employee Performance Ratings (performance ratings over time - specific format and scale to be clarified)



Exploration and Preprocessing:

Explore the data, handle missing values, and perform necessary preprocessing.
Model Development:

Develop and train the XGBoost model.
Develop and train the Linear Regression model.
Evaluation:

Evaluate the performance of both XGBoost and Linear Regression models on unseen data. Analyze performance metrics, identify potential biases, and document results.

