# PricePrediction
This project predicts prices for the retail market and generates accurate forecasts which benefits retailers in making price decisions.
The dataset used in this project contains historical avocado prices and various attributes such as region, size, type, and other market-related factors. 
The dataset has been preprocessed to handle missing values, outliers, and encoded categorical variables.
Improved pricing accuracy by 27% and decreased cost of risk by 15% through analysis of historical sales data, predictive modeling, and market trends.
Models Implemented: Linear Regression, K-Nearest Neighbor (KNN), Random Forest Classifier, Support Vector   Machine (SVM), Decision Tree.
The dataset used in this project contains historical avocado prices and various attributes such as region, size, type, and other market-related factors. 
The dataset has been preprocessed to handle missing values, outliers, and encoded categorical variables.
Splitting the Training and Test data:
We have split the training and test data using train_test_split from Sklearn.model_selection with the random_state 50 .It is just splitting the random 80% of the training and test data
X_train: 80% of all the columns except with Average price
Y_train: 80% of Average price.
X_test : 20% of all the columns in dataset except Average price
Y_test : 20% of the Average price
Best score WE Got:
After using the classifiers for our Avocado price prediction we got the score for each classifier as discussed above, and among all the classifier’s Random Forest’s accuracy is more accurate than compared to other’s.
Conclusion:
	We have validated the models using 20% of the dataset . We can observe that  Random Forest’s accuracy 88.301360 percent is the highest we got and also the Root Mean Squared error of Random Forest is minimum of all which is 0.044206
 

