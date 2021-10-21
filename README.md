# SDAIA-T5-Bootcamp-
This project is proposed for SDAIA T5 Data Science Bootcamp.

# Abstract
The goal of this project is to use prediction models to predict real estate prices in the north of Riyadh city to help many individuals and investors to know prices and take appropriate decisions according to the factors that affect real estate prices.

# Design
- Four models were used in this project to predict real estate prices and reach the best result among these models.
- The models are linear Regression, Decision Tree, Random Forest, and Support Vector Machine.

# Data
- The data were collected from a local source for real estate deals.
- The dataset contains 10 features and 5946 examples.
- This data was used to predict real estate prices and extract some useful information to improve the accuracy of the models.
- The prediction was validated using a set of metrics such as R-square Mean Squared Error and Mean Absolute Error.

# Algorithms
The models were used linear Regression, Decision Tree, Random Forest, and Support Vector Machine.
The steps to implement the models were as follows:
- After reading the data file, the features and the label are determined by finding the correlation between them.
- The data was divided into 80 training set and 20 test set to train the models on this data.
- Models were called and trained on data from the Scikit-learn library.
- After training the models on the training dataset, prediction values are found for each model.
- Through the prediction values, the validity of the models is verified and the best model with a value closer and more accurate to the real values is found using a set of metrics such as R-square Mean Squared Error and Mean Absolute Error.

# Tools

- Numpy and Pandas for data manipulation.
- Scikit-learn for modeling.
- Matplotlib and Seaborn for plotting.
