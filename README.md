# Heart-Failure-Prediction
Build different machine learning model to predict whether there can be  heart failure or not
Load heart disease dataset in pandas dataframe
Remove outliers using Z score. Usual guideline is to remove anything that has Z score > 3 formula or Z score < -3
Convert text columns to numbers using label encoding and one hot encoding
Apply scaling
Build a classification model using various methods (SVM, logistic regression, random forest) and check which model gives you the best accuracy
Now use PCA to reduce dimensions, retrain your model and see what impact it has on your model in terms of accuracy. Keep in mind that many times doing PCA reduces the accuracy but computation is much lighter and that's the trade off you need to consider while building models in real life
