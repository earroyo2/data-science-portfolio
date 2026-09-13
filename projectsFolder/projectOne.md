# Do counties in North Carolina with large populations have a higher percentage of Black women in higher education?

## Problem Definition
The problem that I chose to explore was "Do counties in North Carolina with larger populations have a higher percentage of Black women in higher education?". The reason I chose this topic, is because as a Black woman who is pursuing a bachelor's degree, I am aware that there aren't as many Black women that I expected who are pursuing or have higher education degrees. One of my goals in life is to serve as an example for younger Black girls, so that they can grow up and aspire to pursue higher education as well.

## Data Description
The key variables in this project include: Name of the county, total population by county, total population of Black women by county, and total population of Black women with a bachelor's degree or higher by county. The data was collected from the American Community Survey (ACS) by the US Census Bureau. The most recent data available via an API was from 2024. Each row represents data from a county in North Carolina that the Bureau collected. The main features of the data display the variables in each column. During the data collection, I realized that the dataset was not as large as I expected it to be. I assumed that all 100 counties in North Carolina would be in the dataset, but that turned out to not be the case. After doing a bit of research on the Census Bureau's website, I discovered that the American Community Survey (ACS) "only releases 1-year data for population groups sized 65,000 or more" (Rosenthal 2020). 

## Data Cleaning and Preparation
While scanning my datasets, I noticed that some rows contained null/empty values. The method that I used for cleaning up this data was using the .dropna() function, and dropping the rows with missing values. My justification for dropping the rows was because they didn't appear on my visualizations, therefore they did not provide any actual value to my research question.

## Visualizations, Insights, and Narrative
<img src="TotPopVBW.png" alt="Bar Chart" width="400">
The first visualization that I decided to create, was a bar chart of the total population in each county in North Carolina (from the cleaned data) versus the total population of Black women there. As observed in the chart, all county's in our state have a small population of Black women compared to the total. In the most populated county recorded in 2024, Wake county had a total of just over 1.2 million people, with their population of Black women being only 125,000. Thus meaning that even the most heavily populated county in North Carolina was made up of 10.16% Black women. In contrast, there were many counties 



## Limitations, Ethics, and Reflection
The details of this dataset fail to capture the demographics of every single county in North Carolina, which of course leads to a collection gap. If there were a way for me to do so, I would explore the demographics (variables) across every single county in North Carolina.

## Code and Transparency


## Citations
Author(s, & Rosenthal, J. (2020, January 2). 4 Easy pieces regarding census data. Nc.Gov. https://www.commerce.nc.gov/blog/2020/01/02/4-easy-pieces-regarding-census-data


