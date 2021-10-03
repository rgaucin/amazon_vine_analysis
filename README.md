# Amazon Vine Analysis

## Overview

The purpose of this analysis is to examine the biases in product reviews of Amazon Vine members. Music product review data from Amazon Vine members and non-members was compared to determine if members have a tendency to write more favorable reivews than non-members.

The raw data can be found [here](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Music_v1_00.tsv.gz).

## Results

The review data was filtered such that each review had at least 20 user votes, and at least 50% of those votes labeled the review as helpful. The resulting data provided the following insights:

- There was a total of 7 Vine reviews and 10,5979 non-Vine reviews.
- Of these, 0 Vine reviews and 67,580 non-Vine reviews were 5 stars.
- The percentage of reviews that were 5-star were then 0% and 63.77% for members and non-members, respectively.

## Summary

- The analysis shows that there is a significant discrepency between 5-star review percentages, suggesting that there is a tendency of helpful Vine reviews to be less favorable than non-Vine reviews.
- Fur further analysis, a t-test could be applied to determine if there is a statistically significant difference between Vine and non-Vine reviews, though for this dataset, it may be necessary to expand the data used, such as including 'non-helpful' reviews or reviews with fewer than 20 user votes.
