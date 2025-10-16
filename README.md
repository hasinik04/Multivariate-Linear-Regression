# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Import pandas as pd

### Step2
Read the csv file

### Step3
Get the value of X and Y variables

### Step4
Create the linear regression model and fit

### Step5
Predict the CO2 emission of a car where the weight is 2300kg and the volume is 1300cm^3

### Step 6: 
Print the predicted output

## Program:
```
Developed by: KATHI HASINI
Reg.No: 212224240074

import pandas as pd
from sklearn import linear_model
df=pd.read_csv("car (1).csv")
x=df[['Weight','Volume']]
y=df['CO2']
regr=linear_model.LinearRegression()
regr.fit(x,y)
print("Coefficient",regr.coef_)
print("Intercept",regr.intercept_)
print("Co2 required is",regr.predict([[3300,1300]]))

```
## Output:
### Insert your output
<img width="839" height="257" alt="Screenshot 2025-10-16 085830" src="https://github.com/user-attachments/assets/51d48956-a0a8-4c71-bb8a-c3b6190c4617" />


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
