README for Python Exercises Marcos Dumortier

**Python for Data Science - Session 7**

*Overview*

This Jupyter Notebook is part of the Python for Data Science series, focusing on advanced concepts and techniques using the Pandas library. It builds on foundational knowledge and introduces advanced data manipulation methods, functional programming techniques, and strategies for handling missing data effectively.

*Table of Contents*

Introduction
Lambda Functions and Map
Working with Pandas Series
Advanced Data Manipulation Techniques
Handling Missing Data and Imputation
Practical Examples and Exercises

*Key Features*

Advanced Techniques

- Lambda Functions: Create and use a lambda function to classify flowers based on their petal length.
- Map Method: Apply the map function to convert the Species column into numeric values.
- Data Analysis:
Use value_counts on the Species column to count the number of entries for each species.
Use drop_duplicates to remove duplicate rows based on specific columns like SepalLengthCm and PetalLengthCm.

Data Transformation

- Convert the SepalLengthCm column to a string type using astype, then back to a float type while gracefully handling conversion errors.
- Save the modified DataFrame to a CSV file using to_csv, ensuring the index is preserved.

Handling Missing Data

- Count the number of missing values in each column.
- Replace missing values in the department column with "Unknown".
- Use fillna to fill missing values in the age column with the average age.
- Drop rows where the professor column contains missing values.

Column Manipulation

- Create a new column, professor_last_name, by extracting the last name from the professor column.
