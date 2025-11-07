# Data-cleaning-Python
Description:
This project focuses on cleaning and preparing a raw dataset (datacl.csv) using Python, Pandas, and NumPy.
The cleaning process includes handling missing and invalid values, converting data types, and standardizing inconsistent columns.

Key steps:

Converted 'Easy Apply' column into boolean (TRUE → True, others → False).

Replaced invalid values (-1) in 'Established' with NaN, filled missing values with the median, and converted to int.

Removed rows with missing ratings.

Filled missing ages with the median value.

Verified missing value percentages and confirmed column data types.

After cleaning, the dataset is now consistent, accurate, and ready for analysis or visualization.

📊 Data Visualization Insights: 

<img width="1382" height="777" alt="image" src="https://github.com/user-attachments/assets/dd50d0c2-c281-4b8f-b723-929c4ba53b09" />

After cleaning, the dataset was visualized using Power BI to reveal key relationships between variables such as location, salary, age, and the “Easy Apply” feature.

🔹 1. Sum of Age, Index, and Rating by Easy Apply and Location

Compared multiple locations (Australia, India, New York) based on “Easy Apply” status.

In Australia and New York, candidates with “Easy Apply = True” show higher sums of age and index, suggesting these regions may attract more experienced applicants.

India data displays smaller differences, but the trend still indicates slightly higher ratings for “Easy Apply = True” cases.

🔹 2. Established by Location and Salary (Pie Chart)

Displays salary distribution and company establishment data by location.

New York (NY) dominates with approximately 31.9% of total values, representing the highest salary levels.

Australia (AUS) contributes around 18%, while India (IN) accounts for 14%, indicating regional variation in salary expectations.

💡 Conclusion:

This project demonstrates how structured data cleaning and preprocessing can lead to clear insights when visualized.
Through Python data preparation and Power BI analytics, we successfully:

Identified differences between regions,

Assessed how “Easy Apply” impacts job-related metrics,

And visualized salary distributions for better decision-making.



