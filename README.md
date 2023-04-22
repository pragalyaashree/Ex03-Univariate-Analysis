# Ex03-Univariate-Analysis
## Aim :
To read the given data and perform the univariate analysis with different types of plots.

## Explanation :
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

## Algorithm:
## Step1:
Read the given data.

## Step2:
Get the information about the data.

## Step3:
Remove the null values from the data.

## Step4:
Mention the datatypes from the data.

## Step5:
Count the values from the data.

## Step6:
Do plots like boxplots,countplot,distribution plot,histogram plot.

## Program:
Developed By : R.K PRAGALYAA SHREE
Register Number : 212221040125
```
import pandas as pd
import numpy as np
import seaborn as sns

df=pd.read_csv('superstore.csv')
df

df.head()
df.info()
df.describe()
df.isnull().sum()

df.dtypes

df['Postal Code'].value_counts()

sns.boxplot(x='Postal Code', data=df)
sns.countplot(x='Postal Code',data=df)
sns.distplot(df["Postal Code"])
sns.histplot(x='Postal Code',data=df)
```
## Output :
## Dataset :
![10](https://user-images.githubusercontent.com/128135934/233770893-32a4681f-0c11-445b-aa8e-5facae1af195.png)

## Head :
![20](https://user-images.githubusercontent.com/128135934/233771003-c516c3c3-c8b8-4eb6-b78e-d1548d9d6938.png)

## Info :
![30](https://user-images.githubusercontent.com/128135934/233771024-b5f34fb7-28b3-4598-b24f-b91b6afcdf9e.png)

## Describe :
![40](https://user-images.githubusercontent.com/128135934/233771044-19120134-7a46-4499-a236-9526d9f467be.png)

## Isnull:
![50](https://user-images.githubusercontent.com/128135934/233771068-18c1ab58-b8b6-4ac4-8cac-b89a010f7a1f.png)

## dtypes :
![60](https://user-images.githubusercontent.com/128135934/233771110-313bc230-fcfc-4b76-a57b-c83b1d3f2806.png)

## Valuecount :
![70](https://user-images.githubusercontent.com/128135934/233771134-9d7cebfe-ca7f-42ee-b27b-5994d8e8b4cd.png)

## Boxplot :
![80](https://user-images.githubusercontent.com/128135934/233771158-791aab81-274b-424a-bb3c-a33aedf984db.png)

## Countplot :
![90](https://user-images.githubusercontent.com/128135934/233771177-0fd778bf-ecd0-4d48-8e3c-bcb760f0e6b8.png)

## Distribution plot :
![100](https://user-images.githubusercontent.com/128135934/233771199-c7073298-ddef-4024-85ba-7e2a19d87c96.png)

## Histogram plot :
![200](https://user-images.githubusercontent.com/128135934/233771224-e1ab6280-97d4-46f7-abb7-59be32fc608a.png)

## Result:
Thus we have read the given data and performed the univariate analysis with different types of plots.





