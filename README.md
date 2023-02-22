# Amazon_Vine_Analysis

# I Learned

I be able to:

Define big data and describe the challenges associated with it.
Define Hadoop and name the main elements of its ecosystem.
Explain how MapReduce processes data.
Define Spark and explain how it processes data.
Describe how NLP collects and analyzes text data.
Explain how to use AWS Simple Storage Service (S3) and relational databases for basic cloud storage.
Complete an analysis of an Amazon customer review.

_________________________________________________________________________________________________________________________________________________________________________

# Results

With the information obtained in our developed control, a filter was made in different tables to have an order in the total 5-star reviews and finally obtain the result of the percentage of 5 stars for paid and unpaid Vine.

The data was prepared before any filtering moves were made for this analysis, the data used was selected using only those that have 50% useful votes out of the total votes (since they are more reliable) and two tables were also obtained one for the paid user and another for the non-paid user to facilitate the filtering of information.

# Total Vine and Non-Vine Reviews

From the prepared data, the next step was to count the rows in each table, since all the filtering was done previously, separating both users using the "vine" column ('Y' for paid user and 'N' for not pay) . So the total number of revisions for the paid service is: 94 and for the unpaid service is: 40471.

![image](https://github.com/RodrigoCR25/Amazon_Vine_Analysis/blob/main/Total_Rev_Vine.png)

![image](https://github.com/RodrigoCR25/Amazon_Vine_Analysis/blob/main/Total_Rev_not_Vine.png)

![image](https://github.com/RodrigoCR25/Amazon_Vine_Analysis/blob/main/Total_Rev_Vine_df.png)

![image](https://github.com/RodrigoCR25/Amazon_Vine_Analysis/blob/main/Five_Star_Vine.png)

5 star Vine and non-Vine reviews

For the 5 star reviews for both paid and unpaid it was necessary to create another two tables by filtering the data where the column "star_rating" was equal to 5, so a table was created from each. 

![image](https://github.com/RodrigoCR25/Amazon_Vine_Analysis/blob/main/Porcentage.png)

The total number of 5 star reviews for paid service is: 48 and for the unpaid service is: 15663.

_______________________________________________________________________________________________________________________________________________________________________

# Summary

Summary
Looking at the results, there is a possible positive bias towards paid users on Amazon Vine, as there are more unpaid reviews overall, but ultimately the highest percentage of 5 stars went to paid ones ( 51% paid and 39% unpaid). This could be a first observation to give a conclusion. But if we carry out this analysis in this way, we would fall into an error since more information is needed.

Therefore, the following proposals are proposed:

One option is to develop this same analysis proposal the same analysis that we did, but for different data sets. In this analysis, it was done for video games, it could be done for clothing products or, where appropriate, accessories for children such as toys, which would allow us to have a broader panorama of product reviews.

Perhaps they behave the same or perhaps present the same tendency.

The second option is to focus a little more on this data set and look at the majority of products that shipped to paid and non-paid users, maybe for a period of time the products were actually better for paid. Thus allowing to eliminate the probability that it is something seasonal and also a much more detailed study on the actual products would be nice (although it would take more time) to confirm the 5 stars. review.
