# BreastCancer_Classification
High accuracy CNN for clasification of IDC Kaggle data set

The Breast Histopathology Images set is available from Kaggle at: https://www.kaggle.com/paultimothymooney/breast-histopathology-images

Upon download "arrange_dataset.ipynb" file will prepare train, validation and test folders where images are saved in two cathegories (0 and 1). 
(This file needs several hours to run)
CNN model and it's result are in "Cancer_classifier_CNN_Model1.ipynb" file.
(This file needs around 1 day to run)

It is also possible to explore bachaviour of a model on smaller data set. This is available in second branch called "Exploratory analysis".
There is a file to create h5 file containing train and test set. "Exploratory_analysis.ipynb" file loads data from h5 file and trains models on it. 
(This file needs much less time to run.. cca 1 hour)

Packages:
Tensorflow 2.2 (it important is to have this version of tf) 
Imutilis (0.5.3 is used here, older versions can also be used) and OpenCV (4.2.0.34 is used here, older versions can also be used)
