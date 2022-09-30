# Amazon_Vine_Analysis
## Overview
The Amazon Vine Program gives free products to members in exchange for them writing a review about the gifted product. The purpose of this analysis was to examine Amazon product reviews in order to determine if there is a bias for more favorable reviews from members of the Amazon Vine Program. The analysis not only determined if there is a bias from Vine members but also uncovered data that proves the Vine Program may not be worth the cost for most companies.

### Data Background
The dataset analyzed was over book reviews and initially contained over 10 million rows of product reviews. After extracting and filtering the data to what was needed for this analysis, the total number of reviews studied was 114,309. 

![Initial_Reviews](https://user-images.githubusercontent.com/106348899/193359900-5d946e9a-329e-4a6d-9542-b5f4eed9e1ce.png)


The initial question asked specifically about "bias for favorable reviews from Vine Members" so the data was filtered down further and a deeper analysis was done on only the 5-Star rating reviews. This consisted of 51,998 5-Star product reviews.  A comparison was done on the 5-Star ratings from Vine members versus Non-Vine members as well.

![Filtered_data](https://user-images.githubusercontent.com/106348899/193361443-687f66f6-ab51-403c-a939-98bc6103093d.png)
![Filtered_data2](https://user-images.githubusercontent.com/106348899/193361566-9459b3db-bf34-4500-80a3-c2400c369909.png)


## Resources

Amazon Web Services - RDS, pgAdmin, Google Colaboratory, PySpark, SQL     

product data - "https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Books_v1_00.tsv.gz"

## Results

### Vine Reviews (Paid Reviews)
- Total Number of Vine Reviews - 5,012

![Vines](https://user-images.githubusercontent.com/106348899/193360693-3218928d-7244-4f1a-bf0d-e8f65349c77a.png)

- Number of 5-Star Vine Reviews - 2,031
- Percentage of 5-Star Vine Reviews - 3.9%
- Percentage of 5-Star Vine Reviews out of Total Vine Reviews - 40.5%

### Non-Vine Reviews (Unpaid Reviews)
- Total Number of Non-Vine Reviews - 109,297

![Non-Vines](https://user-images.githubusercontent.com/106348899/193360866-d72f2391-0f36-43dd-b65c-316a6e463c4f.png)


- Number of 5-Star Non-Vine Reviews - 49,967
- Percentage of 5-Star Non-Vine Reviews - 96.1%
- Percentage of 5-Star Non-Vine Reviews out of Total Non-Vine Reviews - 45.7%

## Summary
