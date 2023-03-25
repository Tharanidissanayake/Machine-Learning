# Machine-Learning Coursework
## Spam Classification Using Decision Trees and KNN
KNN and Decision Trees are used in this code to classify emails as spam or not-spam.

## Installation
The following packages and Python 3 are required to run this code.

 - sklearn 
 - matplotlib 
 - seaborn 
 - pandas 
 - numpy

## Dataset
The Spambase Dataset from the UCI Machine Learning Repository is the dataset utilized in this code. 4,601 emails in this dataset have a total of 57 features.

## Steps
The code executes the following procedures:

 - Bring up the Spambase Dataset.
 - Create training and test sets from the data.
 - Data normalization.
 - Create a KNN model using the training data.
 - Use the training set to train a decision tree model.
 - Compare the KNN and Decision Tree models' performance.
 - Use PCA to visualize the outcomes.

## Performance
The KNN model achieved an accuracy of 0.888, precision of 0.865, recall of 0.819, and an F1 score of 0.842. 
The Decision Tree model achieved an accuracy of 0.912, precision of 0.903, recall of 0.825, and an F1 score of 0.862.

## Data Visualizations
The code provides confusion matrices based data visualization.

## Acknowledgements
Tharani Dissanayake is the author of this code. The UCI Machine Learning Repository provided the Spambase Dataset.
