# Amazon_Vine_Analysis

## Overview of Amazon_Vine_Analysis

####  Using the dataset for PC collected from Amazon and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Use PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset.

## Results

- **How many Vine reviews and non-Vine reviews were there?**
	* The total number of Vine reviews was 1775.
	* The total number of non-Vine reviews was 77370.
  
![](https://github.com/princetonduarte/Amazon_Vine_Analysis/blob/main/Vine_reviews_and_non.png)

- **How many Vine reviews werer 5 stars? How many non-Vine reviews were 5 stars?**
	* The number of 5-star Vine reviews was 783.
	* The number of 5-star non-Vine reviews was 35944.
  
![](https://github.com/princetonduarte/Amazon_Vine_Analysis/blob/main/Vine_5_stars.png)	


- **What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?**
	* The percentage of 5-star Vine reviews was 0.44.
	* The percentage of 5-star non-Vine reviews was 0.46.
  
![](https://github.com/princetonduarte/Amazon_Vine_Analysis/blob/main/Percentage_5_stars.png)	

## Summary
The percentages of Vine and non-Vine 5-star reviews are close. Looking at the results there does not appear to be any bias for the revies in the Vine program.

Performing a similar test using the 4-star reviews the percentage of reviews were 0.34 and the non-Vine was at 0.16. So this would indicate a biais for 4-star reviews in the Vine program.
