# Read-from-CSV

## AIM:
To write a program for reading the csv file content
## ALGORITHM:
Step 1:

Load the CSV into a DataFrame
Step 2:

Print the number of contents to be displayed using df.head().
Step 3:

The number of row returned is defined in pandas option settings.
Step 4:

Check your systems maximun column with the pd.options.display.max_columun statement.
Step 5:

Increase the maximum number of rows to display the entire DataFrame

## PROGRAM:
```
#Devloped By: SANJAY S
#Ref no: 212222230132



import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column", len(df.axes[0]))
print("rows", len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/22002102/Read-from-CSV/assets/119091638/0c883000-f766-4b90-8a84-30db69a01e5b)


## RESULT:
Thus the program executed successfully for read csv file.
