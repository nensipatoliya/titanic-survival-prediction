# titanic-survival-prediction

# 🚢 Titanic Survival Prediction using Machine Learning

---

## 📌 **Project Overview**

The Titanic disaster of 1912 is one of the most famous shipwrecks in history.  
This project aims to predict whether a passenger survived or not based on passenger details such as:

- Age  
- Gender  
- Passenger Class (Pclass)  
- Fare  
- Cabin Information  
- Embarkation Port  

Using **Machine Learning**, we analyze historical Titanic passenger data and build a predictive model.

---

## 🎯 **Problem Statement**

Predict passenger survival using historical Titanic dataset.

### **Target Variable**
- **Survived**
  - `0` → Did Not Survive  
  - `1` → Survived  

---

## 📊 **Dataset Information**

Dataset is taken from **Kaggle Titanic Dataset**.

### **Dataset Features**
- PassengerId  
- Survived  
- Pclass  
- Name  
- Sex  
- Age  
- SibSp (Siblings/Spouses aboard)  
- Parch (Parents/Children aboard)  
- Ticket  
- Fare  
- Cabin  
- Embarked  

---

## 🛠 **Technologies Used**

| Technology | Purpose |
|---|---|
| Python | Programming |
| Pandas | Data Handling |
| NumPy | Numerical Computing |
| Matplotlib | Visualization |
| Seaborn | Advanced Visualization |
| Scikit-learn | Machine Learning |

---

## 📂 **Project Workflow**

---

### **1️⃣ Business Understanding**
- Understand Titanic disaster context  
- Define prediction goal  
- Identify important passenger attributes  

---

### **2️⃣ Data Collection**

Dataset loaded using Pandas:

```python
import pandas as pd
data = pd.read_csv('datasets/Titanic-Dataset.csv')

