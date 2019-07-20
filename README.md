# Group Details
Group ID    : 1957

Member Name : Akshat Minocha

SME         : Simran Saha

# Twitter_Follower_Analysis
Classification models to visualize and analyze the Twitter Follow Back problem.


#This problem involves extraction of users data from twitter and visualizing and analyzing it in order to achieve the sole target of predicting whether the user account you have followed, will follow you back.

On completion of this project, I became more clear with the application of  classification models and social media networks, how to build a Random forest & Xgboost Classification models first and then improve it using different other features and techniques.

# Features Extraction
1) The users' information was obtained progressively using the 'python-twitter' module of Python.
2) At first, mostly all of the possible features were obtained with the help of api and were checked for any redundant or null  values.
3) The redundant attributes were dropped and the rest of the categorical data(true/false) was converted to numerical (1/0) form.

# Model Implementation
1) The preprocessed data was divided into train/test data and was used for different classification models.
2) Initially, Random Forest Classifier and Logistic models were applied, which gave no good results (due to wide variation in the 0/1 samples)
3) Then, sampling technique was used and the resultant data was applied to various models, including xgboost classifier.

# Outcome
Xgboost Classification gave the best result with good accuracy and better f1_score (for both 0/1) as comapred to the other models applied.
