Introduction to KNN:
KNN is the most used learning algorithm and is considered as the simplest classification algorithm. It
is also called a lazy learning algorithm. The main purpose of this technique is to predict the new data
point from an existing database in which the data points are divided into different parts. KNN comes
under the sci-kit learn algorithms list. Using KNN we can solve classification, regression, and
forecasting problems. It comes under supervised learning algorithms.
Working of KNN algorithm:
1) Loading the train and test data.
2) Taking K-value into consideration.
3) To calculate the distance between the new data point and its neighbors which are close to
that point. In this assignment use of Minkowski distance is done. This distance is a
combination of both Euclidean and Manhattan distance.
Defined as:
4) Finding the smallest distance between the points i.e in ascending order.
5) Averaging the values.
6) Assigning it to a class based on the most frequent class.
To predict values time series analysis is performed.
Homework outline:
The goal of the assignment is to measure the accuracy obtained by KNN on a time series classification
problem. To calculate the distance Minkowski distance is used where we have four P-values and three
K-values which make a combination of total of 12 observations. 
Nikhil Sanjay Thorat Homework 01
Dataset details:
The dataset is extracted from the below-mentioned link:
http://www.timeseriesclassification.com/description.php?Dataset=ECG200
The dataset is related to feature extraction for structural pattern recognition. The two types of
heartbeats present are normal and Myocardial heartbeats. The data is in the form of .txt with two
different files (i.e. Train and test).
Analysis:
To import and use the independent and target variables .txt file was converted into CSV file and values
from those columns were imported. This dataset contains variables that are used to predict two
different types of heartbeats which are normal and Myocardial heartbeats. This is classified using
numbers 1 and -1 respectively which are the target variables. The objective of the homework is to use
the Minkowski distance metric to calculate the KNN classifier model with different combinations of K
and P values.
Calculating confusion matrix:
To calculate the accuracy of the classification confusion matrix is used. The package used for
computing confusion matrix is Sklearn.metrics.

Scikit is a library that is mainly used for machine learning concepts like classification, regression with
which different functions can be imported and implemented. One such function is
KNeighborsClassifier , which is a function used to build models using the KNN classifier algorithm.
But this function allows P values greater than or equal to 1, since P-value = 0.5 is required the belowmentioned error is thrown
In fig.17, For P-value = 0.5 it shows an error stating that P must be greater than one for the
Minkowski metric. 

Results:
As compared to the other models built K=3 and P=1 is having the highest accuracy with a value of
89%.
