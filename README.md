# Amazon_Vine_Analysis
## Overview
The Amazon Vine Program gives free products to members in exchange for them writing a review about the gifted product. The purpose of this analysis was to examine Amazon product reviews in order to determine if there is a bias for more favorable reviews from members of the Amazon Vine Program. The analysis not only determined if there is a bias from Vine members but also uncovered data that proves the Vine Program may not be worth the cost for many companies.

### Data Background
The dataset analyzed was over book reviews and initially contained over 10 million rows of product reviews. After extracting and filtering the data to what was needed for this analysis, the total number of reviews studied was 114,309. 

![Initial_Reviews](https://user-images.githubusercontent.com/106348899/193359900-5d946e9a-329e-4a6d-9542-b5f4eed9e1ce.png)


The initial question asked specifically about "bias for favorable reviews from Vine Members" so the data was filtered down further and a deeper analysis was done on only the 5-Star rating reviews. This consisted of 51,998 5-Star product reviews.  A comparison was done on the 5-Star ratings from Vine members versus Non-Vine members as well.

## Resources

Amazon Web Services - RDS, pgAdmin, Google Colaboratory, PySpark, SQL     

product data - "https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Books_v1_00.tsv.gz"

## Results

### Vine Reviews (Paid Reviews)

![Vines](https://user-images.githubusercontent.com/106348899/193360693-3218928d-7244-4f1a-bf0d-e8f65349c77a.png)

- Total Number of Vine Reviews - 5,012
- Number of 5-Star Vine Reviews - 2,031
- Percentage of 5-Star Vine Reviews - 3.9%
- Percentage of 5-Star Vine Reviews out of Total Vine Reviews - 40.5%

### Non-Vine Reviews (Unpaid Reviews)

![Non-Vines](https://user-images.githubusercontent.com/106348899/193360866-d72f2391-0f36-43dd-b65c-316a6e463c4f.png)

- Total Number of Non-Vine Reviews - 109,297
- Number of 5-Star Non-Vine Reviews - 49,967
- Percentage of 5-Star Non-Vine Reviews - 96.1%
- Percentage of 5-Star Non-Vine Reviews out of Total Non-Vine Reviews - 45.7%

## Summary
The results of this analysis show that Amazon Vine Members do not show bias in favorable reviews. Out of all of the 5-Star reviews studied (51,998), only 3.9% of those reviews were from Vine Members. This particular dataset did not have many Vine Member reviews to begin with so the percentage of 5-Star Vine Member Reviews to Total Vine Member reviews was calculated. Out of all the Vine reviews for this dataset, only 40.5% were 5-Star Reviews. Just with this insight, companies may want to question if the Vine Program is truly worth the costs.  Of all the 5-Star reviews analyzed, 96.1% were from Non-Vine reviews. Comparing 5-Star Non-Vine reviews to Total Non-Vine reviews from this dataset, 45.7% were 5-Star reviews. In both instances here, Non-Vine reviews trumped Vine reviews. 

### Additional Analysis
Based on the data studied in this analysis companies may want to explore more in depth analyses in order to seriously consider whether the Vine program is truly cost effective. One analysis companies may want to look into is the effectiveness of "helpful votes" in this dataset and how many of those were from Vine members. The previous analysis done on 5-Star reviews did not breakdown and analyze the "helpful votes" category. The helpfulness of the reviews can carry a heavy weight in the opinion of future customers. If the Vine Members are leaving more substantially helpful reviews than Non-Vine Members, this program could very well be worth the cost. 

Another category that needs further analysis is "verification of purchase". For the analysis, it would be benificial to explore how many people were not verified to have purchased the product and still left a review. If a consumer did not really purchase a product, how can they leave a quality review? In conclusion, to further study the influence of Vine member reviews and whether the Amazon Vine Program is cost effective for companies, the "quality" of product reviews needs to be studied further.



