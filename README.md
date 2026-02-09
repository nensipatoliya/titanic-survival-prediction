# titanic-survival-prediction
##🚢 Titanic Survival Prediction using Machine Learning

#📌 Project Overview

The Titanic disaster of 1912 is one of the most famous shipwrecks in history. This project aims to predict whether a passenger survived or not based on passenger details such as:

Age
Gender
Passenger Class (Pclass)
Fare
Cabin Information
Embarkation Port

Using Machine Learning, we analyze historical Titanic passenger data and build a predictive model.

🎯 Problem Statement

Predict passenger survival using historical Titanic dataset.

Target Variable:

Survived
    0 → Did Not Survive
    1 → Survived

📊 Dataset Information
Dataset is taken from Kaggle Titanic dataset.

Dataset contains features like:

PassengerId
Survived
Pclass
Name
Sex
Age
SibSp (Siblings/Spouses aboard)
Parch (Parents/Children aboard)
Ticket
Fare
Cabin
Embarked

🛠 Technologies Used

Technology	Purpose
Python	Programming
Pandas	Data Handling
NumPy	Numerical Computing
Matplotlib	Visualization
Seaborn	Advanced Visualization
Scikit-learn	Machine Learning
📂 Project Workflow
1️⃣ Business Understanding

Understand Titanic disaster context

Define prediction goal

Identify important passenger attributes

2️⃣ Data Collection

Dataset loaded using Pandas:

data = pd.read_csv('datasets/Titanic-Dataset.csv')

3️⃣ Data Preprocessing
✔ Handling Missing Values

Age → Filled using mean/median

Cabin → Dropped or filled

Embarked → Filled using mode

✔ Feature Encoding

Sex → Converted to numeric

Embarked → Label Encoding

4️⃣ Exploratory Data Analysis (EDA)

Visualization used to understand patterns:

Survival count

Survival by Gender

Survival by Class

Age distribution

Example:

sns.countplot(x='Survived', data=data)

5️⃣ Feature Selection

Important features selected:

Pclass

Sex

Age

Fare

Embarked

6️⃣ Model Building

Machine Learning algorithms used (depending on notebook):

Logistic Regression

Random Forest

Decision Tree

Support Vector Machine

Example:

from sklearn.model_selection import train_test_split

7️⃣ Model Training

Dataset split into:

Training Data

Testing Data

8️⃣ Model Evaluation

Evaluation Metrics:

Accuracy

Confusion Matrix

Classification Report

Example:

from sklearn.metrics import accuracy_score

📈 Results

The model predicts passenger survival based on input features.

Typical accuracy range:
✅ 75% – 90% (depends on model tuning)
