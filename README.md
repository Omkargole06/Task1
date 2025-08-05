# 📝 Task 1 – Data Cleaning and Preprocessing

## 🎯 Objective
To clean and preprocess a raw dataset by handling missing values, removing duplicates, fixing inconsistent formats, and standardizing data for analysis.

## 📊 Dataset
- **Netflix Movies and TV Shows Dataset**
- Source: [Kaggle Netflix Titles Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)

## 🛠️ Tools Used
- Microsoft Excel (manual cleaning)
- Python (Pandas library)
- Jupyter Notebook

## 🧹 Cleaning & Preprocessing Steps
- Removed duplicate rows based on `show_id`
- Filled missing values in `director`, `cast`, `country`, `rating` with 'Unknown' or 'Not Rated'
- Standardized text formats (lowercased, trimmed extra spaces)
- Converted `date_added` column to proper Date format
- Renamed columns to lowercase with underscores
- Fixed data types (e.g., numeric, categorical)

## 📁 Files Included
| File Name             | Description                                      |
|-----------------------|--------------------------------------------------|
| `netflix_titles.csv`  | Raw dataset downloaded from Kaggle               |
| `Cleaned_data.csv`    | Cleaned dataset (Python cleaned)                 |
| `Cleaned_data.xlsx`   | Cleaned dataset (Excel cleaned)                  |
| `dataclean.ipynb`     | Python notebook with data cleaning code          |
| `task 1.pdf`          | Task description file (as given)

## 📊 Outcome
- Duplicates removed
- Missing values handled
- Data formats standardized
- Columns renamed and types corrected
- Dataset ready for further analysis

## ✅ Submission
Task submitted as per internship guidelines via GitHub repository.
