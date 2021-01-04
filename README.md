# Amazon_Vine_Analysis

## Overview of the analysis 
The purpose of the analysis is to study Amazon reviews written by people of the paid Amazon Vine program. The Amazon Vine program is a service that provides sellers reviews for their products. Companies like SellBy pay a small amount to Amazon and give products to Amazon Vine members. Then the members publish a review of the product. The reviews of the Vine members will be compared to reviews by non-Vine members to look at trends in ratings in one specific product area. For this project, the chosen dataset is video game reviews.

## Results 
There is a bulleted list that addresses the three questions for unpaid and paid program reviews using bulleted lists and images of DataFrames as support:

### How many Vine reviews and non-Vine reviews were there?
There are only 94 Vine reviews compared to 40471 non-Vine reviews. The non-Vine reviews account for 99.77% of the reviews and demonstrates a very small Vine program for video game reviews.

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
There are 48 five-star Vine reviews compared to 15663 five-star ratings for non-Vine reviewers.

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
The percentage of five-star Vine reviews is 0.31% compared to 99.69% for non-Vine reviews that were five-stars.

## Summary

### State if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement.
There is positivity bias for reviews in the Vine program. 48 out of 94 Vine reviews were five-star ratings which results in 51.06% five-star ratings. Alternatively, the percentage of five-star ratings for non-Vine members is 15663 out of 40471 reviews which results in 38.70%. The percentage of five-star ratings is 12.36 percentage points less than the Vine reviews. One explanation for the high percentage of five-star ratings from Vine reviews is the reviewers desire to remain a Vine reviewer and/or the benefit of receiving free products.

### Provide one additional analysis that you could do with the dataset to support your statement.
My suggestion to confirm positivity bias is to study two additional product reviews in the S3 buckets from Amazon and determine if the same trend exists for other products. The other suggestion is to expand the Vine program and gather more reviews because the percentage of Vine reviews is less than 1% of the total reviews of video games. A larger dataset of Vine reviews would allow more confidence in reporting the percentages of five-star ratings. 
