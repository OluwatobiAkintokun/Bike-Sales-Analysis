# Introduction

# Business questions
The analysis of Bike Purchases dataset is directed toward addressing the following business inquiries.

(1) Average Income Per Bike Purchase
(2)Bike Purchase by Commute Distance
(3) Bike Purchase by Age Bracket
(4) Bike Purchase by Occupation
(5) Total Income by Gender
(6) Bike Purchase By Region

# Dataset
The Bike Purchase dataset comprises 13 columns, namely ID, Marital Status, Gender, Income, Children, Education, Occupation, Home Owner, Cars, Commute Distance, Region, Age, and Purchased Bike. In total, there are 13 columns and 1026 rows in the raw dataset. [Download here](https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx)

# Data cleaning and transformation
The data cleaning and transformation were carried out using Ms Excel. The following actions were taken to enhance the quality and structure of the data.

* A total of 26 duplicate records were eliminated from the dataset for the purpose of enhancing data integrity.
* I modified the Marital Status column in the dataset to ensure data uniformity. Specifically, I replaced 'S' with 'Single' and 'M' with 'Married' in the Marital Status column.
* I made the Gender column clearer by replacing 'F' with 'Female' and 'M' with 'Male,' making it easier to understand the data.
* I created an additional column named 'Age Bracket' using the IF formula. The formula is designed to categorize ages below 31 as "Adolescent", those equal to or above 31 as "Matured Age", and individuals aged 54 and above as "Old". The applied formula is: =IF(L2>54, "Old", IF(L2>=31, "Middle Age", IF(L2<31, "Adolescent", "Invalid"))).
* I changed '10+ Miles' to '10 Miles and Above' in the 'Commute Distance' column to make it easier to understand.

# Data analysis and insights

(1) Average Income Per Bike Purchase
(2)Bike Purchase by Commute Distance
(3) Bike Purchase by Age Bracket
(4) Bike Purchase by Occupation
(5) Total Income by Gender
(6) Bike Purchase By Region

# Data Visualization
![image](https://github.com/OluwatobiAkintokun/Bike-Sales-Analysis/assets/137109080/8b204796-3a3b-4bee-9ed1-b817e3331dde)
