# Read-from-CSV

## AIM:
To write a python program for reading the csv file content

## ALGORITHM:

### Step 1:
Load the CSV into a DataFrame.

### Step 2:
Print the number of contents to be displayed using df.head().

### Step 3:
The number of rows returned is defined in Pandas option settings.

### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.

### Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:

#To write a python program for reading content from a CSV file.

#Developed By : srivatsan G

#Register Number : 212223230216

```
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![Screenshot 2024-05-12 192120](https://github.com/vatsan143/Read-from-CSV/assets/147368204/2696d3fd-1b5b-4d3c-9033-9bff96a1fc78)

## RESULT:
Thus the program is written to read the csv file.
