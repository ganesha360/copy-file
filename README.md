# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
From shutil import copy file
### Step 2: 
From sys import exit 
### Step 3: 
Getting input for source file
### Step 4:  
Getting input for target file
### Step 5: 
Giving condition for files
### Step 6: 
Getting statement from the user to print or not want to print
## PROGRAM:
```PYTHON
#Program to read contents from a CSV file.
#Developed by: GANESH R
#RegisterNumber:212222240029

import pandas as pd
df=pd.read_csv("NBA.csv")
print(df.head(10))
print(df.tail())
print(" rows",df.axes[0])
print(" columns",df.axes[1])
print("no of rows",len(df.axes[0]))
print("no of columns",len(df.axes[0]))
```
### OUTPUT:
![py1](https://github.com/ganesha360/copy-file/assets/120884552/eda02f53-7eb4-4987-83c9-765754acd6ae)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
