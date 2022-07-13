# Amazon_Vine_Analysis

**Overview**

The overview of this analysis was to grab data from the amazon services and in this case we grabbed reviews from amazon products. We then wanted to create a dataframe in SQL that would allow us to match the data from the amazon services to better analyze and interpret the data. After extracting the data from amazon and loading it into SQL we then tranformed the data with PySpark and determined the bias of reviews to see if whther or not having paid vine makes a difference in the rating of 5 stars or not. We are making an analysis from a database containing amazon reviews. We first shorteneed the databse to get rid of any extra data that is not needed. By shortentning the databse to only votes containing more than 20 casts we then continue our analysis on this newly finished databse. We then created new databses containing all the votes that either were a part of the vione program, being paid or unpaid. We then found the total number of reviews, the total number of 5 star reviews, and the percentage of 5 star reviews to whether or not the review was a part of the vine program. 

**Results**

After doing the analysis we found that there were around 613 total votes for paid votes(vine) and about 65000 votes not paid (not Vine).

There were 222 vine reviews that were 5 stars and about 30500 non vine reviews that were 5 stars. 

the Percentage of vine reviews that were 5 stars was about 0.7% compared to the non-vine reviews that were about 99%

**Summary**

All in all for my analysis I do not see any real positivity bias for the reviews that were in the vine program. Having a paid vinre review did not serve any help in determining whether or not it is worth the reviews. From the number I recieved there was no real distinguishiong factor that led to a result that states it would be better for paid vine reviews. Another analysis we could do would be to find the reviews per product title or catagory and dive deeper into the review process with vine or not vibe reviews.
