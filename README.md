# Amazon Vine Analysis

## Overview of the analysis: Explain the purpose of this analysis.

Analysis od Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

The dataset contains reviews of a specific product for health personal care. It was used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. It was used PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in the Health Personal Care dataset.

## Resources

List of Datasets: https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt
Dataset chosen: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Health_Personal_Care_v1_00.tsv.gz

## Results: Using bulleted lists and images of DataFrames as support, address the following questions:

- How many Vine reviews and non-Vine reviews were there?


- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?


- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?



## Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

The summary states whether or not there is bias, and the results support this statement (2 pt)
An additional analysis is recommended to support the statement (2 pt)
