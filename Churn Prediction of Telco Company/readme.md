# Churn Prediction in a Telco Company
## Customer churning prediction is an important activity for any company to identify individuals likely to drop their subscriptions to a service. The ability to predict this, is very key, so that companies identify such individuals and make the neccesary arrangements to keep them. This can be extended to any new individuals who would subscribe to the service in the future, so that based on the patterns of the previous customers, more attention can be focussed on such individuals.
### The dataset consisted of 7043 customers, with their various features recorded. The data was split into a kfold of 5 and cross validated. The random forest algorithm and the xgboost algorithm were the machine learning models used to predict the churn, and the xgboost proved to predict a higher percentage of churned individuals, predicting 55% of the customers that churned with an f1 score of 60.24%, compared to the random forest algorithm which predicted 51% of individuals with an f1 score of 57.62%. Both algorithms were optimized by tuning their hyperparameters in order to achieve the best results, and the metrics evaluated upon were the accuracy, f1score and the confusion matrix. The results of this is useful for any telecom industry or any industry at large, to identify individuals likely to churn so they focus attention and limited resources on them.
### Libraries used
#### pandas
#### numpy
#### matplotlib
#### seaborn
#### sklearn
#### itertools



