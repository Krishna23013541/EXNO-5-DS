# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY
### Name:KRISHNA KUMAR R
### REG:212223230107

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
 Include the necessary coding and corresponding screenshots

```
import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label='line1')
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label='line2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```
![Screenshot 2024-11-12 224311](https://github.com/user-attachments/assets/27c2c45e-1159-4e20-ac2a-2147205c2d5b)

```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,3,5,1,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='red',markersize=10)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')
plt.show()
```
![Screenshot 2024-11-12 224413](https://github.com/user-attachments/assets/705e06ec-4c1a-4048-b2d5-288f6a6b893c)


```

yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```
![Screenshot 2024-11-12 224452](https://github.com/user-attachments/assets/fdc8eadf-9087-4e85-aa50-ff33367ebadd)


```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
```
![Screenshot 2024-11-12 224547](https://github.com/user-attachments/assets/e9133316-cf34-4747-8c76-5205ae86ae13)


```
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
grapes=[0.926,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896, ]
plt.plot(years, apples)
plt.plot(years, grapes)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title('Crop Yields')
plt.legend(['Apples','grapes']);
```
![Screenshot 2024-11-12 224640](https://github.com/user-attachments/assets/c47b7ea4-f3e4-4e8d-baaa-7eab15095b4a)


```
plt.figure(figsize=(14,6))
plt.plot(years,grapes,marker='o')
plt.title("Yield of grapes (tons per hectare)");
```
![Screenshot 2024-11-12 224719](https://github.com/user-attachments/assets/622a9e5e-09e6-4e1a-8aff-1daa095994d3)


```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```
![Screenshot 2024-11-12 224758](https://github.com/user-attachments/assets/4a2d48c0-0760-412d-ab96-87d09d7e62f3)


```
y
```
![Screenshot 2024-11-12 224839](https://github.com/user-attachments/assets/30fb8f5c-61c2-4c4f-82e6-e373489b57e8)


```
plt.scatter(x,y,c='b')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```
![Screenshot 2024-11-12 224912](https://github.com/user-attachments/assets/649d3e73-1c37-4835-9b72-1fbb4da21f91)


```
y=x*x
y
```
![Screenshot 2024-11-12 224941](https://github.com/user-attachments/assets/f41b16ba-9653-40b6-a7b1-61827bd187db)


```
plt.plot(x,y,'y*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```
![Screenshot 2024-11-12 225037](https://github.com/user-attachments/assets/b30dc146-267d-4ac1-8eed-2459673de1b5)


```
np.pi
```
![Screenshot 2024-11-12 225136](https://github.com/user-attachments/assets/bd48e058-9a5e-4c12-b456-027e22d20624)


```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```
![Screenshot 2024-11-12 225210](https://github.com/user-attachments/assets/cb46bef0-eecd-48de-a88c-8ebbc77e7739)


```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='red')
plt.fill_between(x,y2,color='green')
```
![Screenshot 2024-11-12 225241](https://github.com/user-attachments/assets/7f710f41-05e1-4a12-b43b-191bb70b2bc6)


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
```
![Screenshot 2024-11-12 225314](https://github.com/user-attachments/assets/10d49375-9ee4-4000-b85b-a1863235db78)


```
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
![Screenshot 2024-11-12 225347](https://github.com/user-attachments/assets/cabc9269-6892-456b-b931-ac23f2f84f4b)


```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('Xaxis')
plt.show()
```
![Screenshot 2024-11-12 225436](https://github.com/user-attachments/assets/b1e9e160-b5ad-46bd-878e-e40ce19eac45)


```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='lightblue',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('My histogram')
plt.show()
```
![Screenshot 2024-11-12 225504](https://github.com/user-attachments/assets/9431fa07-6e92-4f47-a1ee-ba43d5e8e3ae)


```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![Screenshot 2024-11-12 225537](https://github.com/user-attachments/assets/ad9a0116-2bd9-46c7-9058-f58d979ecaf9)



```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
![Screenshot 2024-11-12 225609](https://github.com/user-attachments/assets/187cc7de-3632-4a85-acf8-30d3ca3a2dc8)

```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
![Screenshot 2024-11-12 225640](https://github.com/user-attachments/assets/5217c1c7-3412-400a-9e07-3a8c8879d2fd)


```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
```
![Screenshot 2024-11-12 225710](https://github.com/user-attachments/assets/e36fc4e6-c87e-4774-b726-997ad28a3a39)




# Result:
 Thus, The implementation of data visualization using matplotlib has been successfully verified.
