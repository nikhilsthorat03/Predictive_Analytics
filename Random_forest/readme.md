HOMEWORK 3
Nikhil Sanjay Thorat
Spring 2020 ALY 6020
Predictive Analytics Instructor: Prof. Marco Montes de Oca
Introduction to Random Forest:
Random Forest consist of multiple decision trees. Each decision tree gives predictors which have the
most number of votes. A random operation is performed which creates some trees. The robustness
of the model depends on the number of trees, more the number of trees is the accuracy. The decision
trees are trained with the bagging method.
Bagging method: Bagging method is used to increase the accuracy of the model and is mainly used in
classification and regression problems. It is well defined averaging approach.
Advantages of using Random Forest:
 Using random forest, we can perform regression as well as classification.
It can be used to handle missing values.
 Random forest models can’t be overfitted.
It can also be operated on categorical variables.

Working of Random Forest:
1. Selecting Random samples from the dataset.
2. Developing a decision tree for every sample and obtaining the result.
3. The result will be predicted using the number of votes.
4. The prediction results will be based on the most number of votes.
Homework Outline: The goal of the assignment is to classify how perfect a model can learn to
compute statistics from a sample dataset

Dataset description: The given dataset was downloaded from the link mentioned below:
https://drive.google.com/file/d/1RSDumnSgINshUAu4zGjC2fsVIO6nOLXM/view
The dataset is divided into two different parts Train and Test and the target variable is in the form of
multiple columns which are quantile 0.1, 0.5, 0.9 including average and variance. The dataset consists
of unknown probability distribution

Results:
The accuracy obtained for different combinations is mentioned above. The highest accuracy obtained
in this combination was with trees: 500, target variable: avg. The accuracy was around 43%. In the
fifth model where the target variable is variance, the accuracy observed is very low. As we go from
quantile 1 to quantile 9 the accuracy increases. The average column also shows high accuracy but the
accuracy gets dropped in the variance model.
References:
[1] Understanding Random Forest
Tony Yiu - https://towardsdatascience.com/understanding-random-forest-58381e0602d2
Dataset:
https://drive.google.com/file/d/1RSDumnSgINshUAu4zGjC2fsVIO6nOLXM/view
