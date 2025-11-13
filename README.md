🧹 Elevate Labs - Task 1: Data Cleaning and Preprocessing
👩‍💻 Author: Layeba Sayyed
💼 Internship: Data Analyst Intern at Elevate Labs
📘 Overview
This project is part of Elevate Labs Data Analyst Internship – Task 1, focused on data cleaning and preprocessing using Python (Pandas, NumPy).
The goal is to transform a raw dataset into a clean, well-structured format ready for analysis.

Dataset Used: Medical Appointment No Shows (Kaggle Dataset)
This dataset contains information about medical appointments in Brazil and whether patients showed up for their appointments.

🎯 Objective
To clean and prepare a real-world dataset by:
Identifying and handling missing values
Removing duplicates
Standardizing text values
Converting inconsistent date formats
Renaming columns for uniformity
Ensuring correct data types
Detecting and handling outliers

🛠️ Tools & Libraries Used
Python 3.x
Pandas – for data cleaning and manipulation
NumPy – for numerical operations
VS Code / Jupyter Notebook / Command Line (optional)

📂 Files in This Repository
File Name	Description
KaggleV2-May-2016.csv	- Original raw dataset
cleaning_script.py - Python script for cleaning the dataset
cleaned_medical_appointments.csv	- Cleaned and processed dataset
cleaning_summary.txt - Summary of all cleaning steps performed
README.md	- Project documentation file

🧾 Step-by-Step Cleaning Process
Loaded dataset using Pandas.
Checked dataset structure and identified missing values.
Removed duplicate rows to ensure data uniqueness.
Standardized column names (lowercase, underscores).
Converted date columns (ScheduledDay, AppointmentDay) to datetime format.
Standardized text values in Gender and No-show columns.
Handled missing values using .fillna() and median imputation.
Removed invalid ages (negative values).
Converted numeric columns to integer types.
Capped extreme outlier ages above 100.
Saved cleaned dataset and generated summary report.

📊 Output
✅ Cleaned Dataset: cleaned_medical_appointments.csv
✅ Cleaning Summary: cleaning_summary.txt
✅ Ready for Analysis / Visualization Tasks

🧠 Learning Outcome
Improved skills in data cleaning and preprocessing using Pandas.
Gained experience handling real-world datasets.
Strengthened understanding of data quality and consistency before analysis.

📅 Internship Context
This task is part of the Data Analyst Internship Program by Elevate Labs.
Task 1: Data Cleaning and Preprocessing
Duration: 1 Day (10 AM – 10 PM Submission Window)
