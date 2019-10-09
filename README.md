# KNN
This is a company dataset taken from Kaggle .They've hidden the feature column but provided the data and the target class

Problem Statement : To create a model that predicts the class data based on the features . So we try to create a KNN model for this.

KNN is the simplest machine learning algorithm used for classification and regression. 
It makes decision based on the entire training dataset. No time is spent on training the algorithm but only for pre-processing and testing.

WORKING : The algorithm makes predictions by calculating similarity between the input sample and each training instance.
Works on smaller data . Stuggles when the data is large


step 1 : Calacute the distance. i) Using Euclidean distance
                                ii) Using Manhattan distance
                                
step 2 : Find the closest neighbors K( should be an odd number)
step 3 : Vote for the labels (take the majority votes for preiction)



      
