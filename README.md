🏥 Indian-disease-data-analysis
📊 Project Overview

This project analyzes healthcare data to understand disease patterns, patient demographics, recovery duration, and mortality trends in India. The goal is to use data analytics techniques to uncover insights that can help improve healthcare decision-making and patient outcomes.

📂 Dataset Summary

Rows: 10,000

Columns: 14

Key Features

Patient Information: Patient ID, Age Group, Gender, Blood Group

Disease Details: Disease Name, Symptoms, Diagnosis Date

Health Factors: Comorbidity, Alcohol Use, BMI

Medical Outcomes: Recovery Days, Cause of Death

Missing Data

Missing values were found in some columns such as Comorbidity, Alcohol Use, Cause of Death, and Recovery Days, which were handled during data cleaning.

🛠 Tools & Technologies

Python

Pandas

MySQL

SQLAlchemy

Matplotlib

Jupyter Notebook / Python Scripts

🧹 Data Cleaning & Preparation

The dataset was cleaned and prepared using Python.

Key steps included:

Handling missing values using median and default values

Standardizing categorical values

Converting diagnosis_date to datetime format

Creating structured data suitable for SQL analysis

Loading the cleaned dataset into a MySQL database

🔍 Exploratory Data Analysis

Initial exploration was performed using Python to understand the dataset structure.

Steps performed:

Used data.info() and data.describe()
 
Checked missing values using isnull()

Verified unique values in categorical columns

Examined disease distribution and recovery patterns

🗄 Database Integration

The cleaned dataset was loaded into MySQL using SQLAlchemy.

Steps included:

Creating a MySQL database

Establishing a Python–MySQL connection

Uploading the cleaned dataset to a database table

Querying the data for further analysis

📈 Data Analysis using SQL

Key analytical questions explored:

What is the total number of patients registered in the dataset?

Which disease has the highest number of reported cases?

What is the average recovery time for each disease?

What is the total number of recorded deaths?

Which disease has the highest mortality rate?

What is the gender distribution of patients?

How many cases were reported each month?

Is there a difference in average recovery time between alcohol users and non-users?

Do patients with comorbidities have a higher risk of death compared to those without comorbidities?

Which five patients had the longest recovery duration?

📊 Key Insights

Certain diseases showed significantly higher case counts compared to others.

Recovery time varies depending on disease type and patient health conditions.

Patients with comorbidities may have higher health risks.

Monthly trends help identify seasonal disease patterns.

💡 Business Recommendations

Focus healthcare resources on diseases with high case counts and mortality rates.

Promote early diagnosis and preventive healthcare programs.

Monitor high-risk patients with existing health conditions.

Use healthcare data analytics for better policy and hospital management decisions.

PATH:-
Indian-Disease-Analysis
│
├── dataset
│   └── indian_diseases_dataset.csv
│
├── python_script
│   └── disease_analysis.py
│
├── sql_queries
│   └── analysis_queries.sql
│
└── README.md
👨‍💻 Author

Vivek Patil

📧 Email: vivekpatilavailable07@gmail.com

🌐 Portfolio: https://vivekpatil07-available.github.io
