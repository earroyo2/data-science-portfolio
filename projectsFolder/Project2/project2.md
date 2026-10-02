# Project 2

## Problem Definition
As someone who has recently entered adulthood, one of the most crucial components of living on your own is WHERE you are going to live. Not only is the 'where' aspect of a home most important, but another humongous factor of choosing a place to live is price. In this project, I will be predicting the price of various house listings in North Carolina from a dataset via the website Kaggle and was collected "via web scraping using python libraries" (Shahriar Sakib 2023). The target variable of this project is of course 'price' and since this is a numerical feature, it is classified as a regression problem. Someone who may benefit from this model or its predictions may be someone who is in the process of looking for a home, or a new realtor who wants to see which factors impact the price of a home listing. This prediction problem is worth investigating, as if you were someone in the process of looking for a home and the location (for example) is a large factor in price, then that person may want to look for a home in a smaller/less populated location in order to find a cheaper home. 


## Background and Context
In order to understand this problem in general, not much is needed to know besides the fact that different aspects of a home (number of bathrooms/bedrooms, location, etc.) impact the price. As for the code aspect of this project, you will need to understand scikit-learn libraries in Python. (Incomplete)

## Data Description
As previously stated, the data came from a website called Kaggle and was uploaded by Ahmed Shahriar Sakib. An exact date of publication was not listed, but the website did state that the dataset was last updated 3 years ago. The original dataset that I obtained from the website contained 2,226,382 entries and 10 different columns (Shakhriar Sakib 2023). Each row represents a single listing on Realtor.com with available features such as brokered_by, status, price, bed, bath, acre_lot, street, city, state, zip_code, house_size, and prev_sold_date. Since the data was already prepared in a csv file, I did not have any limitations or restrictions with the data itself.

## Data Understanding, Exploration, Preparation, and Feature Selection
Due to the size of the original dataset (and it exceeding the maximum row count that my computer can read), I decided to trim down the amount of rows that I planned on using in the models. The original dataset contained listings from various cities in every state and since I live in North Carolina, I decided to use listings exclusively from my state (making the row count 85,745). When looking at the summary statistics of the housing listings from the North Carolina dataset, I noticed that the average listing had 3 bedrooms and 2 bathrooms, and the average house was 2,058 square feet.  (Incomplete)


After creating a new file with exclusively North Carolina listings, I was sifting through the file to make sure that I obtained the correct information when I noticed that some of the observations did not include values for variables such as bed, bath, and house_size. This is when it occurred to me that the listings within this dataset not only included residential buildings, but empty lots of land as well. Since my problem is based around the prediction of actual buildings, I made the decision to again trim the dataset and remove rows that had missing values for bed, bath, and house_size variables (making the final row count 37,342). The features that I decided to choose for my models were bed, bath, price, acre_lot, and house_size, as since they are numerical they would be the best choice for my prediction problem. I separated my data for testing and training by using the 'train_test_split' function from the 'sklearn.model_selection' library, and prevented data leakage by using the 'StandardScaler' function in 'sklearn.preprocessing'. 

## Baseline and Model Development
The baseline model that I chose was the linear regression model, as my problem is focused around prediction. As for the machine-learning models, I chose to train Lasso and Ridge models because they are a good alternative if the original model has strong multicollinearity. I did not tune any of the model's settings or hyperparameters, and I ensured that the models were compared fairly by initializing and executing the models in the exact same way, as well as extracted the same metrics.

## Model Evaluation and Selection

## Model Interpretation and Insights

## Limitations, Ethics, and Reflection

## Code and Transparency

