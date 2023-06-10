# Read-from-CSV

## AIM:
To read from CSV
## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns
### Step 5:
Print the output:
## PROGRAM:
```
Developed by:JEEVITHA S
Ref.no:212222100016

import pandas as pd
df=pd.read_csv("/content/nba.csv")
print(df.head(10))
print(df.tail())
print("rows",df.axes[0])
print("columns",df.axes[0])
print("no of rows",df.axes[0])
print("no of columns",df.axes[0])
```
## OUTPUT:
![image](https://github.com/Jeevithha/Read-from-CSV/assets/123623197/12d6111f-f0af-4331-af95-e5505ae269e4)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
