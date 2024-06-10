# Cardiovascular Disease Prediction
## Project Overview
This project is part of an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The primary goal is to predict whether a patient has a 10-year risk of future coronary heart disease (CHD) using various demographic, behavioral, and medical risk factors. The dataset consists of over 4,000 records and 15 attributes.
## Dataset
The dataset contains the following attributes:
- Age
- Sex
- Education
- Current Smoker
- Cigarettes Per Day
- BP Meds
- Prevalent Stroke
- Prevalent Hypertension
- Diabetes
- Total Cholesterol
- Systolic BP
- Diastolic BP
- BMI
- Heart Rate
- Glucose
## Project Structure
The project is organized into several key sections:
### 1. Problem Statement
This section provides a clear definition of the problem, outlining the objectives of the project. The goal is to predict the 10-year risk of coronary heart disease (CHD) using a variety of patient attributes.
### 2. Importing Libraries
In this section, all necessary libraries are imported. These include:
- 'pandas' and 'numpy' for data manipulation and analysis.
- 'scikit-learn' for machine learning algorithms and model evaluation.
- 'matplotlib' and 'seaborn' for data visualization.
- 'warnings' to ignore warnings for cleaner outputs.
### 3. Data Gathering
The dataset is loaded and initial data inspection is performed. This includes:
- Loading the dataset into a pandas DataFrame.
- Displaying the first few rows of the dataset.
- Checking for missing values and basic statistics of the dataset.
### 4. Exploratory Data Analysis (EDA)
Exploratory Data Analysis (EDA) is a crucial step in understanding the dataset and uncovering patterns, anomalies, and relationships between variables. In this project, EDA includes visualizations and statistical analyses to gain insights into the data.
#### - Gender Distribution
Count Plot: Shows the distribution of patients by gender. 
https://private-user-images.githubusercontent.com/166009612/335560406-6050547d-46f3-4441-b4a0-12a991a8abf4.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTgwMjEzNzksIm5iZiI6MTcxODAyMTA3OSwicGF0aCI6Ii8xNjYwMDk2MTIvMzM1NTYwNDA2LTYwNTA1NDdkLTQ2ZjMtNDQ0MS1iNGEwLTEyYTk5MWE4YWJmNC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNjEwJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDYxMFQxMjA0MzlaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1jYTNiNzY1YjYxZjg3M2I0YjlkOWM5NDk3ODk5MTg1NmE2NmZkZWFiZWU1M2M1ZGQ4ZGE4MjM1OGFmMTVlZmMwJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.bDA_gZ3K0V1UEtf4Gpu0519jDw-Qms2ZQ3k-kn_XQjY
