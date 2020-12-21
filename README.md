# MovieRecommendations

Contributors:
  Rushabh Shah
  

*Abstract*:

In this era of entertainment the companies like Netflix, Amazon prime etc. have provided a huge platform for online streaming of movies, series, documentries and other visual entertainment. The users of these platforms have always been in a dilemma to chose which kind of movies they would like to watch amongst the millions of movies uploaded by these platforms. That is where big data and recommendations have come in for analyzing and providing recommendations to its users which makes it very simple for these users to access the kind of movie acoording to the genres they are interested in. 



*Project Goal*:

The goal of this project is to use image classification that is a supervised learning technique using Convolutional Neural Networks to detect traffic signs. The secondary goal is to use different model to get the best results and achieve an accuracy of 95-99% for the same.



*Motivation:*

This dataset was provided for a Netflix recommendation contest which will provide an opportunity and challenges to learn different types of filtering techniques used in recommendation systems. The project is to be performed on databricks platform using PySpark.



*Methods Applied*

Collaborative Filtering uses aggregation of the past behaviours of all the users and recommends items to users based on the items liked by other users who have likes and dislikes that are similar to the user who is under consideration. This is called user-user based CF.

# Recommendation using ALS.

Alternating Least Squares (ALS) matrix factorization is used to estimate the matrix R (Ratings in this case) which is the product of two matrices that are lower rank X and Y where X * Yt = R.


The method is iterative and in each iteration one of the factor matrices i kept constant and other is solved using least squares. Then the newly solved matrix is held constant and the other factor matrix ix solved.



*Data Summary:*

This dataset is provided by movie lens with 2 files which we will be using for this project which are ratings and movies. The movies.csv has columns which are movieId, title, genre where as the ratings.csv has userId,movieId,ratings and timestamp.

[Data Source and dictonary](https://grouplens.org/datasets/movielens/)

Data consistency: The data seems to be mostly clean with some missing values which have been dropped. There are a few duplicates in the data which have been dropped. 


*Softwares and Packages:*

Project Info:

Contributors: Rushabh Shah.

Languages: PySpark SQL python.

Tools/IDE: Databricks

Duration: December 2020.
