# Movie-Recommendation-by-Collaborative-Filtering-for-Netflix-Data

Flow of this document:

1) Introduction

2) Approach used 

3) Description of the uploaded files

4) Conclusion


## Introduction
Due to the predominance of the internet, more and more data is collected every day, so people now have too many options to choose from, so we are moving from the age of information to the age of recommendation. In the past, the number of movies that can be placed in a store was depended on the size of that store. Whereas, in the present days, the internet allows people to access abundant resources online. For instance, Netflix and Amazon has huge collection of movies. This has resulted in a new problem as people has a hard time selecting the items they want to see. This is where the recommender system comes in.

Big data is the driving force behind Recommendation systems. A typical Recommendation system cannot do its job without sufficient data and big data supplies plenty of user data such as past purchases, browsing history, and feedback for the Recommendation systems to provide relevant and effective recommendations. Hence, data engineering approaches are useful to address these problems.

The goal of this project is to analyze the NETFLIX data using SPARK and based on the outcomes of this analysis, develop a feasible and efficient implementation of the collaborative filtering algorithm in PYSPARK. In this project, around 100,000 movie ratings are predicted for users in a subset of the original NETFLIX data issued for the NETFLIX Prize. This challenge aimed at substantially improving the accuracy of predictions about how much someone is going to enjoy a movie based on their movie preferences


## Approach
The project follows the below approaches:

•	Similarity measure CORRELATION

•	Prediction method weighted

•	User-user model 

•	Evaluation- Mean Absolute Error and Root Mean Squared Error

### User-user
In order to make a new recommendation to a user, user-user method roughly tries to identify users with the most similar “interactions profile” (nearest neighbours) to suggest items that are the most popular among these neighbours which are are new to the user. This method is said to be “user-centred” as it represent users based on their interactions with items and evaluate distances between users.


### Evaluation Methods:
There are many evaluation metrics but one of the most popular metric used to evaluate accuracy of predicted ratings are:
1) Mean Absolute Error (MAE)	

2) Root Mean Squared Error (RMSE)

MAE is average of the differences between values predicted by a model or an estimator and the values observed. Meaning, it is the measure of difference between the actual and predicted values.

RMSE is just the square root of MSE. The predicted values can be positive or negative as they under or overestimates the actual value. Squaring the residuals, averaging the squares, and taking the square root gives us the RMSE error. 

## Description of the codes
ProjectReport.pdf  - project report that include the documentation and results

There are 5 codes in the SCR folder :
1) Netflix_problem1

2) Netflix_problem2

3) Netflix_problem3a

4) Netflix_problem3b

5) Netflix_problem3c



