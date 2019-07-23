
Observations after modeling 


The test set is significantly larger than the train set. Linear regression is trained in a certain level of interval to predict in a train data set. Therefore, data extrapolation is a issues while using a test set to predict. For example,  linear regression will not predict well anything beyond the train set because data extrapolation is varies in the test data and features are not in a linear relationship. Therefore, the forecast will be a linear line. However, polynomial features may alleviate this issues during the process of feature engineering.   
Since the goal is to predict the log error, new features are not aim to predict the sale price. For example, pool count and size could be the outliners that could be attributed to overfitting. 
Filling the missing values with KNN is time-consuming and categorical data need to be compressed before modeling. Some of the fields could just a a noise for the model. 
Feature importance indicates the Gini impurity on the split. The performance measure may be the purity (Gini index) used to select the split points or another more specific error function. Having irrelevant features in data can decrease the accuracy of the models and make the model learn based on irrelevant features. 
Training time will be a issues as the data set is large. Therefore, using fewer features and deploy the time-efficient models such as cat boost and light GBM are ideal to achieve this project
Ensemble model with iterations of different parameters in ensemble model could improve the scores from 0.065 to 0.064. However, finding a right tune could be challenging and time consuming. 

