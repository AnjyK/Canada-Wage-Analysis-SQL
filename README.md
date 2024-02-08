# Canada-Wage-Analysis-SQL

### Project Overview
The dataset under analysis is the wages data of Canada from 6 different provinces. The data is obtained from the open Canada statistics website. The data shows wages specific to a job and provide data on how much workers make at the regional level. Most of the occupations also have national and provincial wages. The National Occupational Classification determines which occupational groupings are associated with each job in Canada. A minimum, median, and maximum wage estimate are presented for most occupations.

### Data Sources
We have taken the data from the below file for data analysis purpose.

[CanadaWageAnalysis](https://github.com/AnjyK/Canada-Wage-Analysis-SQL/blob/main/CanadaWage-2022opendata.csv)

### Tools
- PostGreSQL

### Data Cleaning
1.	The original data set had more than 37000 rows of data, for analysis purpose I have only taken 652 rows of data.
2.	Data of 6 provinces for a few NOC title (job titles) have been kept. All job titles are not covered in the data set. 27 different NOC titles have been kept for data analysis purpose.
3.	From the original dataset wages comment column have been removed as it wasn’t providing any extra information related to the data.
4.	Rows like low wage and high wage where there were null values have been removed as the data becomes meaningless if wages are not present. Those rows have been removed.

### Exploratory Data Analysis
1. To find out the province which has the highest/lowest hourly wage which could give valuable insight to individuals who want to move to province for better wages.
2.	To find out the job titles with the highest/lowest hourly wage.
3.	To find out the province wise data of average median, average wages.
4.	To find out wages as per economic region within a province.
5.	To find out which province has the highest median wage.
6.	Higher wages in a job title may indicate greater demand or labour shortage of workers in those provinces/economic regions.
7.	By looking at the wage differences within provinces we can gain insights about the economic strength. Higher wages indicate growth and development and vice versa. 


### Results/Findings
[CanadaWageAnalysis.sql](https://github.com/AnjyK/Canada-Wage-Analysis-SQL/blob/main/CanadaWageAnalysis.sql)

[CanadaWageAnalysisDoc](https://github.com/AnjyK/Canada-Wage-Analysis-SQL/blob/main/Canada%20Wage%20Analysis%20SQL.docx)


                  
