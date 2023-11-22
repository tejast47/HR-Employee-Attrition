# HR-Employee-Attrition
Employee_Attrition
Predicting employee attrition using HR data

Business Requirement
Predict the employee attrition using the HR data.

ML Requirement
Attrition is the target variable represented as a Boolean field. Using features provided in the CSV file predict whether the employee will leave the organisation or not.

Assumptions
Since we do not have test data separately, we will use the Train-Test Split from SciKit-Learn for generating the test data (used to compute the performance metrics).
Data is fictional and can result in a very low accuracy score- we will then opt for some-other metrics for model evaluation.
There is no Time-Series data for the attrition of employees which will result in some deviation.
Contents
Correlation Heatmap - to explain the relation in various parameters
Project Report - tracking the status and lifecycle of project
Employee Attrition Predictor - IPython notebook
HR-Employee-Attrition - Data file taken from https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset
Visualization plots are added in file Visualization
Algorithms used
Logistic Regression
KNN
SVM
Naive Bages
