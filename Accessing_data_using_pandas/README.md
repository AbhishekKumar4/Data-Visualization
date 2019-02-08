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
![alt text]()

````
print(df.head(5))
````
![alt text]()
