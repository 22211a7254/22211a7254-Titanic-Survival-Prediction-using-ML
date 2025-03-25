# 22211a7254-Titanic-Survival-Prediction

#  An overview of the project
This research develops a machine learning model that uses a number of characteristics, including age, gender, ticket class, and fare, to predict if a passenger survived the Titanic disaster.

# Dataset
The dataset includes the following columns:

PassengerId: Unique identifier

Survived: Target variable (0 = No, 1 = Yes)

Pclass: Ticket class (1st, 2nd, 3rd)

Sex: Gender

Age: Passenger's age

SibSp: Number of siblings/spouses aboard

Parch: Number of parents/children aboard

Ticket: Ticket number

Fare: Passenger fare

Cabin: Cabin number (mostly missing values)

Embarked: Port of embarkation

# Preprocessing of Data

 1.Columns for ticket, name, and cabin were dropped because they weren't needed for modeling.
 
 2.Filled missing values:The median was used to fill in Age and Fare.
 
 3.Encoding in categories: Male = 1, female = 0 was the binary conversion of sex.
 
 One-hot encoding was used for embarking.
 
 4. Normalization
    
 To scale Age and Fare, Min-Max normalization was used.

 # Training of Models
 
 100 estimators were used in the Random Forest Classifier.
 
 Divide the dataset into two parts: 20% for testing and 80% for training.
 
 produced predictions and trained the model.
 
# Model Evaluation

Metrics used:

1.Accuracy: 100%

2.Precision: 100%

3.Recall: 100%

4.F1-score: 100%


