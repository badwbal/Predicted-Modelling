# Predicted-Modelling


Aim
Predicting the salary for a job position is important task for Hire Company and take consideration essential criteria such as when given years of experience, job type, college degree, college major, industry, and miles from a metropolitan area. The aim of this project is to build a salary prediction model for existing and future job seekers by examining important features in the data.
The analysis carried out in step by step process from defining the problem, knowledge discovery data, developing model and deploying pipeline for production. The model applies data transformation and machine learning to predict salary for a job posting based on these available features.
Dataset Information

The data provided to us has been split in training and testing sets. The files included are training data (train_features_df), testing data (test_features_df) and a Target set (train_salaries_df) containing dependent salary feature.
The dataset includes available features or labelled columns for analysis as follows:
Job ID/jobId : Unique Job ID 
Company ID : Company ID for the respective advertised
Degree: Qualification
Major : Degree Specialization
Industry : Industry type such as Health, Finance etc.
Experience (Years) : Number of years of Experience 
Miles from Metropolis : Distance of the job location to nearest metropolitan city
Salary :  x1000 dollars of the respective Job

Methodology
1) Data Cleaning - Hidden information is clarified and data is analyzed to provide a more structured look. Involves dropping missing or redundant features and renaming.
2) Exploratory Data Analysis - In-depth Data Analysis, including summary statistics (descriptive and inferential) and data visualization using regression, distribution, scatter, residual and violent plots.
3) Machine Learning - Baseline Model has been built and compared for Evaluation Metrics like MSE and R^2 against other models like Linear Regression, Ridge Regression, Random Forest and Gradient Descent. Involves model tuning using parameters.
4) Cross-validation and Best Model Selection - Model with the least MSE and most R^2 was selected to be the best performing model. A summary of the evaluation scores is as follows:
Linear Regression: 385.0 ; Polynomial Regressor: 353.0 ; Ridge Regressor: 354.0 ; Random Forest: 375.0 ;
5) Feature Importance - Most important features in the Automation Pipeline are visualized.
6) Deployment - Final model has been built and saved into production using Pipeline. Can be applied to a dataset with unknown Salary values.
Summary
Gradient Boosting is best model based on average MSE on cross-validation, which improves from 384 in the baseline model to 357 on the test data. Features importance tells that miles from major cities is very relevant feature in prediction. This model can provide the most accurate results in prediction when supplied with information on Experience (Years), Miles from Metropolis, Job Type, Degree and Major.
