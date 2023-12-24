# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file
## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Display the result.
## PROGRAM:
~~~
Developed by:RAKSHITHA K
Register No: 23003887

To write a python program for reading content from a CSV file.
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
~~~

## OUTPUT:
![image](https://github.com/RakshithaK11/Read-from-CSV/assets/139336455/5e45e51b-7a99-4880-bb43-c72d38413843)

## RESULT:
Thus python program for reading content from a CSV file is successful.

