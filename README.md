# Amazon_Vine_Analysis
## Project Overview
#### With our choice of PySpark, Pandas, or SQL, this project tasked us with determining if any bias towards favorable reviews exists from Vine members in our choice dataset. This analysis utilizes the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. 

## Resources
- Data Source: (https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz)
- Software: Google Colab Notebook, PostgreSQL, pgAdmin 4, AWS

## Results

<p align="center">
<img width="600" alt="Screen Shot 2022-04-12 at 3 55 36 PM" src="https://user-images.githubusercontent.com/96352751/163043122-fff63ce0-d943-46ca-aecd-f87244896eb0.png">

<img width="600" alt="Screen Shot 2022-04-12 at 3 56 46 PM" src="https://user-images.githubusercontent.com/96352751/163043287-ca019be9-59ac-4794-b69f-fa3381642c03.png">
  
<img width="600" alt="Screen Shot 2022-04-12 at 4 00 17 PM" src="https://user-images.githubusercontent.com/96352751/163043927-1a5e9065-1a5c-4b49-ae2d-1dd4d86f7b04.png">

 <img width="600" alt="Screen Shot 2022-04-12 at 4 01 39 PM" src="https://user-images.githubusercontent.com/96352751/163044038-af377cda-4411-42bc-a127-f45372061b65.png">

<img width="600" alt="Screen Shot 2022-04-12 at 4 04 12 PM" src="https://user-images.githubusercontent.com/96352751/163044424-3bfcc1da-f7be-4759-9718-ed5ead8585a5.png">

<img width="600" alt="Screen Shot 2022-04-12 at 4 04 50 PM" src="https://user-images.githubusercontent.com/96352751/163044548-e4c18f0c-adcb-4e79-835f-94c5e16f600a.png">
</p>

## Summary
#### Our analysis concluded that 51% of the reviews in the Vine program were 5 star reviews whereas the percentage of non-Vine reviews was only 39%. This indicates that a positivity bias exists for reviews in the Vine program. To expand on our results, we can include other statistical measures such as the mean, median, and mode of the star rating for the Vine and non-Vine reviews.
