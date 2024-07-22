# Group One Project One README 

## Project Overview 

# Purpose

The purpose of this project was to analyze the relationship between the 
following variables and cancer death rates per U.S region, limited by data 
constraints to the years 2015-2019, with the desire to see if any of these 
relationships were statistically significant enough to take policy action 
in both the public and private spheres. 
1-	Poverty Rate
2-	Divorce & Marriage Rates
3-	Medicaid & Uninsured Rates 


In conjunction with the analysis, we set out to answer three questions through 
the results found within the data. 
1)	*Does income and/or health insurance access impact your likelihood of having cancer?*

2)	*Do regions with higher cancer rates also show higher divorce rates?*

3)	*Is there a relationship  between regional poverty rates and healthcare* 
    *access metrics, and how does this affect cancer outcomes?*

# Datasets 

The datasets that were used for this study are the following: 
1	– 
2	– 
3	– 
4	– 

*NOTE: The datasets came in a variety of year ranges. To make the analysis* 
*smoother, the year range for each dataset was pared down to the year range 2014 – 2019.* 

*NOTE: The datasets used were read-in either by state or geographical location* 
*per the classification used by the U.S Census Bureau. The final datasets were* 
*then organized solely by geographical location for data analysis purposes.*

*NOTE: For Divorce Data set, California, Hawaii, Indiana, Minnesota, Georgia,*
*and New Mexico were dropped during data cleanup due to either no or partial*
*data available* 


# Installation and Usage 

1) Clone the repository in Terminal or Git Bash

![alt text](<Images/git clone example README.png>)

2) Import Dependencies 

![alt text](<Images/Install Dependencies ReadME.png>)

Note: If you are unable to import dependencies, please run *pip install* through
Terminal or Git Bash 

![alt text](<Images/pip install ReadME.png>)

3) Verify Correct read-in files 

- Medical Care Data 

![alt text](<Images/geographic_data read-in ReadMe.png>)

- Divorce Data 

![alt text](<Images/divorce_data read in ReadME.png>)

- Marriage Data 

![alt text](<Images/marriage_data read-in ReadME.png>)


- Poverty Data 

![alt text](<Images/poverty_2015 data read in ReadME.png>)

![alt text](<Images/poverty_2016 data read in ReadME.png>)

![alt text](<Images/poverty_2017 data read in ReadME.png>)

![alt text](<Images/poverty_2018 data read in ReadME.png>)

![alt text](<Images/poverty_2019 data read in ReadME.png>)

![alt text](<Images/poverty_2020 data read in ReadME.png>)

![alt text](<Images/poverty_2022 data read in ReadME.png>)


- Cancer Data 

![alt text](<Images/cancer_2015 data read in ReadME.png>)

![alt text](<Images/cancer_2016 data read in ReadME.png>)

![alt text](<Images/cancer_2017 data read in ReadME.png>)

![alt text](<Images/cancer_2018 data read in ReadME.png>)

![alt text](<Images/cancer_2019 data read in ReadME.png>)


- Health Insurance/Medicaid Data 

![alt text](<Images/health_insurance data read in ReadME.png>)

![alt text](<Images/health_insurance-rates data read in ReadME.png>)


4) Usage Instruction 

- Datasets are formatted into pivot tables based on U.S regions and have 
    had suffixes added to differentiate each regional dataset from another. 

Example:
![alt text](<Images/pivot_table_data_example README.png>)

![alt text](<Images/pivot_table_example ReadME.png>)

- Pivot Tables were/can be merged for statistical comparisons or plotting

Examples: 

Summary Statistics Table 

![alt text](<Images/marriage_divorce_code_example ReadME.png>)

![alt text](<Images/summary_statistics_usage data ReadME.png>)


Combined Data for Plotting 

![alt text](<Images/south_combined_data_example README.png>)

![alt text](<Images/plotting_usage_data example ReadME.png>)

![alt text](<Images/south_data_plot_code example README.png>)

![alt text](<Images/data_plot_usage_example README.png>)


# Results: 


Question #1: *Does income and/or health insurance access impact your* 
*likelihood of having cancer?*

Answer: To best answer this question, we ran two separate graphs. The first was
a visual comparison between cancer rates and medicaid rates, while the second 
was a standalone line graph dedicated to poverty rates. The separation was 
due to the difference in magnitude between the cancer/medicaid rates and 
the poverty rates 