```python
#even or odd
a=int(input("enter your number"))
if(a%2==0):
    print("even")
else:
    print("odd")
```


```python
#creating a list
fruits=["apple","banana","mango","cherry","orange"]
print (fruits)
```


```python
#creating a programe to check which one is greater.
a=float(input(""))
b=float(input(""))
if(a>b):
 print("a is greater")
else:
 print("b is greater")

```


```python
#creating multiplication table by using userinput
number=int(input("enter your number"))
print("The Multiplication Table of: ", number)
for count in range(1, 11):
    print (number, 'x', count, '=', number * count)

```


```python
#creating a pattern 12345
rows=5
for i in range(1,rows+1):
    for j in range(1,i+1):
        print(j,end="")
    print() 

```


```python
#creating a pattern of 54321
for i in range(5, 0, -1):
    for j in range(i, 0, -1):
        print(j, end="")
    print()
```


```python
#creating a multiplication table of 24
x=24
for i in range(1,11):
    print (x,'*',i,'=',x*i)
```


```python
#to find the product of a set of a real number
i=0
product=1
count=int(input("enter the number of real number:"))
for i in range(count):
    x=float(input("enter a real number:"))
    product=product*x
    print("the product of the number is:",product)
```


```python
#to display the given integer in reverse manner ex-123=321
number=int(input("enter a positive integer:"))
rev=0
while(number!=0):
    digit=number%10
    rev=(rev*10)+digit
    number=number//10
print(rev)
```


```python
#to display the given integer in reverse order
for i in range(5,0,-1):
    for j in range(i,0,-1):
        print(j,end="")
        print()
```


```python
#to multiply of 5 within the range of 10-100
for i in range(10,100):
    if (i%5==0):
        print(i)

```


```python
# WAP to create a function show_employee
# i)it should accept employee name&salary&display both
# ii)if salary is missing in the function cell then assign default value 9000 to salary
def show_employee(name="Anshul",salary=9000):
    print("name",name,"salary",salary)
show_employee("Anshul",100000)
show_employee("Anshul")
show_employee()
```


```python
#file handling-writing a file
f=open("firstfile.txt","w")
f.write("Give it everything you've got and one day you shall best your struggles and come out as the winner")
```


```python
#file handling-opening a file
f=open("firstfile.txt","r")
print(f.readline())
```


```python
#Creating addition of number from user
a=float(input('please enter your numer'))
b=float(input('please enter your numer'))
sum=a+b
print(sum)
```


```python
#Creating empty list and append-1
A=[input("")]
B=[input("")]
A.append("")
B.append("")
print(A+B)
```


```python
#Creating empty list and append-2
A=[]
A.append(input(""))
A.append(input(""))
print(A)
```


```python
#Creating a list of fruits using append
a=[]
a.append("Mango")
a.append("Banana")
a.append("kiwi")
print(a)
```


```python
#Creating mini calculator
#Addition
A=float(input("please enter your no:"))
B=float(input("please enter your no:"))
sum=A+B
print("the Addition of your given number is:",sum)

#Substraction
A=float(input("please enter your no:"))
B=float(input("please enter your no:"))
sub=A-B
print("the Substraction of your given number is:",sub)

#division
A=float(input("please enter your no:"))
B=float(input("please enter your no:"))
mod=A%B
print("the division of your given number is:",mod)

#Remainder
A=float(input("please enter your no:"))
B=float(input("please enter your no:"))
rem=A/B
print("the Remainder of your given number is:",rem)

#Multiplication
A=float(input("please enter your no:"))
B=float(input("please enter your no:"))
mult=A*B
print("the Multiplication of your given number is:",mult)
```


```python
def factorial(n):
    p=1
    i=1
    while i<n:
        p=p*i
        i+=1
    return p
```


```python
#factorial of a number
def factorial(n):
    if n==0:
        return 1
    else:
        return n*factorial(n-1)
n=int(input("Input a number to compute the factorial:"))
print(factorial(n))
```


