# AMazon_challenge

Background
Since your work with Jennifer on the SellBy project was so successful, you’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

DATA FORMAT Tab ('\t') separated text file, without quote or escape characters. First line in each file is header; 1 line corresponds to 1 record.

Video Games https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz

Results
ETL Process data using PySpark
Create DataFrames to match production-ready tables from two big Amazon customer review datasets. Amazon_Reviews_ETL.ipynb

Statistical Analysis to find bias
Analyze whether reviews from Amazon's Vine program are trustworthy and free of bias. Vine_Review_Analysis.ipynb
