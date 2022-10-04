# Car_Price_Prediction
A model to predict the price of a car using Data Science and Machine learning in Python.

**Training Accuracy : 97.75%
  Testing Accuracy : 87.89%**
  
# Abstract
**Preprocessing**

The data is cleaned.
Outliers are removed.
Categorical values are converted to numeric format (Label Encoding).

**Fearure Selection:**

Correlation of all features with each other is checked.
ExtraTreesRegressor is used to check the importance of all features with respect to target variable.
Features with less importance are dropped.

**Split the dataset into train and test dataset.**

**Build the predictor model**

Random Forest Regressor: Training accuracy of 97.75% and Testing accuracy of 87.89%
Linear Regression : Training accuracy of 82.37% and Testing accuracy of 76.54%
Thus, Random Forest Regressor Model was chosen.

**Visualization**

Some Graphs were presented to show the result:
Histogram
Heatmap
Line Graph
