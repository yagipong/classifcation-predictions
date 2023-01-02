# classifcation-predictions
A project to demonstrate the predictive capabilities of classification modeling using machine learning.

The project sought to determine how features of a dataset might be used to predict a single target vector. In this case, the question the model sought to answer was "How might demographic information predict a person's income level?". 

Author: Yaw Agipong

Business problem:

How might demographic information predict a person's income level?

Data:

The source data was the Adult Income Dataset spreadsheet from Kaggle.com

https://www.kaggle.com/datasets/wenruliu/adult-income-dataset

Methods

The model employed Logistic Regression and K-Nearest Neighbor models to forecast predictions, then added Principal Component Analysis to improve the speed and accuracy of the model. In the preparation stage, the analysis employed data cleaning, exploratory and explanatory visualizations, and machine learning preprocessing to format the data appropriately for modeling.

Correlation Heatmap

The Correlation Heatmap demonstrates that most of the variables are not highly correlated.



Bar Graph - Item Fat Content vs. Item Visibility

The bar graph displays the relatively similar visibility between low fat and regular items.

Model

The results of the model indicated that a KNN model using PCA feature engineering provided the highest quality results (in this case, a score of 0.87). This model could be used in a variety of scenarios, such as predicting credit card default rates, market segmentation, or student loan requests. The results of this analysis demonstrated that it is possible with some desgree of confidence to predict a person's income level solely from their demographic information. However, the predictions made are not perfect and should be considered only as one part of a broader assessment of factors likely to influence income levels.

Recommendations:

The most important recommendation is to find variables that can better predict income. The current slate of variables only provides moderate predictive capability, which is not very useful in a business setting.

For further information

For any additional questions, please contact yagipong@outlook.com
