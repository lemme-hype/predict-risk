# **Predict the risk of involvement in sex work online**

# Dependencies
* Python
* Numpy/Matplotlib
* Scikit-learn
* Pandas
* Seaborn
  

# About


Risk prediction is the task of predicting the likelihood of a person's risk of being involved in a sex business by registering on a dating site according to certain attributes

The goal of risk prediction is to develop a predictive model that combines various parameters
(Sexual_polarity, Sexual_orientation, Gender, etc.) to anticipate this risk. In this project, I document my observations as I explore, construct, and compare some commonly used classification models:

  * DecisionTreeClassifier.
  * RandomForestClassifier

I begin with data preprocessing and exploratory analysis, where I impute missing data values using some of the popular data imputation methods such as Mean, k-Nearest Neighbors, Expectation-Maximization.

I then model the data using K-Fold Cross Validation on the specified models as well as on imputed and oversampled datasets.

Finally, I analyze and evaluate the performance of the models on the validated datasets using several metrics such as accuracy, precision, recall, etc., and rank the models accordingly.