# Cervical_cancer_prediction
In this project, i built and trained an XG-Boost classifier to predict whether a person has a risk of having cervical cancer. Data was obtained from 858 patients and has 36 columns at Kaggle, and included features such as number of pregnancies, smoking habits, Sexually Transmitted Disease (STD), demographics, and historic medical records. Performed Exploratory Data Analysis and Data Visualization on the training data set. Prepared the data and splitted into training and test dataset before Model Training. XG-Boost-Algorithm was trained and evaluated for this task using scikit_learn library in Python. The Accuracy for this Machine Learning Model before hyperparameter tuning was:
-99.833 % (Training Dataset) 
-94.961 % (Test Dataset)

After doing hyperparameter tuning of the model, the accuracy of the model increased in the test data, and the variation between the test and the training score was reduced
-96.5 % (Training Dataset) 
-96.511 % (Test Dataset)
