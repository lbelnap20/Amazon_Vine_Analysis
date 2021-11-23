# Amazon_Vine_Analysis

## Overview
This project looks at Amazon reviews of books to determine if there may be any bias from participating in the Amazon Vine project. The dataset referenced : https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Books_v1_02.tsv.gz

## Results 
In order to find the most helpful reviews and to avoid division by zero errors, the dataset was filtered to show only reviews with a total vote count of 20 or greater, and then filtered again to find all reviews that had 50% or more helpful votes. This filtered dataset was then split into two sets, those participating in the Vine program and those that were not. Of these reviews, there were none in the Vine program. Of those not in the Vine program, 60% were 5-star reviews out of a total of 403,807 reviews. There were only two reviews out of the entire unfiltered dataset (3,105,520 reviews) that were part of the Vine program, and only one of those was a 5-star review. 

## Summary 
There does not seem to be a bias in this dataset, given all but one of the 5-star reviews were written by reviewers not in the Vine program. The limitations of analyizing this dataset is that there are only two reviewers out of 3 million in the Vine program, so there is not enough data to make any assumptions about the Vine program as a whole. 
