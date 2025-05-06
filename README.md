# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

### Name: V.SAI SRUTHI
### Register Number: 212223100061

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
## Program:
```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```

```
 x = [1, 2, 3, 4, 5]
 y = [3, 6, 2, 7, 1]
```

```
plt.plot(x,y,label='line1')
```

![image](https://github.com/user-attachments/assets/8c8f9955-40f3-40b4-a3b9-5d2af6d7f7f9)

```
x1 = [1,2,3]
y1 = [2,4,1]
x2 = [1,2,3]
y2 = [4,1,3]
```

```
plt.plot(x1,y1,label='line1')
plt.plot(x2,y2,label='line2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```

![image](https://github.com/user-attachments/assets/f0b263ed-da5b-4309-937c-d407f1ecbca5)

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

![image](https://github.com/user-attachments/assets/f6db9731-5e21-4d3d-9207-7a458cc382ba)

```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```

![image](https://github.com/user-attachments/assets/2cf9156f-8e84-46e5-bc58-1c17d6800742)

```
 years=[2010,2011,2012,2013,2014,2015]
 yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
 plt.plot(years,yield_apples)
```

![image](https://github.com/user-attachments/assets/849e769f-9f84-4a11-a623-2a5e17bbea46)

```
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.926,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896, ]
plt.plot(years, apples)
plt.plot(years, oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title('Crop Yields in Kanto')
plt.legend(['Apples','Oranges']);
```

![image](https://github.com/user-attachments/assets/8e79dbd4-917a-406e-a272-f992680ba5c6)

```
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yield of Oranges (tons per hectare)");
```

![image](https://github.com/user-attachments/assets/0982d728-e535-4aeb-aa18-0a971630a364)

```
 import matplotlib.pyplot as plt
 import numpy as np
 import pandas as pd
 x=np.arange(0,10)
 y=np.arange(11,21)
 x
```

![image](https://github.com/user-attachments/assets/5da8ba6b-36e6-4f12-aeb8-f987056a8310)

```
y
```

![image](https://github.com/user-attachments/assets/8cbd0525-a85f-448c-b54a-7d8458e547d0)

```
 plt.scatter(x,y,c='r')
 plt.xlabel('X-axis')
 plt.ylabel('Y-axis')
 plt.title('Graph in 2D')
 plt.savefig('Test.png')
```

![image](https://github.com/user-attachments/assets/0eef8ad8-b7ab-43d3-b77c-3ebd51482eb7)

```
 y=x*x
 y
```

![image](https://github.com/user-attachments/assets/25ad5df9-0b39-4c4f-8551-67850166111e)

```
 plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
 plt.xlabel('X axis')
 plt.ylabel('Y axis')
 plt.title('2d Diagram')
 plt.legend(['y-values']);
```

![image](https://github.com/user-attachments/assets/3533301e-959b-4760-b014-d602d2f19cb6)

```
 x=np.arange(0,4*np.pi,0.1)
 y=np.sin(x)
 plt.title("sine wave form")
 plt.plot(x,y)
 plt.show()
```

![image](https://github.com/user-attachments/assets/c5a14b17-47ba-4a40-a0b6-4568b1c27b56)

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

![image](https://github.com/user-attachments/assets/ef874ebf-acab-4e33-8ad4-bd14c4fa0f26)

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
```

![image](https://github.com/user-attachments/assets/4de02bce-05c2-4fda-8a55-1f5dd6fcfa33)

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

![image](https://github.com/user-attachments/assets/fd30399e-c21c-4683-b3d4-7440ce493c29)

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

![image](https://github.com/user-attachments/assets/0df5a690-7cce-47b3-b792-fab4c617e0b2)

```
 import matplotlib.pyplot as plt
 ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
 range=(0,100)
 bins=10
 plt.hist(ages,bins,range,color='purple',histtype='bar',rwidth=0.8)
 plt.xlabel('age')
 plt.ylabel('No. of people')
 plt.title('My histogram')
 plt.show()
```

![image](https://github.com/user-attachments/assets/a481df7c-e4a4-41e6-862b-b5a08dbb841e)

```
 import matplotlib.pyplot as plt
 import numpy as np
 np.random.seed(0)
 data=np.random.normal(loc=0,scale=1,size=100)
 data
```

![image](https://github.com/user-attachments/assets/61e8422e-4a77-47b0-9889-599571dbbcaa)

```
 fig,ax=plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')
```

![image](https://github.com/user-attachments/assets/7facde23-ad52-4d8d-9dc8-2c095e994344)

```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```

![image](https://github.com/user-attachments/assets/7dff1557-c7b3-4c2f-8073-7514e971fb41)

```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
```

![image](https://github.com/user-attachments/assets/b8f66a37-3034-4777-b63f-f210adf614ab)




# Result:
Thus, The implementation of data visualization using matplotlib has been successfully verified.
