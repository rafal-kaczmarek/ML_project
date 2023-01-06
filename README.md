The main goal of this project is to show usage of different machine learning techniques in regression where the dependent variable is house sale prices in Seattle in the first half of the 2015. The dataset comes from https://geodacenter.github.io/data-and-lab//KingCounty-HouseSales2015/. It contains data about home sales in King County in 2014-2015. Project is divided in to two parts. Firstly, the data for Seattle was selected, described, visualized and verified for occurence of incorrect values. After it, the feature selection methods were applied. These steps properly prepared dataset which was used in the second part of this project, where selected variables were used to create a dataset for regression. Before implementing various types of regression methods, the dataset was divided into train and test sample. To predict house prices, the following regression techniques were selected:
-Linear Regression
-Lasso
-Ridge
-Decision Tree
-Random Forest
For each of them the k-fold cross validation was used. In order to select the best model metrics like R2, neg_root_mean_squared_error, neg_mean_absolute_error were used. Based on these results, the best techniques are Random Forest, Linear Regression and Rigde Regression.

Creation date: 08.2021
