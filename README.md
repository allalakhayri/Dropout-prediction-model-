##Student Dropout Prediction Project
This project aims to predict the risk of students dropping out of university using machine learning algorithms. The data used for this project is collected from a university in Portugal and includes various features such as marital status, application mode, previous qualification, nationality, and academic performance in the first and second semesters.

##Data
The data used for this project is stored in the file student_data.csv. It contains 3333 instances and 34 features, including the target feature indicating whether a student has dropped out or not.

##Preprocessing
Before building the models, the data was preprocessed to handle missing values and categorical features. Missing values were imputed using the median of the corresponding feature, and categorical features were one-hot encoded.

##Models
Three machine learning algorithms were implemented and compared for this project: logistic regression, random forest, and decision tree classifiers. The models were trained using 70% of the data and evaluated on the remaining 30%.

##Results
The random forest classifier performed the best among the three models, achieving an accuracy of 77% and an F1-score of 0.85 for the graduate class. The logistic regression model achieved an accuracy of 75%, and the decision tree classifier achieved an accuracy of 69%.

##Usage
To use the models for predicting the risk of dropout for a new student, input the student's information in the same format as the data file and pass it through the chosen model to obtain the predicted probability of dropout.

##Dependencies
The project was implemented using Python 3.8 and the following libraries:

pandas
numpy
scikit-learn
seaborn
matplotlib