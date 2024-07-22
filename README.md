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



*NOTE: The datasets came in a variety of year ranges. To make the analysis* 
*smoother, the year range for each dataset was pared down to the year range 2014 – 2019.* 

*NOTE: The datasets used were read-in either by state or geographical location* 
*per the classification used by the U.S Census Bureau. The final datasets were* 
*then organized solely by geographical location for data analysis purposes.*

*NOTE: For Divorce Data set, California, Hawaii, Indiana, Minnesota, Georgia,*
*and New Mexico were dropped during data cleanup due to either no or partial*
*data available* 


# Installation and Usage 

1) **Clone the repository in Terminal or Git Bash**

![alt text](<Images/git clone example README.png>)

2) **Import Dependencies** 

![alt text](<Images/Install Dependencies ReadME.png>)

Note: If you are unable to import dependencies, please run *pip install* through
Terminal or Git Bash 

![alt text](<Images/pip install ReadME.png>)

3) **Verify Correct read-in files** 

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


4) **Usage Instruction** 

- *Datasets are formatted into pivot tables based on U.S regions and have* 
    *had suffixes added to differentiate each regional dataset from another.* 

**Example:**


![alt text](<Images/pivot_table_data_example README.png>)

![alt text](<Images/pivot_table_example ReadME.png>)

- *Pivot Tables were/can be merged for statistical comparisons or plotting*

**Examples:** 


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

Answer: To best answer this question, we pared down the data to only the U.S 
South and ran two separate graphs. The first was
a visual comparison between cancer rates and medicaid rates, while the second 
was a standalone line graph dedicated to poverty rates. The separation was 
due to the difference in magnitude between the cancer/medicaid rates and 
the poverty rates from a numerical standpoint. It would be easier to get a visual
on any relationship by separating out the graphs. In tandem with the graphs, a
correlation table was ran, comparing the three variables. We found a 
statistically significant relationship between the Poverty Rate and Cancer Rates
in the U.S South, and but not for Medicaid Rates and Cancer Rates and Poverty 
Rates and Medicaid Rates in the U.S South. Based on our data, we can say that 
a relationship exists between the Cancer Rate and Poverty Rate, but more 
research and analysis is needed. 

![alt text](<Images/Graph #1, Q1 Cancer vs Medicaid.png>)

![alt text](<Images/Graph #2, Q1, Poverty.png>)

![alt text](<Images/Correlation Q1 .png>)



Question #2:*Do regions with higher cancer rates also show higher divorce rates?*

Answer: To best answer this question, we pared down the data to the U.S South, 
which showed a slight divergence from the downward trend for all divorce rates
per region.  In conjunction with the comparison between the divorce rate and 
cancer rate in the U.S South, we added a third variable, Marriage Rates, to see
that variables relationship with the others, considering that the marriage rate
is interrelated with the divorce rate. We had to run a separate visual for 
cancer rates due to the its percentage range being less than .2 and the 
marriage/divorce rates being between 2 and 8. Comparing both graphs side by side
a slight downward trend is prevelant in all three variables, excepting the 
slight upturn in the divorce rate between 2018-2019. After running a correlation
table, we found that significant correlations exist between all three variables,
with the highest being .98 and the lowest being 0.81. Cancer Rates and Marriage 
Rates had the highest statistical correlation, followed by Divorce Rates and 
Cancer Rates. Based on our data, we can say that there is significant 
statistical relationships between all three variables. It is peculiar to see 
that marriage rates have a stronger correlation with cancer rates than divorce 
rates do, and considering that both within the range of years we graphed have a
downward trend, one would be tempted to make the claim that if one wishes to 
avoid getting cancer, then one should also avoid getting married. More research 
and analysis must be done. 


![alt text](<Images/Graph #1, Q2 South_Cancer.png>)


![alt text](<Images/Graph #2, Q2 South_Divorce_Marriage_Cancer.png>)


![alt text](<Images/Correlation Q2 .png>)



Question #3: *Is there a relationship  between regional poverty rates and*
*healthcare access metrics, and how does this affect cancer outcomes?*

To best answer this question, we pared down the data to the US South, in line 
with our approach to the answers given for the previous questions. Due to the 
low percentage for Cancer rates, it was excluded from the visual representations
that were created. Comparing the Poverty Rate vs Medical Access data, we see 
from a visual standpoint a negative correlation between the two datasets. When 
we bring in a correlation table, our suspicions are confirmed. South Medical Care
and South Poverty rates do share a negative correlation, at -0.95. South Cancer
Rates and South Poverty Rates share a positive correlation at 0.97, and South 
Medical Care and South Cancer rates negative correlation of -0.91. In conclusion, 
we see that there are significant relationships between each of these variables. 
However, they go against the group member's intuition. We believed that when 
poverty rates increase, denial or delay in medical care should also increase 
due to prohibitive costing. The data shows the opposite, as does the relationship
between South Cancer rates and South Medical Care rates. The only correlation 
that matched our intutions was South Poverty Rates vs. South Cancer Rates, which
showed that as poverty rates either increase or decrese, cancer rates follow
the same patterns. More research and analysis will need to be conducted.

![alt text](<Images/Graph #1, Q3, Poverty Rate vs Medical Access.png>)


![alt text](<Images/Graph #2, Q3 South_Divorce_Marriage_Cancer.png>)


![alt text](<Images/Correlation Q3.png>)







