# Amazon_Vine_Analysis
## Overview
The purpose of this analysis was to examine Amazon product reviews in order to determine if there is a bias for more favorable reviews from members of the Amazon Vine Program.  The Amazon Vine Program gives free products to members in exchange for them writing a review about the gifted product. The objective of the analysis is to not only determine if there is a bias from Vine members but to also determine if the Vine Program is worth the cost.

### Data Background
The dataset analyzed was over book reviews and initially contained over 10 million rows of product reviews. After extracting and filtering the data to what was need for this analysis the total number of reviews studied was 114,309. 
## Resources

Amazon Web Services - RDS, pgAdmin, Google Colaboratory, PySpark, SQL
product data - "https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Books_v1_00.tsv.gz"

## Results

### Vine Reviews (Paid Reviews)
- Total Number of Vine Reviews - 5,012
- Number of 5-Star Vine Reviews - 2,031
- Percentage of 5-Star Vine Reviews - 3.9%

### Non-Vine Reviews (Unpaid Reviews)
- Total Number of Non-Vine Reviews - 109,297
- Number of 5-Star Non-Vine Reviews - 49,967
- Percentage of 5-Star Non-Vine Reviews - 96.1%

## Summary
