Student Exam Score Prediction using Linear Regression

Problem Statement: 
The objective of this project is to predict student exam scores based on study habits using a machine learning model. The project focuses on understanding how study hours and attendance influence the final exam score. Linear Regression is used to model the relationship between these features and the target variable.

Dataset Description: 
A small dataset of 20 student records was manually created using Python and Pandas. Each record represents a student and contains information about their study hours, attendance percentage, and exam score.

Features used in the dataset: 
StudyHours – Number of hours a student studies per day
Attendance – Percentage of class attendance
Score – Final exam score obtained by the student

The dataset is stored and processed using a Pandas DataFrame.

Model Used: 
A Linear Regression model from the Scikit-Learn library was used to predict student exam scores. The dataset was split into training and testing sets to evaluate the model's performance. The model learns the relationship between study habits and exam performance and then predicts scores for unseen data.

Results: 
The model was evaluated using Mean Absolute Error (MAE) and R² Score.
MAE measures the average difference between predicted and actual scores, while R² Score indicates how well the model explains the variation in the data. The results show that study hours and attendance both contribute positively to predicting exam scores.

Conclusion: 
This project demonstrates how a simple machine learning algorithm such as Linear Regression can be used to analyze student performance. The experiment also shows the importance of feature selection and proper train-test splitting when building predictive models.
