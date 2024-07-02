# Restaurant Ratings Analysis

## Table of Content

* [Case Study](#case-study)
* [Dataset Description](#dataset-description)
* [ER Diagram](#er-diagram)
* [Data Cleaning](#data-cleaning)
* [Data Analysis](#data-analysis)
* [Dashboard](#dashboard)

## Case Study
Restaurant ratings in Mexico by real consumers from 2012, including additional information about each restaurant and their cuisines, and each consumer and their preferences.

## Dataset Description
Our data set consists of the following observations which include:

#### Consumers
- **Consumer_ID** - Unique identifier for each consumer
- **City** - City where the consumer lives
- **State** - State where the consumer lives
- **Country** - Country where the consumer lives
- **Latitude** - Latitude where the consumer lives
- **Longitude** - Longitude where the consumer lives
- **Smoker** - Whether the consumer smokes or not
- **Drink_Level** - Whether the consumer is an abstemious, casual, or social drinker
- **Transportation_Method** - Whether the consumer transports on foot, by public transport, or by car
- **Marital_Status** - The consumer's marital status (single or married)
- **Children** - Whether the consumer has dependent/independent children or kids
- **Age** - The consumer's age
- **Occupation** - The consumer's occupation (student, employed, or unemployed)
- **Budget** - The consumer's budget (low, medium, high)

#### Consumer_Preferences
- **Consumer_ID** - Unique identifier for each consumer
- **Preferred_Cuisine** - Types of food the consumer prefers

#### Ratings
- **Consumer_ID** - Unique identifier for each consumer
- **Restaurant_ID** -  Unique identifier for each restaurant
- **Overall_Rating** - The overall rating by the consumer for the restaurant (0=Unsatisfactory, 1=Satisfactory, 2=Highly Satisfactory)
- **Food_Rating** - The food's rating by the consumer for the restaurant (0=Unsatisfactory, 1=Satisfactory, 2=Highly Satisfactory)
- **Service_Rating** - The service rating by the consumer for the restaurant (0=Unsatisfactory, 1=Satisfactory, 2=Highly Satisfactory)

#### Restaurants
- **Restaurant_ID** - Unique identifier for each restaurant
- **Restaurant_Name** - The name of the restaurant
- **Cuisine_Type** - Type of cuisine the restaurant serves
- **City** - City where the restaurant is located
- **State** - State where the restaurant is located
- **Country** - Country where the restaurant is located
- **Latitude** - Latitude where the restaurant is located
- **Longitude** - Longitude where the restaurant is located

#### Restaurant_Cuisines
- **Restaurant_ID** - Unique identifier for each restaurant
- **Cuisine_Type** - Types of cuisine the restaurant serves

## ER Diagram
![ER Diagram](https://github.com/Daksh503/Restaurant-Ratings-Analysis/raw/main/ER%20Diagram.png)

## Data Cleaning
Data cleaning involved handling missing values, removing duplicates, and correcting inconsistent data entries. 

## Data Analysis
Data analysis included descriptive statistics, data visualizations, and insights derived from the dataset. Key analysis points included:
- Consumer demographics
- Restaurant ratings distribution
- Correlation between consumer preferences and restaurant ratings

## Dashboard
![Restaurant Ratings Analysis_page-0001](https://github.com/Daksh503/Restaurant-Ratings-Analysis/raw/main/Dashboard/Restaurant%20Ratings%20Analysis_page-0001.png)
![Restaurant Ratings Analysis_page-0002](https://github.com/Daksh503/Restaurant-Ratings-Analysis/raw/main/Dashboard/Restaurant%20Ratings%20Analysis_page-0002.png)
![Restaurant Ratings Analysis_page-0003](https://github.com/Daksh503/Restaurant-Ratings-Analysis/raw/main/Dashboard/Restaurant%20Ratings%20Analysis_page-0003.png)
![Restaurant Ratings Analysis_page-0004](https://github.com/Daksh503/Restaurant-Ratings-Analysis/raw/main/Dashboard/Restaurant%20Ratings%20Analysis_page-0004.png)
![Restaurant Ratings Analysis_page-0005](https://github.com/Daksh503/Restaurant-Ratings-Analysis/raw/main/Dashboard/Restaurant%20Ratings%20Analysis_page-0005.png)
