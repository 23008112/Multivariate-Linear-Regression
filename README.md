# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Import pandas as pa and from sklearn import linear_model

### Step2
Read the csv file from the drive

### Step3
Drive the required list from the file

### Step4
print the list of the program

### Step5
End the program

## Program:
```
#Python program to implement multivariate linear regression and predict the output.
#Developed by:R.SANJANA
#Register Number: 23008112

import pandas as pd
from sklearn import linear_model


df=pd.read_csv("cars.csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("coefficient",regr.coef_)
print("Intercept:",regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))

```
## Output:
![Screenshot 2023-12-24 022627](https://github.com/23008112/Multivariate-Linear-Regression/assets/138972470/52f96c36-90ea-4b95-89c4-d9dc45916089)

![Screenshot 2023-12-24 023434](https://github.com/23008112/Multivariate-Linear-Regression/assets/138972470/18170a85-dfa0-436c-a0f1-1ac459d13bbd)


### Insert your output

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
