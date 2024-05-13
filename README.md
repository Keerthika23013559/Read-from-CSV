# Read-from-CSV

## AIM:
to write a python program for reading content from a CSV file

## ALGORITHM:
### Step 1:
import pandas as pd
### Step 2:
now read the csv file using pd.read_csv() and store it in a variable
### Step 3:
Now print the first 5 lines using head()
### Step 4:
and print the last 5 lines using tail()
### Step 5:
to find the number of rows and cols use len()

## PROGRAM:
```
#to write a python program for reading content from a CSV file
# Name : Keerthika M P
# Reg no: 212223240071

import pandas as pd
df = pd.read_csv('dataset13.csv')
print(df.head())
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))

```
## OUTPUT:
![image](https://github.com/Keerthika23013559/Read-from-CSV/assets/162658262/fa8e7d3d-93d7-48bd-8bd4-b04dca25094e)

## RESULT:
Thus the program to read the csv file is successfully created and eecuted
