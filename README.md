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
Register No. : 212222230116
Name : Ranjan k
```
```
import pandas as pd
f=pd.read_csv('/content/nba.csv')
print(f.head(10))
print(f.tail())
print('No. of Rows:',len(f.axes[0]))
print('No. of Col:',len(f.axes[1]))
```
## OUTPUT:
![Screenshot 2023-11-07 095206](https://github.com/Ranjanranjan/Read-from-CSV/assets/130027697/99f45c62-4ed6-4307-b290-955164a9aa22)



## RESULT:
Thus the program executed successfully for read csv file.
