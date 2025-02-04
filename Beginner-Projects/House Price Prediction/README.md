House prices data is also great to start with if you are a beginner at machine learning. This project will use the house pricing dataset available on Kaggle. The target variable in this dataset is the price of a particular house, which you will need to predict using information like house area, number of bedrooms, number of bathrooms, and utilities.

It is a regression problem, and you can use techniques like linear regression to build the model. You can also take a more advanced approach and use a random forest regressor or gradient boosting to predict house prices.

This dataset has 80 columns, excluding the target variable. You will need to employ some dimensionality reduction techniques to hand-pick features since adding too many variables can make your model perform poorly.

There are also many categorical variables in the dataset, so you need to properly deal with them using techniques like one-hot encoding or label-encoding.

After building your model, you can submit your predictions to the house pricing competition in Kaggle, as it’s still open. The best RMSE achieved by competitors is 0, and many people have achieved good results like 0.15 with the help of regression and gradient boosting techniques.

Dataset: [Kaggle House Price Prediction Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)