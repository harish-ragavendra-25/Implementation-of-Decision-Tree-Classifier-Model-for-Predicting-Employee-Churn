# Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn

## AIM:
To write a program to implement the Decision Tree Classifier Model for Predicting Employee Churn.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1.Import the required libraries.
2.Upload and read the dataset.
3.Check for any null values using the isnull() function.
4.From sklearn.tree import DecisionTreeClassifier and use criterion as entropy.
5.Find the accuracy of the model and predict the required values by importing the required module from sklearn.

## Program:
```
/*
Program to implement the Decision Tree Classifier Model for Predicting Employee Churn.
Developed by: HARISH RAGAVENDRA S
RegisterNumber:  212222230045
*/
```
```
/*

import pandas as pd
data=pd.read_csv("/content/Employee.csv")

print('data.info:')
data.info()

print('data.isnull().sum():')
data.isnull().sum()

print('value_count: ')
data["left"].value_counts()

from sklearn.preprocessing import LabelEncoder
le=LabelEncoder()

data["salary"]=le.fit_transform(data["salary"])
data.head()

*x=data[["satisfaction_level","last_evaluation","number_project","average_montly_hours","time_spend_company","Work_accident","promotion_last_5years","salary"]]
x.head()**

y=data["left"]

from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=100)

from sklearn.tree import DecisionTreeClassifier
dt=DecisionTreeClassifier(criterion="entropy")
dt.fit(x_train,y_train)
y_pred=dt.predict(x_test)

from sklearn import metrics
accuracy=metrics.accuracy_score(y_test,y_pred)
accuracy

dt.predict([[0.5,0.8,9,260,6,0,1,2]])
*/
```

## Output:
![decision tree classifier model](sam.png)
![Screenshot 2023-11-11 165348](https://github.com/harish-ragavendra-25/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/114852180/5f470322-1447-45d4-a34c-076da5e12654)
![Screenshot 2023-11-11 165342](https://github.com/harish-ragavendra-25/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/114852180/648ae4d3-b1d0-4e2d-9594-3f0a8c6929c3)
![Screenshot 2023-11-11 165334](https://github.com/harish-ragavendra-25/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/114852180/bee50148-01fb-496d-942c-f94755630700)
![Screenshot 2023-11-11 165326](https://github.com/harish-ragavendra-25/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/114852180/22534d7d-1947-4e98-935a-735932a38b49)
![Screenshot 2023-11-11 165321](https://github.com/harish-ragavendra-25/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/114852180/6df29c93-53cc-4954-b599-384160ef5a47)
![Screenshot 2023-11-11 165313](https://github.com/harish-ragavendra-25/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/114852180/c2a4b25c-1f66-4abd-b17f-927751ffef36)
![Screenshot 2023-11-11 165302](https://github.com/harish-ragavendra-25/Implementation-of-Decision-Tree-Classifier-Model-for-Predicting-Employee-Churn/assets/114852180/6eb70ca5-86b4-4eff-9936-db34b08cf900)


## Result:
Thus the program to implement the  Decision Tree Classifier Model for Predicting Employee Churn is written and verified using python programming.
