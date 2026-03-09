# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
```
 import matplotlib.pyplot as plt  
import numpy as np 
import pandas as pd


x=[2018,2019,2020,2021,2022]
y=[15000, 20000, 25000, 30000, 35000]
plt.plot(x,y,'g*', linestyle="dashed", linewidth=2,markersize=12)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('2D Diagram')
plt.show()
```
<img width="750" height="580" alt="image" src="https://github.com/user-attachments/assets/6ddaf82f-307b-4b21-86bd-82b4021e3703" />

# Result:
  Thus the data visualization was peformed using matplot python library for the given datas successfully.
