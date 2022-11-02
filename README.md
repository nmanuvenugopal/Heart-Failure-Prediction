# Heart-Failure-Prediction
1. Build different machine learning model to predict whether there can be  heart failure or not.
2. Load heart disease dataset in pandas dataframe.
3. Remove outliers using Z score. Usual guideline is to remove anything that has Z score > 3 formula or Z score < -3.
4. Convert text columns to numbers using label encoding and one hot encoding.
5. Normalising or applying scaling to the data.
6. Build a classification model using various methods (SVM, logistic regression, random forest) and check which model gives you the best accuracy
7. Now use PCA to reduce dimensions, retrain your model and see what impact it has on your model in terms of accuracy. Keep in mind that many times doing PCA reduces the accuracy but computation is much lighter and that's the trade off you need to consider while building models in real life.
