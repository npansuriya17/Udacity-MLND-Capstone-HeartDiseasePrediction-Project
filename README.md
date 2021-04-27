# Heart Disease Prediction Project

Heart Disease Prediction using Logistic Regression

Defination:

Heart diseases is a term covering any disorder of the heart. Heart diseases have become a major concern to deal with as studies show that the number of deaths due to heart diseases have increased significantly over the past few decades in the world, in fact it has become the leading cause of death in the world.

Thus preventing Heart diseases has become more than necessary. Good data-driven systems for predicting heart diseases can improve the entire research and prevention process, making sure that more people can live healthy lives. This is where Machine Learning comes into play.
Machine learning can potentially play a significant role in helping doctors and scientists predict heart disease. A person’s chance of having a heart disease includes many factors such as diabetes, high blood pressure, high cholesterol, abnormal heart rate, and age. 

This project is the capstone assignment for Udacity Machine Learning NanoDegree. It aims to model and predict the presence of heart disease in patients by using binary classification machine learning algorithms and a dataset of patient information, which can be found on Kaggle and UC Irvine's Machine Learning Repository.

In this project, we will use Logistic Regression to predict whether a person has a heart disease or not based on the various biological and physical parameters of the body.

Note: This is only a sample application and should not be considered as medical advice.


What is Logistic Regression ?

Logistic Regression is a statistical and machine-learning techniques classifying records of a dataset based on the values of the input fields . It predicts a dependent variable based on one or more set of independent variables to predict outcomes . It can be used both for binary classification and multi-class classification.

Data info:

The data used for training and testing is the Heart Disease UCI downloaded from Kaggle. The dataset consists of 303 individual data. There are 76 attributes in the dataset, however all published experiments refer to using a subset of 14 of them as far as machine learning is considered so. The "goal" field refers to the presence of heart disease in the patient.

The dataset is already provided in the repository (here).


age: displays the age of the individual.
sex: displays the gender of the individual using the following format : 1 = male 0 = female.
cp: Chest-pain type - displays the type of chest-pain experienced by the individual using the following format : 1 = typical angina 2 = atypical angina 3 = non - anginal pain 4 = asymptotic 
trestbps: Resting Blood Pressure - displays the resting blood pressure value of an individual in mmHg (unit)
chol: Serum Cholesterol - displays the serum cholesterol in mg/dl (unit)
fbs: Fasting Blood Sugar - compares the fasting blood sugar value of an individual with 120mg/dl. If fasting blood sugar > 120mg/dl then : 1 (true) else : 0 (false)
restecg: Resting ECG measurement - (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy by Estes' criteria)
Thalach: Max heart rate achieved - displays the max heart rate achieved by an individual.
exang: Exercise induced angina - (1 = yes; 0 = no)
ldpeak: ST depression induced by exercise relative to rest ('ST' relates to positions on the ECG plot. See more here)
slope: the slope of the peak exercise ST segment (1 = upsloping 2 = flat 3 = downsloping)
ca: Number of major vessels (0-3) colored by fluoroscopy - displays the value as integer or float.
thal: A blood disorder called thalassemia (3 = normal; 6 = fixed defect; 7 = reversible defect)
target: Displays whether the individual is suffering from heart disease or not : 0 = absence 1 = present.


Libraries Used -

Pandas (for data manipulation)
Matplotlib (for data visualization)
Seaborn (for data visualization)
Scikit-Learn (for data modeling)

Contents:
Step 1: Problem Definition
Step 2: Data Collection
	Import libraries.
	Import dataset.
Step 3. Data Exploration
	Understanding the data
	Data Visualization
	Correlation Matrix
	Countplots
Step 4. Data Preparation
	Data Scaling
	Data Train/Test Split
	Uploading Training & Test files to S3
Step 5. Data Modeling
	Modeling/ Training the data
Step 6. Model Deployment
	Deploying the Trained Model
Step 7. Model Evaluation
	Predicting the data
	Calculating the prediction scores
	Getting the model's accuracy
	Confusion Matrix
	