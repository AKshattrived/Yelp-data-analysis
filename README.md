# Analysis of Arizona Businesses using Yelp Dataset

### Introduction
The goal of this project is to perform analysis of Yelp data to derive insights about local businesses in Arizona. Yelp’s dataset includes information about businesses, reviews, check-ins, tips, and users. For Milestone 1, the focus is on Business Level Analysis, utilizing all the JSON files in the Yelp’s dataset. This milestone involves filtering the data for Arizona businesses and performing analysis of key attributes such as ratings, reviews, categories, locations, and operational hours. Milestone 2 shifts the perspective to a user-centric analysis. The goal is to extract meaningful
insights about user activities and engagement patterns.

### Approach
This project includes Jupyter Notebook files, which contains the code for user-level and business-level analysis based on distinct queries applied to the datasets. The analysis leverages the PySpark library to execute these queries efficiently.

All five JSON files—business, checkin, tip, review, and user—were loaded into PySpark DataFrames and subsequently converted into PySpark SQL TempViews with the same names. The findings from the queries are summarized below.
