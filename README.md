# Biometric-Fingerprint-Classification
Built fingerprint classifier by developing a own RBF kernel based support vector machine. Developed SVM in order to make a multi-class prediction model and obtained accuracy of 90% in Python.
ACCURACY
The accuracy score on the testA evaluation is 80.95%

This is a multi class classifier of the RBF kernel.
In order to train the dataset which has 21 classes we used one vs all strategy. In this strategy we take one class as positive and the remaining classes as negatives and do the classification and it should be done with all the 21 classes thus we train the dataset with support vector machine. We used inbuilt functions for the classification of the dataset and training.

METHODS FOR IMPROVEMENT

There are different parameters for which the accuracy will be increased. 

1.	It depends on the feature size of the fingerprints that can be reduced by trimming the blank parts of the fingerprints, if the feature size is big it slows down the training and predicting process that decreases accuracy. The accuracy depends on how many rows and columns we trim for the fingerprints to remove blank parts around them
2.	It also depends on the darkness variance i.e normalization.
3.	Other parameters in the svm function like the penalty parameter(C), gamma(kernel coefficient for rbf), tolerance for stopping criterion value will change the accuracy.

CHALLENGES

The main challenges we faced were 
1.	Preprocessing of the fingerprints where we have to trim the columns and rows to remove blank parts and also darkness variance and creating the matrix for the fingerprints 
2.	We tried to implement our own multi-class classifier using one vs all strategy but we couldn’t do is as we find it difficult to do it for all the classes given so we later came up with in built functions.
3.	For the checker algorithm we tried to do it with single image as a test set and do the prediction.
These are some of the challenges we faced while development of this project
