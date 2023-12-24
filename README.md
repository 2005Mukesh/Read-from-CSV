# Read-from-CSV

## AIM:
To Write a python program for reading content from a CSV file
## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv
### Step 3:
use head and tail method to get the required contents from the file
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
print the output
## PROGRAM:
```
Developed by: MUKESH.R
Register Number:23006020
import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0))
print("NUmber of columns:",len(df.axes[1]))
```
## OUTPUT:
![Screenshot 2023-12-24 095002](https://github.com/2005Mukesh/Read-from-CSV/assets/138849308/154e533c-1e64-4c6a-918d-fb586b585f0b)

## RESULT:
Thus a python program is written to read the contents of a CSV file
