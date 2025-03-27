# EXNO2DS
NAME:VIMALA RANI A

REG NO:212223040240
# AIM:
      To perform Exploratory Data Analysis on the given data set.
      
# EXPLANATION:
  The primary aim with exploratory analysis is to examine the data for distribution, outliers and anomalies to direct specific testing of your hypothesis.
  
# ALGORITHM:
STEP 1: Import the required packages to perform Data Cleansing,Removing Outliers and Exploratory Data Analysis.

STEP 2: Replace the null value using any one of the method from mode,median and mean based on the dataset available.

STEP 3: Use boxplot method to analyze the outliers of the given dataset.

STEP 4: Remove the outliers using Inter Quantile Range method.

STEP 5: Use Countplot method to analyze in a graphical method for categorical data.

STEP 6: Use displot method to represent the univariate distribution of data.

STEP 7: Use cross tabulation method to quantitatively analyze the relationship between multiple variables.

STEP 8: Use heatmap method of representation to show relationships between two variables, one plotted on each axis.

## CODING AND OUTPUT
        <<import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
df=pd.read_csv('/content/titanic_dataset.csv')
df

![Screenshot 2025-03-27 151434](https://github.com/user-attachments/assets/18452f3a-9b86-474f-9db4-58139a69b58c)

df.info()

![Screenshot 2025-03-27 151443](https://github.com/user-attachments/assets/3f24d5ba-03cf-4998-9f7f-c83967c7879d)

df.shape

![Screenshot 2025-03-27 151455](https://github.com/user-attachments/assets/11a1a07c-e48d-4f8b-b540-0cc8d1808ccb)

df.head(4)

![Screenshot 2025-03-27 151511](https://github.com/user-attachments/assets/55bbadea-d863-42d8-ab30-105868cbd2b2)

df.describe()

![Screenshot 2025-03-27 151524](https://github.com/user-attachments/assets/911a6f5a-a6f7-4db6-91ba-1ce25065698b)

df.set_index("PassengerId",inplace=True)
df.describe()

![Screenshot 2025-03-27 151536](https://github.com/user-attachments/assets/7407a822-014c-4d03-a4be-940544b33a5e)

>>

# RESULT
        Thus, the Exploratory Data Analysis on the given data set was performed successfully.
