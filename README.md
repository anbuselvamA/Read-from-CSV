Read-from-CSV
AIM:
To develop a python program to read a file rom csv.

ALGORITHM:
Step 1:
Import the pandas function as pd.

Step 2:
Read the file and store it in the variable f.

Step 3:
Print the head and tail.

Step 4:
Print the number of rows using the length function(len).

Step 5:
Print the number of coloumns using the same length function(len).

PROGRAM:
Program developed by:R.Joyce Beulah
Reference number:22009334
Python program to read a file from csv.

import pandas as pd
f=pd.read_csv('cars.csv')
print(f.head(10))
print(f.tail())
print("Row:",len(f.axes[0]))
print("Col:",len(f.axes[1]))
OUTPUT:
outputRead-from-CSV
AIM:
To develop a python program to read a file rom csv.

ALGORITHM:
Step 1:
Import the pandas function as pd.

Step 2:
Read the file and store it in the variable f.

Step 3:
Print the head and tail.

Step 4:
Print the number of rows using the length function(len).

Step 5:
Print the number of coloumns using the same length function(len).

PROGRAM:
Program developed by: anbuselvam  a
Reference number:22009081
Python program to read a file from csv.

import pandas as pd
f=pd.read_csv('cars.csv')
print(f.head(10))
print(f.tail())
print("Row:",len(f.axes[0]))
print("Col:",len(f.axes[1]))
OUTPUT:
output

RESULT:
Thus the program is successfully executed.



RESULT:
Thus the program is successfully executed.