```python
#for making graph
import matplotlib.pyplot as plt
import numpy as np
xpoints = np.array([0,6])
ypoints = np.array([0,100])
plt.plot(xpoints,ypoints)
plt.show()
```


```python
#for making graph
import matplotlib.pyplot as plt
import numpy as np
xpoints = np.array([1,2,7,9])
ypoints = np.array([3,9,2,6])
#"*" for marker we can use anysign
plt.plot(xpoints,ypoints,marker="*")
plt.show()
```


```python
#for making graph
import matplotlib.pyplot as plt
import numpy as np
xpoints = np.array([1,2,7,9])
ypoints = np.array([3,9,2,6])
#"*" for marker we can use anysign + assigining colors in graph
plt.plot(xpoints,ypoints,marker="*",color="red")
plt.show()
```


```python
#for making graph
import matplotlib.pyplot as plt
import numpy as np
xpoints = np.array([1,2,7,9])
ypoints = np.array([3,9,2,6])
#"*" for marker we can use anysign + assigining colors in graph plus changing line style
plt.plot(xpoints,ypoints,marker="*",color="red",linestyle="dotted")
plt.show()
```


```python
#for making graph
import matplotlib.pyplot as plt
import numpy as np
xpoints = np.array([1,2,7,9])
ypoints = np.array([3,9,2,6])
#"*" for marker we can use anysign + assigining colors in graph
plt.plot(xpoints,ypoints,marker="*",color="red",linestyle="dashed")
plt.show()
```


```python
#for making graph
import matplotlib.pyplot as plt
import numpy as np
xpoints = np.array([1,2,7,9])
ypoints = np.array([3,9,2,6])
#"*" for marker we can use anysign + assigining colors in graph plus changing line style
plt.plot(xpoints,ypoints,marker="*",color="red",linestyle="solid")
plt.show()
```


```python
#for making graph
import matplotlib.pyplot as plt
import numpy as np
xpoints = np.array([1,2,7,9])
ypoints = np.array([3,9,2,6])
#"*" for marker we can use anysign + assigining colors in graph plus changing line style
plt.plot(xpoints,ypoints,marker="*",color="red",linestyle="dashdot")
plt.show()
```


```python
#for making graph
import matplotlib.pyplot as plt
import numpy as np
xpoints = np.array([1,2,7,9])
ypoints = np.array([3,9,2,6])
#"*" for marker we can use anysign + assigining colors in graph plus changing line style 
plt.plot(xpoints,ypoints,marker="*",color="purple",linestyle="dotted",linewidth="20")
plt.show()
```


```python
#for making graph
import matplotlib.pyplot as plt
import numpy as np

xpoints = np.array([1,2,7,9])
ypoints = np.array([3,9,2,6])
plt.plot(xpoints,ypoints,marker="*",color="purple",linestyle="dotted",linewidth="4")

x1points = np.array([5,4,3,2])
y1points = np.array([6,7,8,9])
plt.plot(x1points,y1points,marker="*",color="red",linestyle="dotted",linewidth="3")

x2points = np.array([2,6,8,0])
y2points = np.array([5,1,3,4])
plt.plot(x2points,y2points,marker="*",color="green",linestyle="dotted",linewidth="2")

plt.show()
```


```python
#python program to get average of a list
#importing the Numpy module
#taking a list of elements
import numpy as np
list = [2,4,4,4,5,5,7,9]
#calculating average using average()
print(np.average(list))
```


```python
#python program to get variance of a list 
import numpy as np 
list = [2,4,4,4,5,5,7,9]
print(np.var(list))
```


```python
#Standard deviation of a list
import numpy as np
list = [290,124,127,899]
#calculating standard
#deviation using var()
print(np.std(list))
```


```python
import numpy as np
arr=np.array([1,2,3,4,5])
print(arr)
print(type(arr))
```


```python
import numpy as np
arr=np.array([[[1,2,3],[4,5,6]],[[1,2,3],[4,5,6]]])
print(arr)
```
