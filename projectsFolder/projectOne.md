# Do counties in North Carolina with large populations have a higher percentage of Black women in higher education?

## Problem Definition


## Data Description
The key variables in this project include: Name of the county, total population by county, total population of Black women by county, and total population of Black women with a bachelor's degree or higher by county. The data was collected from the American Community Survey (ACS) by the US Census Bureau. The most recent data available via an API was from 2024. Each row represents data from a county in North Carolina that the Bureau collected. The main features of the data display the variables in each column. During the data collection, I realized that the dataset was not as large as I expected it to be. I assumed that all 100 counties in North Carolina would be in the dataset, but that turned out to not be the case. After doing a bit of research on the Census Bureau's website, I discovered that the American Community Survey (ACS) "only releases 1-year data for population groups sized 65,000 or more" (Rosenthal 2020). 

## Data Cleaning and Preparation
While scanning my datasets, I noticed that some rows contained null/empty values. The method that I used for cleaning up this data was using the .dropna() function, and dropping the rows with missing values. My justification for dropping the rows was because they didn't appear on my visualizations, therefore they did not provide any actual value to my research question.

## Visualizations and Insights


## Narrative


## Limitations, Ethics, and Reflection


## Code and Transparency


## Citations
Author(s, & Rosenthal, J. (2020, January 2). 4 Easy pieces regarding census data. Nc.Gov. https://www.commerce.nc.gov/blog/2020/01/02/4-easy-pieces-regarding-census-data


