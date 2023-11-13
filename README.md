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
Program for copying the contents from one file to another file
Developed by: GANESH R
RegisterNumber: 212222240029

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:

![PY3](https://github.com/ganesha360/copy-file/assets/120884552/355687dc-40c9-47bc-b946-c6bcb26f2e3a)
![PY4](https://github.com/ganesha360/copy-file/assets/120884552/b7e976ff-a8da-44f2-b68a-e138b3ec721e)


![PY2](https://github.com/ganesha360/copy-file/assets/120884552/4c987e88-67a3-4020-ac4f-da5ba1229729)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
