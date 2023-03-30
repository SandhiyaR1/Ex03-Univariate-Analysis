# Ex03-Univariate-Analysis
# AIM:
To read the given data and perform the univariate analysis with different types of plots.

# ALGORITHM:
### STEP 1:
Read the given data.

### STEP 2:
Get the informations and type of datas.

### STEP 3:
Count the values using value_counts().

### STEP 4:
Describe the dataframe.

### STEP 5:
Do plots like boxplots,countplot,distribution plot,histogram plot

# PROGRAM:
# diabetes.csv
```
Developed by: Sandhiya R
Reference number:212222230129

import pandas as pd
data1=pd.read_csv("/content/diabetes.csv")
df1=pd.DataFrame(data1)
df1.info()
df1.dtypes
df1['BloodPressure'].value_counts()
df1.describe()
import seaborn as sns
sns.boxplot(x='BMI',data=df1)
sns.countplot(x='Age',data=df1)
sns.distplot(df1['BMI'])
sns.histplot(x='Age',data=df1)
df1.skew()
df.kurtosis()
```
# SuperStore.csv
```
import pandas as pd
data2=pd.read_csv("/content/SuperStore (1).csv")
df2=pd.DataFrame(data2)
df2.info()
df2.dtypes
df2["Postal Code"].value_counts()
df2.describe()
import seaborn as sns
sns.boxplot(x='Sales',data=df2)
sns.countplot(x="Sales",data=df2)
sns.distplot(df2['Sales'])
sns.histplot(x="Sales",data=df2)
df2.skew()

```
# OUTPUT
# diabetes.csv
### Info
![image](https://user-images.githubusercontent.com/113497571/228897270-c0c98ec4-1b4e-4dd4-a15e-ea1c773384a4.png)
### Datatypes
![image](https://user-images.githubusercontent.com/113497571/228897628-6ed32a70-0afa-479c-a321-b5187f5caba7.png)
### value count
![dsvaluecount](https://user-images.githubusercontent.com/113497571/228898935-1212fa08-0335-4de0-8411-7505cd40ea92.png)
### Describe
![image](https://user-images.githubusercontent.com/113497571/228899232-eeb86634-3960-47bf-9299-3ae99f30bdec.png)
### box plot
![dsboxplot](https://user-images.githubusercontent.com/113497571/228899771-92c75cf0-091d-4f20-8caa-8e1145b2ce59.png)
### countplot
![image](https://user-images.githubusercontent.com/113497571/228900167-cabbc5ee-0ebc-4b9b-bd8d-1ea932efc2aa.png)
### Distribution plot
![dsdisplot](https://user-images.githubusercontent.com/113497571/228900853-c77b3893-d46a-45d5-9439-d17d2449d01f.png)
### histogram
![image](https://user-images.githubusercontent.com/113497571/228901177-b7bf7a6f-bf31-436b-a7b5-df68684af1d8.png)
### skew()
![image](https://user-images.githubusercontent.com/113497571/228901489-48adbab2-380f-49e9-bbe3-d8e2ca3bc710.png)
### kurtosis()
![image](https://user-images.githubusercontent.com/113497571/228901598-bd1a827b-e2f2-4b9f-82b0-f49ee06cf855.png)
# SuperStore.csv
### Info
![image](https://user-images.githubusercontent.com/113497571/228902804-bb5feed6-d936-4e8b-a472-791dd444566b.png)

### Datatypes
![image](https://user-images.githubusercontent.com/113497571/228902893-8387a86b-896d-4bee-9390-f5ae27aa57ab.png)
### Valuecounts
![image](https://user-images.githubusercontent.com/113497571/228903125-2a43e92a-e30d-4f71-98ff-905d20eec578.png)

### Describe
![image](https://user-images.githubusercontent.com/113497571/228903239-b5367ea4-4f11-4c16-ac20-ea795482a67f.png)
### Boxplot
![image](https://user-images.githubusercontent.com/113497571/228903364-32fa540e-9b57-4b2a-84ae-d1bb7f60b08c.png)
### Countplot
![image](https://user-images.githubusercontent.com/113497571/228903771-5d2d5b9a-ee2a-487a-b937-999c6b2b95f1.png)
### Distribution plot
![image](https://user-images.githubusercontent.com/113497571/228903832-e3cbe24a-3a79-4ec5-b790-6714311b9d45.png)

### Histogram plot
![image](https://user-images.githubusercontent.com/113497571/228903964-749e8df0-6c4e-4c2f-aec6-b3e1a70a80ef.png)

### skew()
![image](https://user-images.githubusercontent.com/113497571/228904091-26b8b71b-4ceb-4093-bf3c-7e1c35138d2c.png)
# RESULT
To read the given data and perform the univariate analysis with different types of plots is done successfully.















