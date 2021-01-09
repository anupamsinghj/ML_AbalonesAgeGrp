# ML_AbalonesAgeGrp

Abalone Age Group Classification

Objective: To classify abalones into different age groups from 4000+ samples based on their physical characteristics

• Implemented K-Nearest Neighbors, Naive Bayes, Decision Tree, Random Forest, Adaboost classifier, Multi-class Neural Network on the processed dataset
• Performed Hyperparameter tuning of the classifiers & acquired around 90% accuracy on Neural Network Classifier

The abalone data set contains 4177 rows and 9 columns. Dataset consists of 8 features and the number of rings (which is directly related to the age). These columns include 7 continuous attributes(Length, Diameter, Height, Whole weight, Shucked weight, Viscera weight, Shell weight), a categorical attribute (Sex) which is divided into three categories and one integer response variable (Number of rings). Number of rings vary from 1 to 29.But we reduce the number of
classes from 29 to 5.

We convert Regression problem into a classification problem by dividing the classes into 5 groups like :
________________________
Rings Range  |  Class
_____________|___________
1-6          |  1
7-12         |  2
13-18        |  3
19-24        |  4
24-29        |  5
