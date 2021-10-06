# Amazon_Vine_Analysis
Module 16 Big Data

## Overview
This project analyizes the Amazon reviews written by members of the paid Amazon Vine program for bias toward favorable reviews from Vine members. The data are extracted using PySpark, then loaded into pgAdmin via an AWS RDS instance. This data is shoe reviews

## Results
How many Vine reviews and non-Vine reviews were there?
&nbsp;&nbsp;&nbsp;&nbsp;![alt text](https://github.com/sarifrey/Amazon_Vine_Analysis/blob/main/resources/paid_5star.jpg)

* There are 22 Vine reviews of show

&nbsp;&nbsp;&nbsp;&nbsp;![alt text](https://github.com/sarifrey/Amazon_Vine_Analysis/blob/main/resources/upaid_5star.jpg)

There are 29,987 non-Vine reviews of shows

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

&nbsp;&nbsp;&nbsp;&nbsp;![alt text](https://github.com/sarifrey/Amazon_Vine_Analysis/blob/main/resources/paid_5star_reviews.jpg)
There were 13 five-star Vine reviews.

&nbsp;&nbsp;&nbsp;&nbsp;![alt text](https://github.com/sarifrey/Amazon_Vine_Analysis/blob/main/resources/upaid_total_5star.jpg)

There were 14,475 five-star non-Vine reviews.

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

&nbsp;&nbsp;&nbsp;&nbsp;![alt text](https://github.com/sarifrey/Amazon_Vine_Analysis/blob/main/resources/paid_5star_percentage.jpg)

59 percent of the Vine reviews for shoes were five-star.

&nbsp;&nbsp;&nbsp;&nbsp;![alt text](https://github.com/sarifrey/Amazon_Vine_Analysis/blob/main/resources/upaid_percentage.jpg)

54 precent of the non-Vine reviews for shoes were five-star.

## Summary

Given the low number of paid Vine reviews and the low number of 5 star reviews, there is not a positive bias in the reviews by paid Vine users. There are more positive reviews for non-Vine reviews, however, that does mean there is a positive bias. The non-Vine reviews gain nothing for giving a positive review. 

Another analysis that could be done is analizing the 5 star reviews in the entire dataset - combining Vine and non-Vine - and then calculating the overall percentage of 5 star reviews in the entire dataset. 
