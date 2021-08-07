# [Airbnb Listing Price Predictor](https://github.com/dungngo99/airbnb-listings) &middot; [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/dungngo99/airbnb-listings/blob/master/LICENSE)

A final project for my data science class at Tulane where I built a regression model (KNN) to predict the airbnb rental price in New York City.

## Link to live webpage: https://dungngo99.github.io/airbnb-listings/

## 📚 Table of contents

- [Technical stack](#technical-stack)
- [Introduction](#introduction)
- [Project Plan](#projectplan)
- [Conclusion](#conclusion)
- [Note](#note)
- [License](#license)

## 🛠 Technical stack

- Python libraries: 
  1. Data extraction and manipulation: numpy, pandas
  2. Data visualization: plotly, seaborn, ipywidgets, and matplotlib
  3. Data analysis: scipy and scikit-learn

## 🚀 Introduction

Airbnb's first appearance in 2008 has a disruptive change in hospitality and accommodation around the world. This tutorial gives you basic information about Airbnb operations and its relationship with customers (hosts and travelers). All the source codes will be done in Python with emphasis on Data Visualization and Data Analysis.

## ⬇ Project Plan

The project will answer the follow questions with data analysis:
1. Is there any correlation between price and number of reviews, rating scores, host response rate, or number of bedrooms of a house?
2. What is the price distribution of Airbnb listings?
3. Which locations in NYC have the highest price and rating scores?
4. What are the popular room types and house types in NYC?
5. What time of the year are AirBnBs most popular in New York City? Are specific holiday seasons more popular?
6. Can we predict the rental price given several features? Which kind of model will we use to predict the most accurately?
7. What can we understand from the customers' reviews? What changes should we make to make them happier?
8. How do NYC Airbnb listings compare with Boston or San Francisco's ones?

## 🤩 Conclusion
1. Is there any correlation between price and number of reviews, rating scores, host response rate, and average number of rooms?
  - There is a postive correlation between price vs. host response rate, and price vs. average number of rooms. 
  - Possible suggestions for hosts are that they should increase their response rate and renovate their houses such as adding more side beds or utilities in the kitchen. 
  - On the other side, rating scores and number of reviews may not have relationship with rental price. Two former features will be included in the training set for Machine Learning model.

2. What is the price distribution of Airbnb listings in NYC?
  - The rental distribution can be seen in the boxplot. The mean price is 173 dollars, which is similar to those of big cities, such as San Franciso or Boston. The distribution is skewed to the right, which indicates that the mean is higher than the medium.

3. Which locations in NYC have the highest price?
  - Manhattan has the most expensive rentals compared to the other boroughs. Prices are higher for rentals closer to city hot spots. However, there are a few outliers in Bronx, Staten Island and Brooklyn that defy the above hypothesis.

4. What are the popular room types in NYC?
  - The most popular room type are Entire home/apt.

5. What times of a year does rental listings increase? Are there any specific holiday seasons that suddenly change the number of listings?
  - The demand shows a seasonal pattern - demand increases from January to October, then drops slightly in November and December. In general, the demand for Airbnb listings has been steadily increasing over the years.

6. Can we predict the rental price given several features? Which kind of model will we use to do so?
  - KNN model is used to fit the training data. After running data visualization, I come up with seven features that are related to the rental price. However, training and test errors are high for this model, which suggests that either the prices of Airbnb apartments are rather arbitrary or there exists other more influential factors that are not included in this dataset.

7. What can understand from the customers' reviews? What changes should we execute to make them happier?
  - As we can see in the two WordClouds, the customers care about the living room, kitchen, transportation, and house location. A possible suggestion for hosts can be that they should pay attention to customers' reviews and make reasonable changes to satisfy them.

8. How do NYC listings compare to ones of Boston and San Francisco?
  - In addition to the price we discussed above, NYC's percents of room types are approximately close to those of Boston or San Francisco. This makes sense since Airbnb owners gain the most profit if they lend entire home/apt.

## 😀 Note
I also acquired several technical and soft skills along the way. 
  1. How to deal with multiple data formats
  2. How to work on different Python libraries, particularly Scikit-learn to train ML model. 
  3. How to use Github to control version while working with Jupyter Notebook.
  4. How to communicate effectively and practice public presentation

## 📄 License

TODO List is [MIT licensed](./LICENSE).