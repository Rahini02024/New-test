AI HEALTH PREDICTION

Project Description:
AI Health Prediction is a Machine Learning project developed to predict whether a person is
likely to have diabetes based on health-related information.
The project uses the Pima Indians Diabetes Dataset and applies Logistic Regression as the machine learning algorithm.
The dataset is divided into training and testing data, and 
the trained model is used to predict the outcome for the test data.

Technologies Used:

* Python
* Pandas
* Scikit-learn
* Logistic Regression
* Machine Learning

Dataset:
The project uses the Pima Indians Diabetes Dataset.
The dataset contains health-related attributes such as:
* Pregnancies
* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age

The Outcome column is used as the target variable.

Methodology:

1. Load the diabetes dataset.
2. Prepare the input features and target variable.
3. Split the dataset into training and testing sets.
4. Train a Logistic Regression model.
5. Predict the outcomes using the test data.
6. Calculate the model accuracy.
7. Generate the classification report.

 Machine Learning Algorithm:
 Logistic Regression is used for classification because the project predicts a binary outcome:

* `0` – No diabetes
* `1` – Diabetes

Output:
     AI_Health_Prediction_Output.png
The program displays:
Accuracy
Classification Report
Precision
Recall
F1-score

Conclusion:
The AI Health Prediction project demonstrates how Machine Learning
can be applied to healthcare data to predict diabetes outcomes. 
The Logistic Regression model is trained using patient health information and 
evaluated using accuracy and a classification report.
