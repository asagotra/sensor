Task

The file task_data.csv contains an example data set that has been  generated artificially. The set consists of 400 samples where for each sample there are 10 different sensor readings available. The samples have been divided into two classes where the class label is either 1 or -1. The class labels define to what particular class a particular sample belongs.

Your task is to rank the sensors according to their importance/predictive power with respect to the class labels of the samples.

Pyth script that generates a ranking of the sensors from the provided CSV file.

The ranking should be in decreasing order where the first sensor is the most important one.


Solution

Perform evaluation of feature importance with Mean decrease impurity method (Using feature_importances_ measure from RandomForestRegressor, xgboost, sklearn library)

Sort/Visualize the result
