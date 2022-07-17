# Amazon_Vine_Analaysis

## Backround

Amazon Vine programs is a service that allows manufacturers and publisher to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

## Project Overview

In this project, we will access to approximately 50 datasets. Each one contains reviews of specific product. We will pic the one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into PgAdmin.

## Resources

### Data Source:
•	Amazon Vine Reviews Automotive

### Software:
•	Google Colab  
•	PgAdmin
•	AWS 

### Languages:
•	pySpark

## Result
#### •	Vine and non-Vine Reviews
<img width="750" alt="total_reviews" src="https://user-images.githubusercontent.com/77603561/179383505-efac90a5-5380-4b19-b336-c154d15aa839.png">

<img width="505" alt="unpaid_total_reviews" src="https://user-images.githubusercontent.com/77603561/179383506-86e8b29e-72e5-4d64-a2fa-b1c0018d4e7b.png">

#### •	Vine and non-Vine 5 stars Reviews

<img width="507" alt="5star_review" src="https://user-images.githubusercontent.com/77603561/179383385-3c5e4f29-6207-4a5b-8de1-5d4c2d956fea.png">
               
<img width="542" alt="unpaid_total_5_star_reviews" src="https://user-images.githubusercontent.com/77603561/179383409-11355d2c-7914-425f-8167-5def540c0fff.png">

#### •	Percantage of Vine and non-Vine Reviews

<img width="519" alt="percantage" src="https://user-images.githubusercontent.com/77603561/179383478-ecd40d20-bb86-4761-956c-09c277977a5a.png">
<img width="561" alt="upaid_percantage" src="https://user-images.githubusercontent.com/77603561/179383485-217f846b-82ea-4cc1-a463-a6d34af1b847.png">

## Summary
•	In this DataSet, there were more non-Vine reviews than Vine reviews 
##### Vine Reviews : 2088
##### Non-Vine Reviews : 1011346
•	And 5 stars non-Vine reviews is more than the 5 stars vine reviews
##### 5 stars Vine reviews : 958
##### 5 stars non-Vine reviews : 605422
•	As a result we can say amazon vine program is not effective for this product.!
