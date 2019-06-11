# Cancer Prediction | Python_Guild


Problem setting:

A pharmaceutical company wants to develop a test for cancer based on mass spectrometry measurements. In mass spectrometry, the mass of certain proteins in the body is
determined, which may provide information about a disease of the patient. Due to the high number of proteins - mass spectrometry provides measurements for 10,000 different proteins - it is so far difficult to conclude from the existence of certain proteins or protein combinations that there is a cancer. However, it is known that only a very small part of the proteins indicates a cancer. A large part of the measured values is thus irrelevant for
the test.
The aim of your work is to create a model based on the data from 100 patients that uses only a few of the available measurements (numerical features) to make the most accurate prediction possible as to whether a cancer exists. It is particularly important to ensure that no cancer remains undetected.



Plan:

We will conduct an adequate preprocessing, noting that many of the features don’t contain any information about the class label. For this reason, we will use a suitable method for feature reduction/selection. To this aim, we will compare the following methods:
• backwards elimination of features via alternating the training of a classifier and the deletion of the least important features
• dimensionality reduction using principal component analysis before training the classifier.
We will identify and implement a suitable learning method in Python, training and evaluating the model to predict cancer. 

---------------------------------------------
Python 3.7.3
