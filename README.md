
# Password Strength Classifers
Generated and compared multiple machine learning models in determining the strength of given passwords. The different algorithms used are SVM, decision tree, random forest, gradient boosting, light gradient boosting and categorical boosting. 

Classifiers are trained and tested using [this](https://www.kaggle.com/datasets/bhavikbb/password-strength-classifier-dataset) Dataset. TF-IDF vectorizer is used for feature extracion. Accuracy, confusion matrix and f1 score are determined for all the classifiers.

### Requirements
- Python 3.7
- Pandas
- Numpy
- Scikit Learn
- Pickle

### Notes
- data - Copy.csv is the cleaned dataset.
- Saved models should be loaded using pickle. 
