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
Developed by: Sanjev R M
Register number:212223040186
```
```
import matplotlib.pyplot as plt
x1 = [1,2,3]
y1 = [2,4,1]
plt.plot(x1,y1,label="line 1")
x2 = [1,2,3]
y2 = [4,1,3]
plt.plot(x2,y2,label="line 2")
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```
![download](https://github.com/user-attachments/assets/d159a969-7840-4bad-816f-c832f7dface3)
```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')
plt.show()
```
![download](https://github.com/user-attachments/assets/8faa2031-2e4e-40ec-bac5-fca0c8d71346)
```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```
![download](https://github.com/user-attachments/assets/175cb6f3-005c-4361-b263-7aed621e6e92)
```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
```
![download](https://github.com/user-attachments/assets/f67b6813-01dd-48b6-8989-6cfb05203584)
```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
```
![download](https://github.com/user-attachments/assets/a5c309af-aeeb-4408-9ec2-722f566bbe25)
```
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.926,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896, ]
plt.plot(years, apples)
plt.plot(years, oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title('Crop Yields in Kanto')
plt.legend(['Apples','Oranges'])
```
![download](https://github.com/user-attachments/assets/83f15e3e-2f7f-4c11-8d9f-6e036070602e)
```
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yield of Oranges (tons per hectare)");
```
![download](https://github.com/user-attachments/assets/e2f5b68a-ea4a-4f93-9aca-3a6d3aad0337)
```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```
array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])
```
y
```
array([11, 12, 13, 14, 15, 16, 17, 18, 19, 20])
```
plt.scatter(x,y,c='r')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```
![download](https://github.com/user-attachments/assets/3f0a6a70-3c21-40fb-bcf6-5b06e6b5d6c3)
```
y=x*x
y
```
array([ 0,  1,  4,  9, 16, 25, 36, 49, 64, 81])
```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```
![download](https://github.com/user-attachments/assets/748883ce-1041-40cd-ac61-4633ffbb6a30)
```
np.pi
```
3.141592653589793
```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```
![download](https://github.com/user-attachments/assets/51e6a69c-c5a1-4cac-bf21-fcb4c5b19622)
```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')
```
![download](https://github.com/user-attachments/assets/3177e606-24a1-4eaf-99d3-375a1515ff3c)
```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')

plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My bar chart!')
plt.show()
```
![download](https://github.com/user-attachments/assets/240b54e3-554b-47c7-b7d6-f86949816abb)
![download](https://github.com/user-attachments/assets/2baad53d-0cfc-455d-a325-5b9fffb7111f)
```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
```
![download](https://github.com/user-attachments/assets/601937df-e36f-4f68-9c00-e2b9b2ffad43)
```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('My histogram')
plt.show()
```
![download](https://github.com/user-attachments/assets/1444142e-c166-4e52-acd6-e8a89bda447c)
```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![{8ED48DF2-DF28-4AA0-A533-C7CBAFB8F277}](https://github.com/user-attachments/assets/7d641197-ba3f-48fd-88c2-bbaf00640293)
```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
![download](https://github.com/user-attachments/assets/d811b4f0-5964-4e8f-8910-2fbe8af69a9d)
```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
![download](https://github.com/user-attachments/assets/a97675a1-855d-43dc-a1f5-a5e209f0e9f6)
```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
```
![download](https://github.com/user-attachments/assets/3340121c-bff8-44c9-a875-82a72fc03e56)










# Result:
Thus the program to Perform Data Visualization using matplot python library for the given datas is been implemented.
