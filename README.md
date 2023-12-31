# Read-from-CSV
## AIM:
To write the program to read from csv.
## ALGORITHM:
### Step 1:
Import the pandas library as "pd".
### Step 2:
Read the CSV file "cars.csv" using read_csv() method and assign it to the variable "df".
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns and 'shape' attribute to find the dimensions of the dataframe.
### Step 5:
Print the output and end the program.
## PROGRAM:
```
#Program to read contents from a csv file
#Developed by : VEERARAGAVAN V
#RegisterNumaber : 212223230237
import pandas as pd
df=pd.read_csv('cars.csv')
print(df.head(10))
print(df.tail(5))
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
print(df.shape)
```
## OUTPUT:
![Screenshot 2023-12-31 135246](https://github.com/veerargavanv27/Read-from-CSV/assets/138955645/2d3f6b48-6f64-4509-b2c2-118d3d305f2c)
## RESULT:
Thus a python program is written to read the contents of a CSV file.
