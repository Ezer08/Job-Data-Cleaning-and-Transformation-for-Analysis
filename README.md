Job Salary and Company Data Cleaning Project 📊🔍


Overview 🌟


This project is focused on cleaning and transforming a dataset containing job salary estimates, company details, and job descriptions. The goal is to provide a well-organized and structured dataset, which can be used for further analysis or visualization.

The dataset includes various columns such as job titles, salary estimates, company ratings, and more. The main objective of this project is to clean and process the raw data, handle missing values, remove irrelevant information, and convert some columns into more useful formats.

Key Features ⚙️


Data cleaning and transformation of raw job-related data 🧹
Extraction of salary ranges from raw salary estimates 💵
Removal of irrelevant characters and columns 🚮
Standardization of company and job-related information 🏢
Reorganization of dataset columns for better readability 🔄
Handling of missing values and duplicates 🔄

Technologies Used 🛠️

Python 🐍
Pandas 📊
Regular Expressions (Regex) 📝
Steps Performed 📝


1. Data Inspection 🔍

Checked the shape and columns of the dataset
Inspected data types of each column
Handled missing values and duplicate rows


2. Data Cleaning 🧼

Removed unnecessary columns, such as the index column
Cleaned the Salary Estimate column by removing characters like 'K', '$', and '(Glassdoor est.)'
Split salary ranges into Salary Min and Salary Max columns
Converted salary columns into integers and calculated the average salary
Cleaned the Job Description column by removing newline characters and extra spaces
Standardized company names by removing ratings from the Company Name column
Extracted state names from the Location column and converted state abbreviations to full names
Renamed columns like Size to Number of Employees for clarity
Converted the Revenue column to a consistent format with revenue ranges
Reorganized columns for a more readable format


3. Final Dataset 🗂️

The dataset is now clean and well-organized, ready for analysis or visualization
Renamed specific columns to indicate values are in thousands (K)
Dropped unnecessary columns such as Salary Estimate
