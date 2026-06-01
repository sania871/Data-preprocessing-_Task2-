# Data-preprocessing-_Task2-
Student Scores Analysis with NumPy & Pandas
 Overview
This project demonstrates how to clean, preprocess, and analyze student performance data using Python libraries NumPy and Pandas.
It covers statistical calculations, data exploration, preprocessing (handling missing values, correcting formats, removing outliers and duplicates), and basic insights.

🛠️ Technologies Used
Python 3.x

NumPy

Pandas

 Project Workflow
Part 1 — NumPy Operations
Extracted math_score column as a NumPy array.

Calculated mean, median, maximum, and minimum values.

Printed results for quick statistical overview.

Part 2 — Pandas Exploration
Loaded dataset using Pandas.

Displayed first 5 rows (df.head()).

Checked data types of all columns (df.dtypes).

Counted missing values in each column (df.isnull().sum()).

Identified students with attendance < 70%.

Part 3 — Data Preprocessing
Handled missing values:

Filled math_score, science_score, and attendance with their respective mean values.

Filled gender with mode value.

Replaced "twenty" in age with numeric 20 and filled missing ages with mode.

Converted age column into numeric format.

Outlier handling:

Applied IQR method to clip extreme values in math_score and science_score.

Removed duplicate rows to ensure dataset consistency.
