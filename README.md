## Amazon_Vine_Analysis
### Module 17 Challenge


#### Project Overview
Project to help the Amazon Vine program analyze written reviews by their paid members. The Amazon Vine Program is a service for manufacturers and publishers to recieve 
reviews for their products. A company like SellBy that will pay a small fee to Amazon and provide products to Amazon Vine members who are required to publish a 
review. Using the picked dataset and the skills learned with Pyspark to perform and ETL process to extract and transform the data, connecting to an AWS RDS instance, and 
loading the trasnformed data into pgAdmin. Then it will be determined if there is any bias towards favorable reviews from the Vine members in the dataset.


### Deliverables
1. Perform an ETL on Amazon Product Reviews- functions > groupby() agg()
2. Determine Bias of Vine Reviews  > vine == 'Y' vine == 'N'
3. Written Report of Analysis (README)


### Summary
The conclusion that can be made from this dataset with the functions used, we can determine that there is a bias for the reviews related to the Vine program. It appears 
that these paid reviews are less likely to be helpful and more about the money made from the Vine program. From this I would recommend the program be looked at more 
thoroughly. In order to analyze tyhis dataset further to support this statement we can filter it further by including verified purchases to add more reliability to our 
findingds.



