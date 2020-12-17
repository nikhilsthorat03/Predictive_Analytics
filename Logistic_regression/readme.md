HOMEWORK 2
Nikhil Sanjay Thorat
Spring 2020 ALY 6020
Predictive Analytics Instructor: Prof. Marco Montes de Oca
Introduction to Logistic regression:
Logistic regression is the most common method used for the classification of two different classes in
Machine learning. It is used to solve a binary classification problem. The classification is done using
one dependent variable and multiple independent variables. The outcome of this type of regression
can only give two types of classes. The model gives a constant output, unlike linear regression which
gives continuous output. The estimation of Logistic regression is done using the Maximum Likelihood
Estimation (MLE) approach.

Types of Logistic regression:
1) Binary Logistic regression: Only two outcomes are possible from the target variable.
2) Multinomial Logistic regression: Three or more than three outcomes are possible.
3) Ordinal Logistic regression: Three or more than three ordinal categories are present.

Steps involved in performing Logistic regression:
1) Model building in Scikit-learn
2) Loading the dataset
3) Selecting the features
4) Splitting the given dataset
5) Developing the model for prediction
6) Evaluating the model for calculating the accuracy
7) Plotting the graphs (ROC curve)
8) Getting the AUC score

Homework Outline: The goal of the assignment is to classify two different types of actor classes which
are male and female. To compute this classification the image is converted into 1D series and using
the distance the outline was calculated. A logistic regression model is built to get the accuracy of the
classification results. As the dataset is huge it is a better option to use ROC to get the accuracy. In
terms of the confusion matrix, the accuracy is not perfect all the time if the dataset is having
imbalances of classes.
Dataset description: The given dataset was downloaded from the link mentioned below:
http://www.timeseriesclassification.com/description.php?Dataset=Yoga
The dataset is divided into two different parts Train and Test and the target variable is in the form of
(1,2). The rest of the data provided is in the form of time series.

Results and Conclusion:
In problem 1, with the actual dataset, the logistic regression model was trained and the accuracy
obtained was around 66.70% and the AUC score 0.69.
In problem 2, from the dataset 68 instances were removed and the removed instances were
concatenated with the class 2 instances and the logistic regression model was trained with the ration
of 69/300. The accuracy obtained was 60.83% and the AUC score was 0.69. We can observe that
there's a drop in the accuracy of the model when the values are dropped and concatenated.
In problem 3, even more values were dropped and concatenated from class 2 instances the dataset
with the ratio of 34/300. The accuracy obtained was 57.13% and the AUC score was 0.65. As the
number of instances dropped was more the accuracy was even reduced more.
We can see that the actual dataset is already having some imbalances due to which the accuracy is
low. As we drop and concatenated the values the accuracy is getting even more reduced which is
evident from the models built-in problems 2 and 3 respectively.
