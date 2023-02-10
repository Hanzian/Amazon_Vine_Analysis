# Amazon Vine Analysis

## Overview of Project
For this week's project, we will be looking at Big Data and Cloud Services. Big Data is data that has more variety and is generating at high volumes quickly. Spark has become the leading technology for handling big data. This will allow us to process and analyze data quickly and at a massive scale. We will also be using Google Colab since it is hosted in the cloud. This makes it easier to read datasets that are from the cloud as well. Our data will be pulled from Amazon's Simple Storage Service (S3).

## Purpose
The purpose of this week's project is help businesses optimize their marketing efforts at BigMarket. The project will be to analyze Amazon reviews written by members of the paid Amazon Vine program. Amazon Vine members are delivered products and are required to publish a review. . We will then be using PySpark to analyze our data to determine if there is any bias toward favorable Vine member reviews. 

## Requirements
To run the Jupyter Notebook for this project, you will need the following:

- Python 3.x
- Jupyter Notebook
- Pandas library
- Numpy library

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

## Delivrable 2

### Analysis

The analysis in the Jupyter Notebook includes the following steps:

- Extraction of the Amazon reviews dataset into a Pandas DataFrame.
- Transformation of the dataset to clean and prepare the data for analysis.
- Loading of the cleaned and transformed data into a new DataFrame.
- Analysis of the Vine reviews and non-Vine reviews to understand the differences between the two.
- Calculation of the percentage of 5-star reviews for each group.


### Results

#### Total of Number of Reviews
![total](https://github.com/Hanzian/Amazon_Vine_Analysis/blob/main/Images/Total%20Number%20of%20reviews.png)

## Conclusion
The results of the analysis show that the Amazon Vine program does not have a significant impact on the quality of reviews. The percentage of 5-star reviews is the same for both Vine reviews and non-Vine reviews, with 47.01% of the reviews in each group being 5-star reviews.

## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.



**Hanzian Ngoran**

