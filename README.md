# Amazon Vine Analysis

## Overview of the analysis

The purpose of this work is to analyze the results from the Amazon Vine program based on a random dataset. The Sellby company pays a fee to receive reviews of the products they sell. The goal of this document is to determine if there is any bias toward favorable reviews from Vine members.
The data source selected for this analysis are the reviews for [baby products](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Baby_v1_00.tsv.gz)

## Results

After organizing the raw data from Amazon and storing the tables in a database cloud service, we proceeded to calculate the total number of reviews, the five-star reviews, and the percentage of each group labeled as "VINE GROUP" and "NON VINE GROUP".

<p align="center"><img src="https://user-images.githubusercontent.com/88695570/145751263-068d7962-2d9c-4e18-b043-3707128a2fc6.png">

- How many Vine reviews and non-Vine reviews were there? The data set contains a total of 1,752,932 samples/reviews.
- How many reviews were 5 start and what is the percentage on each group?
  - VINE GROUP 
  <p align="center"><img src="https://user-images.githubusercontent.com/88695570/145751315-7bfc5074-3685-4eed-96d8-39796ca4e0ec.png">
  
  - NON VINE GROUP 
  <p align="center"><img src="https://user-images.githubusercontent.com/88695570/145751327-e4294cb3-7ebc-4f3b-b88f-ea6e42e7a26b.png">

## Summary 

- We can estimate that the difference between the five star reviews from both groups is close to 4% (43.63% - 47.95%). Based on this result, we can conclude that there is a slight margin of error between both groups, but it is not enough to consider it bias toward favorable reviews from the Vine group.

- Something additional to keep in mind is the distribution of "star review" for each group. The following table shows the results for two queries counting the number of reviews by numeric ranking. The top ratings (3-4-5) have the highest proportion on both sides. This result can support our conclusion about the tendency to show similar behavior in both groups.
 
<p align="center"><img src="https://user-images.githubusercontent.com/88695570/145752447-59c3ce58-d27f-4d67-9e08-8efab540c16a.png">

<p align="center"><img src="https://user-images.githubusercontent.com/88695570/145752310-af4b05d4-16db-4bcb-914d-fb099b832451.png">

    
    
