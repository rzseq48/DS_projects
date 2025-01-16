Student Performance Analysis
Project Overview
This project analyzes the factors influencing student performance using various machine learning models. The analysis involves cleaning and preprocessing the dataset, applying feature engineering techniques, and evaluating models such as Linear Regression and Random Forest. The goal is to predict students' final scores and derive actionable insights to improve academic outcomes.

Table of Contents
Project Description
Technologies Used
Dataset Description
Analysis and Results
Installation Instructions
Usage
Future Work
Contributors
Project Description
This project evaluates student performance based on several factors such as attendance, hours studied, parental education, and participation in extracurricular activities.
The project implements machine learning models to predict final scores and assesses their performance using metrics like RMSE, R², and MAE.
Technologies Used
Python 3.8+
Jupyter Notebook
Libraries:
pandas for data manipulation
matplotlib and seaborn for data visualization
scikit-learn for machine learning and evaluation
numpy for numerical operations
Dataset Description
The dataset includes the following columns:

Attendance_Rate: Percentage of classes attended.
Hours_Studied: Weekly study hours.
Participates_Activities: Participation in extracurricular activities (1: Yes, 0: No).
Has_Internet: Availability of internet at home (1: Yes, 0: No).
Parent_Education: Education level of parents (ordinal scale).
Final_Score: Final academic performance score (target variable).
Analysis and Results
Linear Regression:
RMSE: 7.85
R²: 0.78
MAE: 6.38
Random Forest:
RMSE: 8.45
R²: 0.75
MAE: 6.71
Insights
Feature engineering improved model performance compared to the initial dataset.
Hours studied and attendance have a marginal positive correlation with final scores.
Participation in extracurricular activities showed limited impact on the predictions.


Installation Instructions

Clone this repository:

git clone https://github.com/rzseq48/DS_projects.git

cd StudentPerformanceAnalysis

Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install required dependencies:


pip install -r requirements.txt

Future Work
Explore additional features such as teacher evaluations and peer interactions.
Test other machine learning models like Gradient Boosting or Neural Networks.
Incorporate hyperparameter tuning for Random Forest to enhance its performance.
Validate the model on a larger and more diverse dataset.

