# Read-from-CSV

## AIM:
To write a python program for reading content from CSV file.
## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use the len() method to get the number of rows and columns.
### Step 5:
Display the result.
## PROGRAM:
```
Developed by: Jothilakshmi
Register number: 212223110017
'''
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![copyoutput](https://github.com/Jothilakshmi12/Read-from-CSV/assets/138849182/90fe11e1-1e95-4552-9bec-91d7ad3cab4a)

## RESULT:
Thus the python program for reading content from a CSV file is successful.
