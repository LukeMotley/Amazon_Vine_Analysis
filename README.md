# Amazon_Vine_Analysis

## Overview
In this project, I analyze the Amazon Vine program and determine whether there is a bias that favors Vine member giving higher review products. I used Pyshark to create the ETL process of extracting the data, transforming it by filtering through the data for particular specifications, and then loading it to a database on a AWS server.

## Results

Vine Reviews: **94**

Non-Vine Reviews: **40471**

Vine Reviews with 5 stars: **48**

Non-Vine Reviews with 5 stars: **15663**

What percentage of Vine reviews were 5 stars? **51.063%**

What percentage of non-Vine reviews were 5 stars? **38.701%**

![image](https://user-images.githubusercontent.com/85656361/138714068-4688a34c-90ef-43a2-b271-832ebd3702a5.png)

## Summary

The reviews of those in the Vine Program were given 5 stars 51% of the time, whereas
those not in the Vine Program gave 5 star reviews only 39% of the time. This would suggest that there is a positive bias for reviews of those in the Vine Program. 

More analyzes that could be done are looking for relationships between each groups natural tendency. It would also be possible to analyze 1-4 star ratings and see if there are any noticable clusters or outliers that might sckew the percentages.
