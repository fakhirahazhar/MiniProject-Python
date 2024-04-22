# MiniProject-Python
How to create a DataFrame in Python using pandas library. This DataFrame is named Rekap_Nilai_Student and is filled with several data columns, each of which takes values from several variables: ID, assignment, UTS, UAS, and information

## Creating DataFrame

pd.DataFrame() is a function from pandas library which is used to create DataFrame objects. DataFrame is a very commonly used data structure in data science and data analysis because it provides an efficient table-like structure for data manipulation and storage.

## Data Column 

In creating this DataFrame, we fill the DataFrame with data stored in dictionary form where the dictionary key is the column name and the value of the key is the data for that column.
  - 'Student ID': This is the column that will store data from the ID variable.
  - 'Task': This column will store the task value of the task variable.
  - 'UTS': This column will store the Midterm Exam scores from the UTS variable.
  - 'UAS': This column will store the Final Semester Exam scores from the UAS variable.
  - 'Description': This column will store information that may be related to student performance or status, from the description variable.

## Data Source Variables

ID, assignment, UTS, UAS, and description are variables that must be previously defined that store the data that will be entered into the DataFrame. This can be a list, array, or series from pandas.

<div align="center"><img src="https://github.com/fakhirahazhar/MiniProject-Python/assets/165735471/fd767bee-bfe4-4f19-9d63-66ea4e357561" /></div>
