# Amazon Vine Analysis

## Overview of the analysis

Analysis od Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

The dataset contains reviews of a specific product for health personal care. It was used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. It was used PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in the Health Personal Care dataset.

## Resources

* List of Datasets: https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt
* Dataset chosen: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Health_Personal_Care_v1_00.tsv.gz

## Questions addressed

- How many Vine reviews and non-Vine reviews were there?

![Non-Vine Reviews](https://github.com/lindaperez/Amazon_Vine_Analysis/blob/main/non-vine-reviews.png)


- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

![Vine Reviews](https://github.com/lindaperez/Amazon_Vine_Analysis/blob/main/vine_reviews.png)

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

![Totals](https://github.com/lindaperez/Amazon_Vine_Analysis/blob/main/totals.png)

## Summary:  

* There is no positivity bias founded for reviews in the Vine program. The percentage of Five stars Reviews for the paid program is less than the percentage of Five Stars received in the non-paid program.

* Could be interesting do the analysis for 4 star and identify if there is a relationship or correlation with the field verified purchase.
