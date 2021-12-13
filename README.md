# Amazon Vine Analysis

## Overview of the analysis

The purpose of this work is to analyze the results from the Amazon Vine program based on a random dataset. The Sellby company pays a fee to receive reviews of the products they sell. The goal of this document is to determine if there is any bias toward favorable reviews from Vine members.
The data source selected for this analysis are the reviews for [baby products](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Baby_v1_00.tsv.gz)

## Results

After organize the raw data from Amazon and store the tables in a database cloud service, we proceeded to calculate the total number , the 5 start reviews and the precentage for each group labeled as "VINE GROUP" and "NON VINE GROUP".

- How many Vine reviews and non-Vine reviews were there? The data set contains a total of 1,752,932 samples/reviews.
- How many reviews were 5 start on each group?
  - VINE GROUP 
  - NON VINE GROUP 
- What percentage of Vine reviews were 5 starts and what percentage of non-Vine reviews were 5 starts?
  - VINE GROUP
  - NON VINE GROUP
  - 
## Summary 

- Considering the percentage of the 5 star reviews between both groups, we can estimate than the difference is close  around 4% (43.63% - 47.95%). Based on this result, we can conclude that there is a slight margin of error but not enough to consider that there maybe a bias toward favorable reviews from the Vine group.
- 
