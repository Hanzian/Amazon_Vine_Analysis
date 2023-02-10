# Amazon Vine Analysis

## Overview of Project
For this week's project, we will be looking at Big Data and Cloud Services. Big Data is data that has more variety and is generating at high volumes quickly. Spark has become the leading technology for handling big data. This will allow us to process and analyze data quickly and at a massive scale. We will also be using Google Colab since it is hosted in the cloud. This makes it easier to read datasets that are from the cloud as well. Our data will be pulled from Amazon's Simple Storage Service (S3).

### Purpose
The purpose of this week's project is help businesses optimize their marketing efforts at BigMarket. The project will be to analyze Amazon reviews written by members of the paid Amazon Vine program. Amazon Vine members are delivered products and are required to publish a review. . We will then be using PySpark to analyze our data to determine if there is any bias toward favorable Vine member reviews. 

### Requirements
To run the Jupyter Notebook for this project, you will need the following:

Python 3.x
Jupyter Notebook
Pandas library
Numpy library

## Delivrable 1

We will be using PySpark to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.

### Results
#### Customers_df
![customers_df](https://github.com/Hanzian/Amazon_Vine_Analysis/blob/main/Images/Customers_df.png)

#### Poducts_df
![products_df](https://github.com/Hanzian/Amazon_Vine_Analysis/blob/main/Images/Products_df.png)

#### Review_id_df
![review_id_df](https://github.com/Hanzian/Amazon_Vine_Analysis/blob/main/Images/Review_id_df.png)

#### Vine_df
![vine_df](https://github.com/Hanzian/Amazon_Vine_Analysis/blob/main/Images/Vine_df.png)


## Results
In order for us to determine if there was a bias of Vine Reviews, we created a dataframe from our Amazon review data that had 6 columns:
1. review_id: The unique ID of the review.
2. star_rating: The 1-5 star rating of the review.
3. helpful_votes: Number of helpful votes.
4. total_votes: Number of total votes the review received.
5. vine: Review was written as part of the Vine program.
6. verified_purchase: The review is on a verified purchase.
