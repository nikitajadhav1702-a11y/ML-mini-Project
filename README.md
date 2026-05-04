# ML-mini-Project
This is my Machine Learning Mini Project Repository


This project focuses on predicting student performance using machine learning techniques. 
The main objective is to classify whether a student will pass or fail based on various academic and personal features such as study time, absences, and previous grades.

The dataset used is the Student Performance dataset, where the final grade (G3) is converted into a binary outcome: Pass or Fail.
Students scoring 10 or above are considered pass, while others are considered fail.

Data preprocessing plays an important role in this project. Categorical data is converted using Label Encoding, and feature scaling is applied 
using StandardScaler to improve model performance. The dataset is cleaned and prepared before training the model.

Logistic Regression is used as the machine learning model for classification. It predicts the probability of a student passing or failing based on input features.
If the predicted probability is greater than or equal to 0.5, the student is classified as pass; otherwise, fail.

The model achieved an accuracy of around 80–85%, showing that it can effectively predict student performance.

In conclusion, Logistic Regression proves to be a simple yet effective algorithm for this problem. 
The project demonstrates how machine learning can be applied in education to identify students who may need early support and intervention.
