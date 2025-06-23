# Task_1_Data_Cleaning_and_Preprocessing
Task 1: Data Cleaning and Preprocessing – Elevate Labs Data Analyst Internship
<br> 
Date: June 23, 2025
<br>
Author: Mehvish Idreesi 
<br>
## 📝 Objective
The goal of this task was to clean and preprocess a raw dataset by addressing issues like missing values, duplicate records, inconsistent formats, and unstructured columns to make the data analysis-ready.
<br>
---

## 📁 Files in this Repository
| File Name | Description |
|-----------|-------------|
| `netflix_original_data.csv` | Raw dataset used for this task |
| `netflix_cleaned.csv` | Final cleaned version of the dataset |
| `Netflix_data_cleaning.ipynb` | Jupyter Notebook with step-by-step cleaning |
| `README.md` | This file – summary of the project |

---

## 🧹 Data Cleaning Steps Performed
- Checked uniqueness of `show_id` column.
- Removed duplicate rows using `.drop_duplicates()`.
- Dropped rows with missing values in `director`, `type`, and `country` columns.
- Standardized the `title` column (stripped whitespace and title-cased).
- Converted the `date_added` column to datetime format.
- Split the `duration` column into:
  - `duration_num` (numeric duration)
  - `duration_unit` (e.g., minutes, seasons)
- Converted `duration_num` to integer.

---

## 🛠 Tools Used
- Python
- Pandas
- Jupyter Notebook

---

## ✅ Outcome
- A cleaned, structured version of the Netflix dataset ready for analysis or visualization.
- Strengthened understanding of real-world data preprocessing using Pandas.
- Prepared for common data cleaning interview questions.

---

