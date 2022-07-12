# Amazon Vine Analysis

## Overview
We were asked to analyze Amazon reviews written by both Amazon Vine program members and non-Vine members to gain a better understanding of how many reviews are generated between these two populations and how helpful the reviews are.


## Results
There were a total of 6,908,145 reviews listed in the dataset we looked at. However, we wanted to be sure we were only considering helpful reviews so we only looked at reviews that had votes above 20, which gave us a total of 96,147 reviews. 

![total reviews](/Images/vine_df.png)
![total helpful](/Images/helpful.png)

- How many Vine reviews and non-Vine reviews were there?<br>
Of the helpful reviews only 2% (n=1,820) were Vine reviews while 98% (n=94,327) were non-Vine reviews.<br>
![vine reviews](/Images/vine_reviews.png)<br>
![non-vine reviews](/Images/non_vine_reviews.png)
- How many Vine reviews were 5 stars?<br>
There were 788 five-star Vine reviews.
![Vine 5 Star Reviews](/Images/vine_5_star.png)
- How many non-Vine reviews were 5 stars?<br>
There were 37,602 five-star non-Vine reviews.
![Non-Vine 5 Star Reviews](/Images/non_vine_5_star.png)
- What percentage of Vine reviews were 5 stars?<br>
43.29% of Vine reviews had 5 stars.
- What percentage of non-Vine reviews were 5 stars?
39.86% of non-Vine reviews has 5 stars
![Ratings](/Images/ratings.png)



## Summary

The results of this analysis seem to show that there is not bias in Vine reviews vs. non-Vine reviews since the precetnage of 5 star reviews are within 3% points (40% v. 43%). At first glance this would say that both reviews tend to get roughly the same rating so there is no bias from the Vine users who are given products to review compared to a normal consumer. 


What we have not done here is run significance testing to see if the difference in percentage of reviews were 5 stars is statistically significant. Since the populations between Vine and non-Vine reviews is so large it would be worth looking further into this. So, while the Vine reviews had a higher percentage of 5 star ratings (43%) compared to the non-Vine reviews (40%) we cannot currently tell if this is statistically significant or not. We should run this test to better understand our results. 

In order to continue or analysis to see if there is any bias in the Vine reviews we could look at the relationship between 5 star ratings and helpful votes. We could run the same analysis as above, but only on 5 star ratings that have helpful votes above a certain threshold (say 5+ helpful votes). This would remove 5 star ratings that were possibly given without the review being marked as helpful. 


