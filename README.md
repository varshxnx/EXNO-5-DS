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
NAME : VARSHINI S
REG NO : 212222220056
```
```
import matplotlib.pyplot as plt
x_val = [0,1,2,3,4,5]
y_val = [0,1,4,9,16,25]
plt.plot(x_val,y_val)
plt.show()
```
![image](https://github.com/varshxnx/EXNO-5-DS/assets/122253525/97b9aa5c-ea9c-44c3-9eab-27189241fe85)

```
import matplotlib.pyplot as plt
x = [1,2,3]
y = [2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph')
plt.show()
```
![image](https://github.com/varshxnx/EXNO-5-DS/assets/122253525/8e42f624-e639-47cf-a5c9-1b9342d7aca8)

```
import matplotlib.pyplot as plt
x1 = [1,2,3]
y1 = [2,5,3]
plt.plot(x1,y1,label = 'line 1')
x2 = [1,2,3]
y2 = [3,1,6]
plt.plot(x2,y2,label = 'line 2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title("Two lines on the same graph")
plt.legend()
plt.show()
```
![image](https://github.com/varshxnx/EXNO-5-DS/assets/122253525/6a175832-59cc-4f90-995b-3be1c84a6939)

```
import matplotlib.pyplot as plt
import numpy as np
x = [1,2,3,4,5]
y1 = [10,12,14,16,18]
y2 = [5,7,9,11,13]
y3 = [2,4,6,8,10]
plt.fill_between(x,y1,color = 'blue')
plt.fill_between(x,y2,color = 'orange')
```
![image](https://github.com/varshxnx/EXNO-5-DS/assets/122253525/51cbaa95-1cb6-431e-ad75-6f30b6ea6790)

```
plt.stackplot(x,y1,y2,y3,labels = ['line1','line2','line3'])
plt.legend(loc = 'upper left')
plt.title('Stacked line charts')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.show()
```
![image](https://github.com/varshxnx/EXNO-5-DS/assets/122253525/40b29b16-437b-45a5-8282-a3f83766820a)

```
import numpy as np
import matplotlib.pyplot as plt
val = [2,4,7,3]
names = ['A','B','C','D']
plt.bar(names, val,color = 'purple')
plt.show()
```
![image](https://github.com/varshxnx/EXNO-5-DS/assets/122253525/434878d5-3927-4c3d-b2ec-42e0fae8ae61)

```
import matplotlib.pyplot as plt
import numpy as np
ages = [2,6,4,12,13,12,16,18,18,19,26,24,39,34,45,42,54,56,90,56,86,79]
range = (0,100)
bins = 10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('no of people')
plt.title('histogram')
plt.show()
```
![image](https://github.com/varshxnx/EXNO-5-DS/assets/122253525/487aedfb-1b8a-46f4-ac8a-1a9e31ee616b)

```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![image](https://github.com/varshxnx/EXNO-5-DS/assets/122253525/26cec230-8da2-43f3-89f4-9f47d0b787bd)

```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel("data")
ax.set_ylabel("values")
ax.set_title("box plot")
```
![image](https://github.com/varshxnx/EXNO-5-DS/assets/122253525/d94160d5-7372-47af-9b19-f2f6fcefc1a5)

```
import matplotlib.pyplot as plt
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels = slices,colors=colors,startangle=90,shadow = True,explode = (0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
![image](https://github.com/varshxnx/EXNO-5-DS/assets/122253525/b4067a0f-ba7f-437d-954a-2dd29d30510b)


# Result:
  Thus, We have successfullu performed Data Visualization using matplot python library for the given datas.
