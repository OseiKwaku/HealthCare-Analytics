### Overview
This project analyzes healthcare data for day cases, inpatients, and outpatients to derive insights into hospital performance, speciality groups.. The goal is to identify trends, improve patient care, and optimize resource allocation.

## Key Questions Asked
1. What are the trends in patient volumes for day cases, inpatients, and outpatients?
2. Speciality with the highest and lowest number on patients.
3. The speciality name that brought more patients to the hosipital.

### Tools Used
- Power BI: For data visualization and dashboard creation.
- Kaggle: For sourcing the dataset.
- Excel: For initial data exploration.

### Data Cleaning/ Preparation
- Changed data type in archive_date column from text to date type.
- Renamed columns in the outpatient table and created a custom column for case type in the outpatient table.
- Appended the inpatient and outpatient tables as "All_Data"
- Replaced blank values in the appended table to "No input" for time band and age profile columns. 
