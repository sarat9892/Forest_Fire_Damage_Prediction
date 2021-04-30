# Machine Learning on Forest Fires Dataset

 - This is a difficult regression task, where the aim is to predict the burned area of forest fires, in the northeast region of Portugal, by using meteorological and other data.

## Process

### Regression

- Various regression models are implemented to estimate the area of forest fire burnt, using the predictor variables
- Models tested include, OLS, Ridge/Lasso Regression, Support Vector Regression, Decision Tree Regressor, Random Forests and Gradient Boosted Regressor
- Feature selection algorithms are also employed to pick the best predictor variables
- Power Transformation and Standard Scaling are use to transform the data

#### Regression - Outcome

- R squared does not go beyond 0.03
- The least MAE observed is 18 hectares
- Most of the target variable values are 0 (250 out of 500) and the non zero values are also highly skewed. Even the predictor variables are also highly skewed
- Even the data transfomation methods were not helpful

### Classification

- A new column called burn is created which holds the value 0 for 0 area burn and 1 for non-zero area burn.
- This column can be used to train a binary classification model that predicts whether the given environment parameters lead to buring forests or not
 


## Data

Source: http://archive.ics.uci.edu/ml/datasets/Forest+Fires
