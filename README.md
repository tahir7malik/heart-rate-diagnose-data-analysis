# Heart-Rate-Diagnose-Data-Analysis
This repository contains code and resources for conducting analysis on health & medical dataset. The purpose of this project is to explore, analyse, and derive insights from medical data where patients are dealing with heart related problems. The analysis encompasses various aspects &amp; factors influencing various orders.

## Project Overview

**I completed this analysis as part of my 1 month internship at Unified Mentor. I was asked to analyze the health and medical data &amp; come up with meaningful insights.**

[Tableau Dashboard](https://public.tableau.com/app/profile/tahir.malik/viz/heart-rate-diagnose-data-analysis/Dashboard)
![Dashboard](https://github.com/tahir7malik/heart-rate-diagnose-data-analysis/blob/main/plots/heart-rate-diagnose-data-analysis-dashboard.png)

###  Data Sources

Patient': The primary dataset used for this analysis is in "heart-disease-dataset.csv" file, containing detailed information about several patient medical information.

  - This spreadsheet contains 14 columns:
    - age: This column represents the age of the patient <br/>
    - sex: This column represents the sex of the patient. It's typically encoded as 0 for female and 1 for male <br/>
    - cp: This column represents the chest pain type experienced by the patient. It's categorical with 4 different values indicating different types of chest pain <br/>
    - trestbp: This column represents the resting blood pressure of the patient measured in mm Hg (millimeters of mercury) <br/>
    - chol: This column represents the serum cholesterol level of the patient measured in mg/dl (milligrams per deciliter) <br/>
    - fbs: This column represents whether the patient's fasting blood sugar is greater than 120 mg/dl. It's a binary variable encoded as 0 for false and 1 for true <br/>
    - restecg: This column represents the resting electrocardiographic results of the patient. It's categorical with values 0, 1, and 2 representing different results <br/>
    - thalach: This column represents the maximum heart rate achieved by the patient during exercise <br/>
    - exang: This column represents whether exercise induced angina is present. It's a binary variable encoded as 0 for false and 1 for true <br/>
    - oldpeak: This column represents the ST depression induced by exercise relative to rest <br/>
    - slope: This column represents the slope of the peak exercise ST segment. It's categorical with several possible values indicating different types of slope <br/>
    - ca: This column represents the number of major vessels (0-3) colored by fluoroscopy <br/>
    - thal: This column represents a diagnostic technique called thallium scintigraphy, with values 0, 1, and 2 indicating different conditions: normal, fixed defect, and reversible defect <br/>
    - target: This column represents the presence of heart disease. It's a binary variable encoded as 0 for no heart disease and 1 for presence of heart disease <br/>

### Tools

- Python: Data Processing, Data Cleaning, Data Analysis
- Pandas: Data Cleaning, Data Analysis
- Microsoft Excel: Data Cleaning, Data Analysis
- Tableau: Data Visualization

## Approach for Data Analysis
1. **Ask**: ask questions & define problem
2. **Prepare**: prepare data by collecting & storing information
3. **Process**: process data by cleaning & checking information
4. **Analyse**: analyse data to find patterns & trends
5. **Share**: share data with audience
6. **Act**: act on data & use analysis results

### ASK (KPI)
- Heart Disease Prevalence Rate = (No. of individuals having heart disease / Total number of people in dataset)
- Average Age
- Average Resting Blood Pressure
- Average Serum Cholesterol Level
- Percentage of individuals with High Fasting Blood Sugar
- Maximum Heart Rate Achieved by male & female
- Percentage of individuals with Excercise-Induced Angina
- Average ST Depression
- Percentage of individuals with Abnormal Resting Electrocardiographic Results

### PREPARE
- We received our dataset from unified mentor management team

### PROCESS
- Renamed the columns
- Checked for null values from all the columns of the dataset
- We found out most of the dataset was well organized

### ANALYSE
- Sorted & filtered data
- Calculated heart disease prevalence rate throughout the dataset
- Calculated avg. age
- Calculated avg. resting blood pressure
- Calculated avg. serum cholesterol
- Calculated % individual of high fasting blood sugar level
- Calculated peak heart rate in both genders
- Calculated avg. ST depression etc..

  
### SHARE
- Heart Patient: 526
- Non Heart Patient: 499
- Total Patients: 1025
- Heart Disease Prevalence Rate: 51.3 %
- Average age in dataset: 54 years
- Average resting blood pressure: 131 BPM
- Average serum cholesterol: 246 mg/dl
- High fasting blood sugar rate: 14.9 %
- Females in dataset: 312
- Males in dataset: 713
- Max Heart Rate (female): 192 BPM
- Max Heart Rate (male): 202 BPM
- Exercise Induced Angina Rate: 33.7 %
- Average ST depression: 1
- Abnormal Resting Electrocardiographic Rate: 51.5 %

### ACT
- Heart Disease Prevalence: The prevalence of heart disease in the dataset is relatively high at 51.3%, indicating that heart disease is a significant health concern among the patients included in the study.
- Demographic Distribution: The dataset consists of 312 females and 713 males, suggesting a higher representation of males. This may indicate either a higher prevalence of heart disease among males or a higher proportion of males seeking medical attention for heart-related issues.
- Age and Heart Disease: The average age of patients in the dataset is 54 years, indicating that heart disease affects individuals across a wide age range. However, it would be beneficial to analyze the age distribution further to understand if there are specific age groups more susceptible to heart disease.
- Resting Blood Pressure and Serum Cholesterol: The average resting blood pressure and serum cholesterol levels are 131 BPM and 246 mg/dl, respectively. Elevated levels of both indicators are associated with an increased risk of heart disease, highlighting the importance of monitoring these parameters for early detection and prevention.
- High Fasting Blood Sugar: A concerning finding is the high fasting blood sugar rate of 14.9%. Elevated blood sugar levels are associated with diabetes, which is a significant risk factor for heart disease. This suggests a potential need for diabetes screening and management among the patient population.
- Max Heart Rate: The maximum heart rate recorded for males (202 BPM) is higher than that for females (192 BPM). While individual variation exists, this may reflect physiological differences between genders.
- Exercise Induced Angina and Abnormal Resting Electrocardiographic Rate: The rates of exercise-induced angina (33.7%) and abnormal resting electrocardiographic findings (51.5%) are both relatively high. These findings indicate that a significant portion of the patient population experiences symptoms during physical activity and may have abnormal heart rhythms at rest, further emphasizing the prevalence and severity of heart disease in the dataset. <br><br>

In conclusion, the findings suggest a high prevalence of heart disease among the patient population, with several risk factors such as elevated blood pressure, cholesterol levels, and fasting blood sugar.<br>
Additionally, the high rates of exercise-induced symptoms and abnormal electrocardiographic findings underscore the importance of comprehensive cardiac evaluation and management in clinical practice.
