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
![Screenshot 2023-12-26 092848](https://github.com/23008112/Multivariate-Linear-Regression/assets/138972470/5621de04-97cb-4713-bb00-e21f25441c21)

![Screenshot 2023-12-26 093022](https://github.com/23008112/Multivariate-Linear-Regression/assets/138972470/992a81a7-61cc-4278-a4eb-013cb78ce553)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
