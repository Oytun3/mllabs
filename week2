import numpy as np 
import pandas as pd
t = (1,2,3,4)
t[1:3]
dictionary = {"name":["ali","veli","zübeyde","ahmet","kubra","can"],
             "age":[12,34,56,78,None,12],
             "note":[123,456,78,87654,None,89]}
dataframe1 = pd.DataFrame(dictionary) 
print(dataframe1)
df = pd.read_csv(r"C:\Users\User\Desktop\data.csv")
print(df)
head = dataframe1.head() 
print(head)
tail = dataframe1.tail()
print(tail)
print(dataframe1.columns)
print(dataframe1.info())
print(dataframe1.dtypes)
print(dataframe1.describe())
print(dataframe1["name"]) 
print(dataframe1.loc[:, "age"])            
dataframe1["new_future"] = [1,2,3,4,5,6] 
print(dataframe1.loc[:3,"age"])
print(dataframe1.loc[:3, "name":"note"])
print(dataframe1.loc[::-1])
print(dataframe1.loc[:, "new_feature"]) 
print(dataframe1.loc[:3, ["name","note"]])
print(dataframe1.loc[:,:"age"])
print(dataframe1.iloc[:,[2]])
filtre1 = dataframe1.age>10
dataframe1["bool"]= filtre1
print(dataframe1.loc[:,["age","bool"]])
type(filtre1)
filtrelenmis_data= dataframe1[filtre1] 
print(filtrelenmis_data)
filtre2 = dataframe1.note>100
filtrelenmis_data2 = dataframe1[filtre2&filtre1] 
print(filtrelenmis_data2)
dataframe1[dataframe1.age>20]
mean1 = dataframe1.note.mean()
print(mean1)
mean_np= np.mean(dataframe1.note) 
print(mean_np)
dataframe1.dropna(inplace=True) 
dataframe1
print(dataframe1.note.mean())
dataframe1["mean"]= ["bad" if dataframe1.note.mean()>each else "good" for each in dataframe1.note]
dataframe1
dataframe1.columns = [each.upper() for each in dataframe1.columns] 

dataframe1.columns
dataframe1.drop(["NEW_FUTURE"],axis=1,inplace=True)
dataframe1
data1 = dataframe1.head()     
data2 = dataframe1.tail()
data_concat = pd.concat([data1,data2],axis=0)
data_concat
data_contact2 = pd.concat([data1,data2],axis=1)
data_contact2
dataframe1["new_age"] = [each*2 for each in dataframe1.AGE]
dataframe1
