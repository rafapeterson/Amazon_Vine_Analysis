# Amazon_Vine_Analysis
## Overview
In this analysis, the product reviews for the "video games" category on Amazon were extracted in order to review the difference in rating of 5-star reviews based on whether they were a part of the Amazon Vine program (paid for review) or not. In order to further drill down the analysis, the results were first filtered to where the total_votes count was equal to or greater than 20. This was to pick reviews that would have been marked as "helpful." To further drill down the data, another filter was applied to the data- this time, we drilled down to reviews where the number of helpful_votes divided by total_votes was equal to or greater than 50%.
## Results
From these results: <br>
**Total Reviews:** ![image](https://user-images.githubusercontent.com/13009587/148609179-3277bd9b-61ca-49c9-922a-ed41358bb746.png)
The total number of reviews was **40,565** <br>
The total number of Vine reviews was **94**, and the total number of non-Vine reviews was **40,471**![image](https://user-images.githubusercontent.com/13009587/148609537-dad5b56d-4f27-45f2-80e9-430be813fcdb.png)<br>
<br>
To further evaluate the data, it was separated into the number of 5-star reviews, which was **15,711** reviews.![image](https://user-images.githubusercontent.com/13009587/148609640-3b5ee0fa-ff88-44da-89c2-228f94f0f7b0.png)
. Of those, **48** were Vine reviews, while **15,663** were not Vine reviews.![image](https://user-images.githubusercontent.com/13009587/148609830-8e692994-92d5-4aae-93dc-d2c75e90f1e1.png)
<br>
<br>
Percentage-wise, ~51% of Vine reviews were 5-star, while ~38.7% of non-Vine reviews were 5-stars.
![image](https://user-images.githubusercontent.com/13009587/148609990-010ce2a8-1dc6-4e09-a8d6-465c48c3b43b.png)


## Summary
Based on this data, the vast majority of reviews were NOT part of the Vine program. There exists a positivity bias with Vine reviews(51%), however there is still a substantial number of 5-star organic (or non-Vine) reviews(38,.7%). To support the theory of a positivity bias, I would run an analysis that broke down the number of vine reviews for each star-level (1-5), and run the same analysis for non-Vine reviews. 
