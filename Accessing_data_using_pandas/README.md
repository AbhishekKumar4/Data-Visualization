# Accessing Data with Pandas

**1. Import DataSet**

````
import pandas as pd
df = pd.read_csv('D:\\CrimeStatistics.csv')
````

**2. Describe gives you overview of dataset**
````
print(df.describe(include = 'all'))
````
![alt text](https://raw.githubusercontent.com/AbhishekKumar4/Data-Visualization/master/Accessing_data_using_pandas/images/dataframe_describe.PNG)

**3. Use head to see top n rows**
````
print(df.head(5))
````
![alt text](https://raw.githubusercontent.com/AbhishekKumar4/Data-Visualization/master/Accessing_data_using_pandas/images/df_head.PNG)

**4. Use tail(n) to see last n rows**
````
print(df.tail(5))
````
![alt text](https://raw.githubusercontent.com/AbhishekKumar4/Data-Visualization/master/Accessing_data_using_pandas/images/tail_func.PNG)

**5. df.columns to view all columns**
````
print(df.columns)
````
![alt text](https://raw.githubusercontent.com/AbhishekKumar4/Data-Visualization/master/Accessing_data_using_pandas/images/viewallcolumns.PNG)

**6. df.dtypes to view datatype of each column**
````
print(df.dtypes)
````
![alt text](https://github.com/AbhishekKumar4/Data-Visualization/blob/master/Accessing_data_using_pandas/images/column_data_type.PNG)

**7. Know the shape(number of rows x columns) of your data**
````
print(df.shape)
````
![alt text](https://raw.githubusercontent.com/AbhishekKumar4/Data-Visualization/master/Accessing_data_using_pandas/images/shape.PNG)
