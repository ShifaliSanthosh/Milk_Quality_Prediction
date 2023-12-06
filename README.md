# Milk_Quality_Prediction
Milk Quality Prediction using the SVM algorithm

This is a small project where the Support Vector Machine (SVM) algorithm is used on a milk quality dataset that is on Kaggle [<link>](https://www.kaggle.com/datasets/cpluzshrijayan/milkquality).
Primarily used for classification problems, this algorithm finds the maximum hyperplane between the different vectors. Taking the two extremes, it is training and testing the dataset for future predictions. The decision boundary maximizes the distinction between two values of an attribute which are closest but not of the same category.

Here, the milk quality CSV file includes seven attributes (pH, temperature, taste, odour, fat, turbidity and colour) of which the SVM algorithm trains for all the values. 
Firstly, we are extracting the number of rows and columns. Then after training it for a test size = 0.4, we test it on a given sample. Upon completing that, both the accuracy score on trained values and the predicted score of the quality attribute are printed. Finally, the trained model is saved and loaded.
