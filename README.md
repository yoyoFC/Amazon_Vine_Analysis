# Amazon Vine Analysis

## Overview of the analysis

The purpose of this work is to analyze the results from the Amazon Vine program based on a random dataset. The Sellby company pays a fee to receive reviews of the products they sell. The goal of this document is to determine if there is any bias toward favorable reviews from Vine members.
The data source selected for this analysis are the reviews for [baby products](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Baby_v1_00.tsv.gz)

## Results

After organizing the raw data from Amazon and storing the tables in a database cloud service, we proceeded to calculate the total number of reviews, the five-star reviews, and the percentage of each group labeled as "VINE GROUP" and "NON VINE GROUP".

- How many Vine reviews and non-Vine reviews were there? The data set contains a total of 1,752,932 samples/reviews.
- How many reviews were 5 start on each group?
  - VINE GROUP 
  - NON VINE GROUP 
- What percentage of Vine reviews were 5 starts and what percentage of non-Vine reviews were 5 starts?
  - VINE GROUP
  - NON VINE GROUP
  - 
## Summary 

- We can estimate that the difference between the five star reviews from both groups is close to 4% (43.63% - 47.95%). Based on this result, we can conclude that there is a slight margin of error between both groups, but it is not enough to consider it bias toward favorable reviews from the Vine group.

-Something additional to keep in mind is the distribution of "star review" for each group. The following table shows the results for two queries counting the number of reviews by numeric ranking. The top ratings (3-4-5) have the highest proportion on both sides. This result can support our conclusion about the tendency to show similar behavior in both groups.
