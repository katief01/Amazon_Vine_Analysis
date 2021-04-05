# Amazon_Vine_Analysis

## Overview of the analysis of the Vine program:
The purpose of this challenge was to analyze Amazon reviews written by members of the Amazon Vine program to determine if there is any bias toward favorable reviews from Vine members in a sports equipment reviews dataset. I used PySpark to perform the ETL process by extracting the data, transforming the data, and connecting to a database generated through the AWS webserver.

## Results:
### Number of Vine reviews and non-Vine reviews:

Vine reviews = 334 

<img width="663" alt="Vine_Reviews" src="https://user-images.githubusercontent.com/74223626/113526060-0e1afe00-957e-11eb-8339-0f1cca1307ab.png">

Non-Vine reviews = 61,614

<img width="701" alt="Non-Vine_Reviews" src="https://user-images.githubusercontent.com/74223626/113526074-1c691a00-957e-11eb-8867-958f10c163d9.png">

### Number of Vine and non-Vine reviews with 5 stars:

5-star Vine reviews = 22,775

<img width="578" alt="5_Star_Vine_Reviews" src="https://user-images.githubusercontent.com/74223626/113526103-3efb3300-957e-11eb-9060-97f55e62467d.png">

5-star Non-Vine reviews = 10,029

<img width="583" alt="5_Star_Non-Vine" src="https://user-images.githubusercontent.com/74223626/113526114-4faba900-957e-11eb-9a41-60b4be801939.png">

### Percentage of 5-star Reviews for Paid and Un-Paid members:

<img width="655" alt="Percentage_5" src="https://user-images.githubusercontent.com/74223626/113528897-99e55800-9587-11eb-94f5-7b5d35e81783.png">

## Summary:
After reviewing the dataset of sports equipment reviews, I determined there was no evidence of any positivity bias for reviews in the Vine program. The percentage of 5-star reviews is very similar for the paid reviews(54%) versus the un-paid reviews(52%) as seen in the screenshot above.

