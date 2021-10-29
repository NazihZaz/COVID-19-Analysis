# Project_1_COVID19_Team_ABC
This repository is for the Project #1 of the GA Tech Data Bootcamp

The purpose of this project is to analyze certain metrics related to the COVID 19 pandemic such as the most affected states, the rate of positive cases per state or the relationship between COVID ICU bed Usage and COVID hospital bed usage. The questions we attempted to answer were: 
1. What US states were the most affected by the COVID 19 pandemic and what was their answer? 
2. Are the states with larger population the most impacted by COVID 19? 
3. How are the medical services affected by COVID19?
4. Is Vaccination the right answer to this pandemic? 

Overview of our process to find these answers: 
First, we utilized the COVID 19 ACT NOW API to pull in COVID data in .json format. 
Then we created a For Loop to aggregate the data we wanted into lists, and then created our DataFrame. 
After putting our data into our DataFrame, we did some cleaning of the data to drop rows with missing data, and we also created some columns for additional calculations. 
Retrieved Latitude and Longitude data for states, and merged to our DataFrame. 
Dropped any rows with missing values to create a clean DataFrame to work with. 
Utilized our DataFrame to analyze various metrics and answer the questions we had. 
MatPlotLib and Google Maps’ Heat Maps were created to analyze our data.
Png files of our Data Visualizations, and full Panda's script for analysis are included in this Repository. 

## Note: It is important to note that the API calls were performed on 10/28/2021.

## Outputs generated:

[Output 1: Created a DataFrame that contains our Data]:

[Output 2: Gmaps Heatmap of Death Toll in the US]:

[Output 3: Bar graph of Completed Vaccination Ratio per State]:

[Output 4: Scatter plot using Linear Regression of Postive Test T compared to Population]:

[Output 5: Scatter plot using Linear Regression of Death Toll compared to Population]:

[Output 6: Scatter plot using Linear Regression of Death Toll compared to COVID Hospital Bed Usage]:

[Output 7: Scatter plot using Linear Regression of ICU Bed COVID Usage compared to Hospital Bed COVID Usage]:

[Output 8: Scatter plot using Linear Regression of ICU Bed COVID Usage vs Completed Vaccination Rate]:

[Output 9: Scatter plot using Linear Regression of Postive Case Ratio compared to Completed Vaccination Rate]:

[Output 10: Scatter plot using Linear Regression of Case Density compared to Completed Vaccination Rate]:



## Conclusions: 
1. States most affected by COVID from a volume standpoint were some of the largest states by population such as California, New York, Texas. 
2. There is a strong relationship between overall Hospital Bed COVID Usage and their escalation to the ICU. Ultimately, cases leading to an ICU admissions have a higher chance of leading to death. 
3. Higher Vaccination ratios led to a lower Positive Case Ratio and a lower Case Density overall. 
