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

# Data analysis and visualization.

1. Average Income by Gender

![image](https://github.com/OluwatobiAkintokun/Bike-Sales-Analysis/assets/137109080/04e5c2a8-ec3b-4d7d-a4d0-342c2f51d7c8)



(2)Bike Purchase by Commute Distance

![image](https://github.com/OluwatobiAkintokun/Bike-Sales-Analysis/assets/137109080/82301325-b585-43ff-a1f2-5fc75d1ea388)

Insights: There's a connection between having a bike and how far someone travels to work. Short commutes, like 1-2 miles, show more bike owners on the line graph. In this analysis, there were fewer bike owners with commutes over 10 miles, suggesting longer commutes may lean away from bike ownership.

(3) Bike Purchase by Age Bracket

![image](https://github.com/OluwatobiAkintokun/Bike-Sales-Analysis/assets/137109080/fed8a199-2c9d-44de-b2bd-97c7b2454376)

(4) Bike Purchase by Occupation

![image](https://github.com/OluwatobiAkintokun/Bike-Sales-Analysis/assets/137109080/8fa9695d-951f-4ffd-9e71-384b69cb9d5b)

(5) Total Income by Gender

![image](https://github.com/OluwatobiAkintokun/Bike-Sales-Analysis/assets/137109080/442e2116-1d9d-4f19-8491-24ee61c472ad)

(6) Bike Purchase By Region

![image](https://github.com/OluwatobiAkintokun/Bike-Sales-Analysis/assets/137109080/b2e5c3e1-4c6f-4328-a22c-c8f4e376aecd)

# Dashboard

I created a user-friendly and interactive dashboard with Ms Excel to showcase the outcomes of the data analysis.

![image](https://github.com/OluwatobiAkintokun/Bike-Sales-Analysis/assets/137109080/8b204796-3a3b-4bee-9ed1-b817e3331dde)
