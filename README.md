# Amazon_Vine_Analysis
Module 16

## Overview of the analysis

Using data collected by Amazon, I decided to analyzing Amazon reviews of books written by members of the paid Amazon Vine program to determine if there is any bias toward favorable reviews from Vine members in your dataset.

## Results

![Counts](https://user-images.githubusercontent.com/84158312/137638025-4a238c57-5f1e-4978-93ad-c392308bd410.png)

- How many Vine reviews and non-Vine reviews were there? 
    As we can see in the Pyspark using the Vine Participated Dataframe, there is only 4,781 reviews versus the 332,395 nonpaid reviews from the count of the unpaid dataframe. I guess people are very passionate about their books.

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
    There were 1,604 reviews that the Vine Program participated go rates by other Amazon reviews as 5 star reviews. Out of the non-Vine reviews, there was 168,800 reviews that gave a 5 star review.

![percentages](https://user-images.githubusercontent.com/84158312/137638059-e83ed22a-8951-40d2-9e11-2529482bba8b.png)

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
    The percentages we calculated using the total sum of all 5 star reviews filter from the helpful votes dataframe, a dataframe that represents the amount of reviews that customers found helpful. The Vine reviews that were 5 stars only accounted for 0.94% of all the 5 star reviews. The remaining 99.05% was from 5 star reviews of unpaid reviewers. 
    I also calculated that the percentage of the Vine reviews that were 5 stars out of all the Vine reviews, which was 34%, whereas out of the unpaid reviews that were 5 stars put of all the unpaid reviews was 51%. So even out of the Vine reviews versus the unpaid reviews, there was less of a percentage of 5 star reviews. 
    
## Summary: 
  
  Based on the analysis, the Vine reviews definetly are not biased. Out of the total amount of 5 star reviews, the paid 5 star reviews do not even amount to 1% of the total 5 star reviews. Also the percentage of Vine reviews that are rated 5 stars out of the total of Vine reviews is only 34%, which is less than the percentage of 5 star reviews for unpaid reviews out of the unpaid reviews, which happens to be 51%. The Vine Reviews are definely not handing out their 5 stars easily. 
