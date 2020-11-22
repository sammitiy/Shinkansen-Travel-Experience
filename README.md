# Shinkansen-Travel-Experience
Shinkansen Travel Experience
I recently participated in a Hackathon #hackofalltrades with great learning. The problem statement given to us was of a Shinkansen Travel Experience. The goal of the problem was to predict whether a passenger was delighted considering his/her overall travel experience of traveling in Shinkansen (Bullet Train).

There was a Survey data taken from over 95K passengers about the rating across different parameters, we had to predict the "Overall Experience" which was a binary classification. Travel data was also collected from these passengers. Two different sets of Train and Test were provided.

EDA: Dependant variable was balanced. Almost the entire data had missing values, in my approach, most of them were imputed using the highest frequency value for categorical data. Few were imputed with further analysis using the correlated parameters. Survey and Travel datasets were merged on 'ID' of every passenger. There were mere outliers in the data which were ignored. The data was label and hot encoded and scaled using z-scores. The training data was spilt 80:20 and the test set was used for validating.

Several classification algorithms like CART, Random Forest, Boosting, Bagging, Naive Bayes, Logistic Regression were used with parameter tuning, cross-validation, and threshold adjustments to built models. Adaptive Boosting with base estimator RF worked the best of all.

Accuracy was the metrics which was checked for the leaderboard ranking. I am currently 6th on the leaderboard with an accuracy of 0.9517. 
