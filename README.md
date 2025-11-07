# Data-cleaning-Python
Description:
This project focuses on cleaning and preparing a raw dataset (datacl.csv) using Python, Pandas, and NumPy.
The cleaning process includes handling missing and invalid values, converting data types, and standardizing inconsistent columns.
<img width="1382" height="777" alt="Screenshot 2025-11-07 075917" src="https://github.com/user-attachments/assets/8058e04d-f1e0-48fd-add3-1cb5418220b6" />

Key steps:

Converted 'Easy Apply' column into boolean (TRUE → True, others → False).

Replaced invalid values (-1) in 'Established' with NaN, filled missing values with the median, and converted to int.

Removed rows with missing ratings.

Filled missing ages with the median value.

Verified missing value percentages and confirmed column data types.

After cleaning, the dataset is now consistent, accurate, and ready for analysis or visualization.




