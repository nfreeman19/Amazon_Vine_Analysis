# Amazon_Vine_Analysis

## Overview of the analysis of the Vine program:

We were asked to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

We needed to pick one of fifty datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. We used SQL to determine if there is any bias toward favorable reviews from Vine members. 

## Results:

- How many reviews were paid? 94 How many reviews were unpaid? 40471
- How many paid 5 Star reviews were there? 48 How many unpaid 5 Star reviews were there? 15,663
- What was the percentage of paid 5 Star reviews? 51.06% What was the percentage of unpaid 5 Star reviews? 38.71%

Results below:

![myTest](https://github.com/nfreeman19/Amazon_Vine_Analysis/blob/main/Screen%20Shot%202021-10-24%20at%208.22.42%20AM.png)
![myTest](https://github.com/nfreeman19/Amazon_Vine_Analysis/blob/main/Screen%20Shot%202021-10-24%20at%208.34.50%20AM.png)

## Summary:

There are more unpaid reviews than paid reviews as far as this particular dataset. 
However the percentage of the reviews in the Vine program were 5 stars reviews were higher than non-vine reviews. This would show a bias in favor of the Vine program.
