# Taxi-Fare-Prediction-in-scala-using-spark-machine-learning
we are predicting the fare amount for a taxi rides in New York City given the pickup and dropoff locations.

There were two data sets available, the one was for training the model and the other was for testing the models. But we are training and testing using the training data set only. The source for the data sets is Kaggle:
https://www.kaggle.com/c/new-york-city-taxi-fare-prediction/data

The End goal for this project is to predict the estimated fare price for taxi rides in the New York City area. It was required by the Kaggle that RMSE of the predictions should be between $5 - $8.

We are making this project using the cluster provided by the university on yarn using spark framework. We are using jupyter notebook for coding in Scala and zeppelin for the visual representations.

We using Regression for the prediction of fare amount:
We are using four Regression Algorithms:
Linear Regression
Gradient boosted Tree Regression
Random Forest Regression
Decision Tree Regression


We calculated the absolute difference between the pickup and drop-off latitude and longitude values and the distance in kilometers between the pickup and drop-off location values
We did two separate set of evaluation one using the absolute difference and the kilometer difference between the lat long values

