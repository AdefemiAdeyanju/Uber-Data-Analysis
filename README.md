# Uber-Data-Analysis
An analysis on Uber dataset using Python

This project was undertaken to understand the usage of Uber services in a particular month. I achieved this through thorough data analysis and visualisation.

## Project Steps

### Step 1 - Data Collection

*I downloaded the uber dataset from kaggle to perform analysis and imported it into jupyter notebook using the pd.read_csv method.


### Step2 - Data Cleaning and Exploratory Data Analysis

*I derived basic information from the above collected data using the .info(), .describe() and .head() methods.
*I wrote a function to determine the number of null values, of which there were none.(This can also be done easily using the pandas .isnull method)
*I converted date object to DateTime format and added day of the week, hour of day etc to the column.
*I inspected the length of the dataset using the .shape method.
*I inspected the Base column using the .unique() method.
*I wrote a function to determine the number of trips made daily.
*I sorted the Day of the month by values rather than date.
*I wrote some code to determine the trips made. (DayofWeekNum 0 - 6 representing days of the week and HourOfDay 0 - 23 representing the time in 24h format)

### Step3 - Data Visualization

*I visualized total rides using the Base column.
*I plotted a pivot table visualization based on the day number and the day of the week in relation to the Base.
*I plotted a pivot line chart based on the HourOfDay and Base to visualize the journeys made.
*I plotted a pivot bar chart based on the HourOfDay and Base to visualize the journeys made.
*I plotted a bar chat to analyze hours of trip made.
*I potted a heat map on the Day/Hour with highest frequency of trips made.

### Suggestions on future work/Improvement plans

*I would love to analyze and compare datasets of previous years to predict the usage of uber services in forthcoming years.
