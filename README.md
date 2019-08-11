# Machine-Learning-Algortihms-on-Amazon-Fine-Foods-Reviews

This repository demonstrates the application of multiple Machine Learning Algortims to the Amazon Fine Foods Review Dataset.

-----------------------------------------------------------------------------------------------------------------------------
Description of the Dataset-
Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews.
EDA: https://nycdatascience.com/blog/student-works/amazon-fine-foods-visualization/.
The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.
Number of reviews: 568,454
Number of users: 256,059
Number of products: 74,258
Timespan: Oct 1999 - Oct 2012
Number of Attributes/Columns in data: 10
Attribute Information:
1. Id
2. ProductId - unique identifier for the product
3. UserId - unqiue identifier for the user
4. ProfileName
5. HelpfulnessNumerator - number of users who found the review helpful
6. HelpfulnessDenominator - number of users who indicated whether they found the
review helpful or not
7. Score - rating between 1 and 5
8. Time - timestamp for the review
9. Summary - brief summary of the review
10. Text - text of the review
------------------------------------------------------------------------------------------------------------------------------
Objective-

Given a review, determine whether the review is positive (rating of 4 or 5) or negative (rating of 1 or 2).

Q. How to determine if a review is positive or negative?
A. We could use Score/Rating. A rating of 4 or 5 can be considered as a positive review.A rating of 1 or 2 can be considered as negative one.A review of rating 3 is considered nuetral and such reviews are ignored from our analysis. 
This is an approximate and proxy way of determining the polarity (positivity/negativity) of a review.

------------------------------------------------------------------------------------------------------------------------------

ML Algorithms Demonstarted-
1)TSNE-Used for visualisig the data in lower dimensions.
2)K Nearest Neighbors
3)Support Vector Machines
4)Logistic Regression.
5)Decision Trees.
6)Random Forests and Gradient Boosted Decision Trees
7)Naive Bayes
8)Clustering Algorithm used in UnSupervised settings

------------------------------------------------------------------------------------------------------------------------------
In order to apply the above algorithms the data was first preprocessed using various steps and then the review text was 
vectorized using-\
1)Bag Of Words\
2)TFIDF\
3)Avg Word 2 Vec\
4)TFIDF Weighted Word 2 VEC

The above ML algorithms were applied to all or a combination of the above word vectorizations.

In addition to applying the ML Algotithms Hyperparameter tuning using Grid Search Cv and Randomized Search Cv was also performed to 
find the optimal tunable parameters for each algorithm
