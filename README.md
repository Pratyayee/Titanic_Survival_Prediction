# Titanic_Survival_Prediction_Machine_Learning

# Description:

i. I have read train.csv and test.csv in two separate dataframes. 

ii. From my intution I have figured out the unimportant features for predicting the number of survived. Thus the features, Passenger ID, Name, Ticket and Cabin are discarded for both the dataframes. 

iii. I have replaced the value of column Sex by binary values and Embarked by 1,2 and 3 for both the dataframes. 

iv. Then, I have changed NaN values of Sex and Embarked columns with the median values of the respective columns for both the dataframes. 

v. Then partitioned the 'Age' attribute into 6 different parts and valued 1,2,3,4,5,6 respectively. 

vi. I scaled the 'Fare' column into the range (0,1). 

vii. Then I did a 10 fold cross validation over the training data frame for Logistic Regression, Support Vector Machine(Linear and Rbf kernel),K Nearest Neighbour, Decision Tree, Random Forest, Perceptron and Bayes Classifier and calculated their accuracy and observed that Support Vector Machine Rbf kernel function predicting most accurately 8. I predicted the 'Survived' attribute of the persons in the test data frame and then with the 'PassengerId' column I created the Predicted_Survived.csv file.
