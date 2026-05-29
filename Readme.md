# Titanic Data Cleaning & Preprocessing

## 📌 Project Overview

This project focuses on cleaning and preprocessing the Titanic dataset. The goal is to transform raw data into a clean and structured format suitable for further analysis and machine learning applications.

## 🎯 Objective

- Handle missing values
- Remove duplicate records
- Convert data types where necessary
- Rename columns for better readability
- Create clean datasets ready for analysis

## 📂 Dataset

The project uses the Titanic dataset containing the following files:

- train.csv
- test.csv
- gender_submission.csv

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Google Colab / Jupyter Notebook

## 🔄 Data Preprocessing Steps

### 1. Handling Missing Values
- Numerical columns were filled using median values.
- Categorical columns were filled using mode values.

### 2. Removing Duplicates
- Duplicate records were identified and removed.

### 3. Data Type Conversion
- Appropriate data types were assigned to columns.
- Age column was converted from float to integer after rounding.

### 4. Column Standardization
- Column names were reviewed and standardized for consistency.

## 📊 Output

Generated cleaned datasets:

- train_cleaned.csv
- test_cleaned.csv
- gender_submission_cleaned.csv

These datasets are now ready for Exploratory Data Analysis (EDA) and Machine Learning tasks.

## 📁 Repository Structure

```
synent-task1-titanicdatacleaning-buddy
│
├── notebook
│   └── titanic_cleaning.ipynb
│
├── cleaned_data
│   ├── train_cleaned.csv
│   ├── test_cleaned.csv
│   └── gender_submission_cleaned.csv
│
└── README.md
```

## 🚀 Key Learnings

- Data Cleaning Techniques
- Missing Value Treatment
- Data Type Conversion
- Duplicate Handling
- Data Preprocessing Workflow

## 👨‍💻 Author

Preet Dhoriyani

Summer Internship Program – Synent Technologies