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

![2024-06-10 (1)](https://github.com/RutujaPatil26/Machine_Learning_Project/assets/172021951/9540de3e-9d57-4bdf-8f96-dd495515ba09)

There are more than 1,750 female patients and approximately 1,500 male patients.
#### - CHD Risk Distribution
Count Plot: Displays the distribution of patients with and without CHD risk.

![Screenshot (32)](https://github.com/RutujaPatil26/Machine_Learning_Project/assets/172021951/cd99092a-c6e6-4962-8f6b-a3a602b53285)

Approximately 2,800 patients have no risk of CHD, while around 500 patients are at risk.
#### - CHD Risk by Gender
Count Plot: Shows the distribution of CHD risk among males and females.

![Screenshot (33)](https://github.com/RutujaPatil26/Machine_Learning_Project/assets/172021951/a6b42967-e5b2-4b40-b006-ae03282106f7)
