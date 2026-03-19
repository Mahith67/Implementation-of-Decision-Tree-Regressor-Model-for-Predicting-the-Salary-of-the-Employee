# Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee

## AIM:
To write a program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. 
2. 
3. 
4. 

## Program:
```
/*
Program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.
Developed by: MAHITH M
RegisterNumber:25004610
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn.tree import DecisionTreeRegressor

dataset = pd.read_csv("Salary.csv")

X = dataset.iloc[:, 1:2].values
y = dataset.iloc[:, 2].values

regressor = DecisionTreeRegressor(random_state=0)
regressor.fit(X, y)

salary_pred = regressor.predict([[6.5]])
print("Predicted Salary:", salary_pred)

X_grid = np.arange(min(X), max(X), 0.01)
X_grid = X_grid.reshape((len(X_grid), 1))

plt.scatter(X, y, color='red')
plt.plot(X_grid, regressor.predict(X_grid), color='blue')
plt.title("Decision Tree Regression")
plt.xlabel("Level")
plt.ylabel("Salary")
plt.show()
*/
```

## Output:
<img width="1357" height="611" alt="image" src="https://github.com/user-attachments/assets/c95ae353-b91a-490b-85d3-e86682f3e14f" />



## Result:
Thus the program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee is written and verified using python programming.
