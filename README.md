# Credit_Risk_Analysis
Challenge 17 


### Overview of the analysis:
We are going to use different types of machine learning models. We are going to use three different type of machine learning algorithms to see which one is better to predict risk. 

ONE AND TWO
1. Oversampling RandomOverSampler
2. SMOTE
3. Undersampling ClusterCentroids

THREE
1. We now are going to train and compare BalancedRandomForestClassifier and EasyEnsembleClassifier to predict credit risk, both models will then be evaluated.


It is important to note that we have been learning that we have supervised and unsupervised learning. 

### Important General information
#### Libraries: imbalanced-learn and scikit-learn libraries

With machine learning we are able to get a sample data to keep and compare it againts the model. We are going to use different models to check the predictions and aftwerwards check it with our data sample.

 Please note that before starting the work, we first need to read a CSV.file and then check what information is relevant. What data is actually valuable for the model. *As well, plenty of times, we need to transform the data type that we have and even convert it into a numerical form. This is so that the mode is able to read the information. 


### Results: 


### Summary:
After testing our supervused machine learning models we are able to know which one was the best by having our traget columns closest to one. Please remember that the ratio needs to be between 0 and 1, (A .99 would be a high accuracy). Again, in order to know which was the best model we need to take a find the balanced accuracy from the different models. 
