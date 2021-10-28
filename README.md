# Project_1_COVID19_Team_ABC
This repository for the Project #1 of the GA Tech Data Bootcamp

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
