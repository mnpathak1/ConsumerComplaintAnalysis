## Dataset
It is based on US consumer complaints dataset available on data.gov.   
Dataset already has information on classsifying the complaints for different categories (supervised learning).  

## Consumer Complaint Analysis Summary and Prediction Model
This work predicts the category of a consumer complaint.     
Text analysis and prediction model building were done using scikit-learn, plots were done using seaborn.   
Consumer complaint narratives were transformed into vectors of numbers using TF-IDF weighted vector representation for model building.  
Top 2 unigrams and bigrams were identified for each given class.  
Less significant classifications are removed and the classification model is developed based on more significant classes.   
Based on cross-validation accuracy among different methods, LinearSVC is selected for moel building (80%  test accuracy).  
Error analyais showed some classification errors are not easy to assign a particular category.  
Mortgage complaints showed best F1 score (90%) i.e. easiest to classify.  

## Future work
* Update model based on more updated data 
* Apply neural netowork sequence model and classification and compare results
